
// 1. Obtener pacientes mayores de edad
db.system.js.save({
  _id: "obtenerMayoresEdad",
  value: function() {
    return db.PACIENTE.find({ nacimiento: { $lt: new Date("2007-01-01") } }).toArray();
  }
});

// 2. Buscar médicos por especialidad
db.system.js.save({
  _id: "buscarMedicosEspecialidad",
  value: function(especialidad) {
    return db.MEDICO.find({ especialidad }).toArray();
  }
});

// 3. Contar pacientes por nombre
db.system.js.save({
  _id: "contarPacientesPorNombre",
  value: function(nombre) {
    return db.PACIENTE.countDocuments({ nombre: new RegExp(nombre, 'i') });
  }
});

// 4. Listar camas disponibles
db.system.js.save({
  _id: "listarCamasDisponibles",
  value: function() {
    return db.CAMA.find({ estado: "Disponible" }).toArray();
  }
});

// 5. Buscar pacientes por rango de edad
db.system.js.save({
  _id: "buscarPacientesPorEdad",
  value: function(min, max) {
    const hoy = new Date();
    const fechaMin = new Date(hoy.getFullYear() - max, hoy.getMonth(), hoy.getDate());
    const fechaMax = new Date(hoy.getFullYear() - min, hoy.getMonth(), hoy.getDate());
    return db.PACIENTE.find({ nacimiento: { $gte: fechaMin, $lte: fechaMax } }).toArray();
  }
});

// 6. Listar enfermeros por turno
db.system.js.save({
  _id: "listarEnfermerosPorTurno",
  value: function(turno) {
    return db.ENFERMERO.find({ turno }).toArray();
  }
});

// 7. Buscar medicamentos por nombre parcial
db.system.js.save({
  _id: "buscarMedicamentos",
  value: function(nombre) {
    return db.MEDICAMENTO.find({ nombre: new RegExp(nombre, 'i') }).toArray();
  }
});

// 8. Listar hospitales por nombre parcial
db.system.js.save({
  _id: "listarHospitalesPorNombre",
  value: function(nombre) {
    return db.HOSPITAL.find({ nombre: new RegExp(nombre, 'i') }).toArray();
  }
});

// 9. Buscar médicos por nombre
db.system.js.save({
  _id: "buscarMedicosPorNombre",
  value: function(nombre) {
    return db.MEDICO.find({ nombre: new RegExp(nombre, 'i') }).toArray();
  }
});

// 10. Buscar pacientes por dirección parcial
db.system.js.save({
  _id: "buscarPacientesPorDireccion",
  value: function(direccion) {
    return db.PACIENTE.find({ direccion: new RegExp(direccion, 'i') }).toArray();
  }
});

// 11. Listar EPS disponibles
db.system.js.save({
  _id: "listarEPS",
  value: function() {
    return db.EPS.find().toArray();
  }
});

// 12. Buscar médicos por especialidad usando agregación
db.system.js.save({
  _id: "agruparMedicosPorEspecialidad",
  value: function() {
    return db.MEDICO.aggregate([
      { $group: { _id: "$especialidad", total: { $sum: 1 } } }
    ]).toArray();
  }
});

// 13. Obtener todos los consultorios por piso
db.system.js.save({
  _id: "consultoriosPorPiso",
  value: function(piso) {
    return db.CONSULTORIO.find({ piso }).toArray();
  }
});

// 14. Buscar historia clínica por fecha de apertura
db.system.js.save({
  _id: "buscarHistoriaPorFecha",
  value: function(fecha) {
    return db.HISTORIA_CLINICA.find({ fecha_apertura: fecha }).toArray();
  }
});

// 15. Buscar cuidados por tipo
db.system.js.save({
  _id: "buscarCuidadosPorTipo",
  value: function(tipo) {
    return db.CUIDADO.find({ tipo }).toArray();
  }
});

// 16. Buscar servicios por nombre
db.system.js.save({
  _id: "buscarServicio",
  value: function(nombre) {
    return db.SERVICIO.find({ nombre: new RegExp(nombre, 'i') }).toArray();
  }
});

// 17. Buscar personal por rol
db.system.js.save({
  _id: "buscarPersonalPorRol",
  value: function(rol) {
    return db.PERSONAL.find({ rol }).toArray();
  }
});

// 18. Buscar diagnósticos por texto
db.system.js.save({
  _id: "buscarDiagnosticos",
  value: function(texto) {
    return db.DIAGNOSTICO.find({ descripcion: new RegExp(texto, 'i') }).toArray();
  }
});

// 19. Buscar tratamientos por indicación
db.system.js.save({
  _id: "buscarTratamientoPorIndicacion",
  value: function(texto) {
    return db.TRATAMIENTO.find({ indicaciones: new RegExp(texto, 'i') }).toArray();
  }
});

// 20. Contar camas por estado
db.system.js.save({
  _id: "contarCamasPorEstado",
  value: function() {
    return db.CAMA.aggregate([
      { $group: { _id: "$estado", total: { $sum: 1 } } }
    ]).toArray();
  }
});
