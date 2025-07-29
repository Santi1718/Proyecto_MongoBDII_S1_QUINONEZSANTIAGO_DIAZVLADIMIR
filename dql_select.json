
// 1. Mostrar todos los pacientes
db.PACIENTE.find()

// 2. Buscar pacientes mayores de 60 años
db.PACIENTE.find({
  nacimiento: { $lt: new Date("1965-01-01") }
})

// 3. Encontrar pacientes llamados "Juan"
db.PACIENTE.find({ nombre: /Juan/i })

// 4. Mostrar todos los hospitales
db.HOSPITAL.find()

// 5. Mostrar todas las EPS registradas
db.EPS.find()

// 6. Buscar médicos por especialidad "Cardiología"
db.MEDICO.find({ especialidad: "Cardiología" })

// 7. Mostrar medicamentos disponibles
db.MEDICAMENTO.find()

// 8. Buscar pacientes nacidos después del año 2000
db.PACIENTE.find({ nacimiento: { $gt: new Date("2000-01-01") } })

// 9. Mostrar enfermeros de turno nocturno
db.ENFERMERO.find({ turno: "Nocturno" })

// 10. Mostrar camas disponibles
db.CAMA.find({ estado: "Disponible" })

// 11. Buscar medicamentos con nombre "Salbutamol"
db.MEDICAMENTO.find({ nombre: "Salbutamol" })

// 12. Buscar médicos cuyo nombre contenga "Lucía"
db.MEDICO.find({ nombre: /Lucía/i })

// 13. Buscar pacientes que vivan en una calle con número 100
db.PACIENTE.find({ direccion: /100/ })

// 14. Mostrar todos los servicios ofrecidos
db.SERVICIO.find()

// 15. Buscar citas agendadas para el 2025-08-01
db.CITA.find({ fecha: "2025-08-01" })

// 16. Buscar pacientes llamados "Laura Fernández"
db.PACIENTE.find({ nombre: "Laura Fernández" })

// 17. Listar todos los consultorios
db.CONSULTORIO.find()

// 18. Buscar diagnósticos que incluyan la palabra "aguda"
db.DIAGNOSTICO.find({ descripcion: /aguda/i })

// 19. Buscar tratamientos que incluyan "medicamento"
db.TRATAMIENTO.find({ indicaciones: /medicamento/i })

// 20. Mostrar horarios que empiecen a las 08:00
db.HORA.find({ hora_inicio: "08:00" })
// 21. Buscar pacientes nacidos antes de 1950
db.PACIENTE.find({ nacimiento: { $lt: new Date("1950-01-01") } })

// 22. Buscar pacientes que vivan en "Calle 50"
db.PACIENTE.find({ direccion: /Calle 50/i })

// 23. Mostrar médicos cuya especialidad sea "Pediatría"
db.MEDICO.find({ especialidad: "Pediatría" })

// 24. Listar todos los diagnósticos
db.DIAGNOSTICO.find()

// 25. Buscar pacientes con apellido "Ramírez"
db.PACIENTE.find({ nombre: /Ramírez/i })

// 26. Buscar pacientes con nombre que contenga "Suárez"
db.PACIENTE.find({ nombre: /Suárez/i })

// 27. Mostrar camas en mantenimiento
db.CAMA.find({ estado: "Mantenimiento" })

// 28. Listar consultorios del piso 3
db.CONSULTORIO.find({ piso: "3" })

// 29. Buscar medicamentos con concentración "400mg"
db.MEDICAMENTO.find({ concentracion: "400mg" })

// 30. Buscar horarios que terminan a las 10:30
db.HORA.find({ hora_fin: "10:30" })

// 31. Mostrar todas las historias clínicas
db.HISTORIA_CLINICA.find()

// 32. Buscar hospitales que tengan "Centro" en el nombre
db.HOSPITAL.find({ nombre: /Centro/i })

// 33. Listar médicos cuyo nombre contenga "Carlos"
db.MEDICO.find({ nombre: /Carlos/i })

// 34. Buscar tratamientos que mencionen "hielo"
db.TRATAMIENTO.find({ indicaciones: /hielo/i })

// 35. Mostrar pacientes nacidos en diciembre
db.PACIENTE.find({ nacimiento: { $regex: /-12-/ } })

// 36. Buscar pacientes nacidos entre 1990 y 2000
db.PACIENTE.find({
  nacimiento: {
    $gte: new Date("1990-01-01"),
    $lte: new Date("2000-12-31")
  }
})

// 37. Buscar personal con rol de "Enfermero"
db.PERSONAL.find({ rol: "Enfermero" })

// 38. Buscar cuidados de tipo "Curación"
db.CUIDADO.find({ tipo: "Curación" })

// 39. Mostrar EPS cuyo nombre contenga "Sura"
db.EPS.find({ nombre: /Sura/i })

// 40. Buscar citas con motivo que incluya "control"
db.CITA.find({ motivo: /control/i })

// 41. Mostrar pacientes con nombre que comience con "Andrés"
db.PACIENTE.find({ nombre: { $regex: /^Andrés/ } })

// 42. Mostrar médicos especializados en "Dermatología"
db.MEDICO.find({ especialidad: "Dermatología" })

// 43. Buscar citas con fecha posterior al 2025-08-02
db.CITA.find({ fecha: { $gt: "2025-08-02" } })

// 44. Buscar medicamentos cuya presentación sea "Tableta"
db.MEDICAMENTO.find({ presentacion: "Tableta" })

// 45. Listar camas con número mayor a 15
db.CAMA.find({ numero: { $gt: 15 } })

// 46. Buscar consultorios con número menor a 300
db.CONSULTORIO.find({ numero: { $lt: 300 } })

// 47. Buscar historias clínicas abiertas en el año 2025
db.HISTORIA_CLINICA.find({
  fecha_apertura: { $regex: /^2025/ }
})

// 48. Buscar pacientes con nombre que termine en "Ruiz"
db.PACIENTE.find({ nombre: { $regex: /Ruiz$/ } })

// 49. Mostrar todos los tipos de cuidado
db.CUIDADO.find().distinct("tipo")

// 50. Buscar médicos con apellido "Pérez"
db.MEDICO.find({ nombre: /Pérez/i })

// 51. Mostrar EPS cuyo nombre incluya "Coomeva"
db.EPS.find({ nombre: /Coomeva/i })

// 52. Buscar medicamentos con nombre que comience en "Ibu"
db.MEDICAMENTO.find({ nombre: { $regex: /^Ibu/ } })

// 53. Mostrar todos los turnos de enfermeros
db.ENFERMERO.find().distinct("turno")

// 54. Buscar pacientes nacidos en abril
db.PACIENTE.find({ nacimiento: { $regex: /-04-/ } })

// 55. Listar consultorios del piso 4
db.CONSULTORIO.find({ piso: "4" })

// 56. Buscar servicios que incluyan la palabra "Urgencias"
db.SERVICIO.find({ nombre: /Urgencias/i })

// 57. Buscar personal con nombre que contenga "Camila"
db.PERSONAL.find({ nombre: /Camila/i })

// 58. Buscar medicamentos que incluyan "azol" en el nombre
db.MEDICAMENTO.find({ nombre: /azol/i })

// 59. Mostrar camas con número exacto 21
db.CAMA.find({ numero: 21 })

// 60. Mostrar horarios que comiencen después de las 09:00
db.HORA.find({ hora_inicio: { $gt: "09:00" } })

// 61. Buscar pacientes con dirección que contenga "#10"
db.PACIENTE.find({ direccion: /#10/ })

// 62. Buscar médicos que no sean "Traumatología"
db.MEDICO.find({ especialidad: { $ne: "Traumatología" } })

// 63. Mostrar EPS ordenadas alfabéticamente
db.EPS.find().sort({ nombre: 1 })

// 64. Mostrar pacientes ordenados por fecha de nacimiento descendente
db.PACIENTE.find().sort({ nacimiento: -1 })

// 65. Buscar médicos cuyo nombre contenga "Luis"
db.MEDICO.find({ nombre: /Luis/i })

// 66. Buscar citas con motivo "Dolor abdominal"
db.CITA.find({ motivo: "Dolor abdominal" })

// 67. Listar consultorios cuyo número sea mayor que 100 y menor que 400
db.CONSULTORIO.find({ numero: { $gt: 100, $lt: 400 } })

// 68. Buscar pacientes que vivan en "Calle 1"
db.PACIENTE.find({ direccion: /Calle 1/i })

// 69. Mostrar medicamentos ordenados por concentración
db.MEDICAMENTO.find().sort({ concentracion: 1 })

// 70. Buscar turnos que no sean "Mixto"
db.ENFERMERO.find({ turno: { $ne: "Mixto" } })

// 71. Mostrar todas las direcciones de hospitales
db.HOSPITAL.find({}, { _id: 0, direccion: 1 })

// 72. Buscar pacientes cuyo nombre tenga exactamente "Pedro Suárez"
db.PACIENTE.find({ nombre: "Pedro Suárez" })

// 73. Mostrar solo los nombres de los médicos
db.MEDICO.find({}, { _id: 0, nombre: 1 })

// 74. Buscar medicamentos cuyo nombre contenga exactamente "Omeprazol"
db.MEDICAMENTO.find({ nombre: "Omeprazol" })

// 75. Buscar camas que no estén disponibles
db.CAMA.find({ estado: { $ne: "Disponible" } })

// 76. Buscar EPS que no sean "Sura"
db.EPS.find({ nombre: { $ne: "Sura" } })

// 77. Mostrar horarios cuyo fin sea antes de las 11:00
db.HORA.find({ hora_fin: { $lt: "11:00" } })

// 78. Buscar pacientes con nombre que incluya "Luisa"
db.PACIENTE.find({ nombre: /Luisa/i })

// 79. Mostrar diagnósticos que incluyan la palabra "leve"
db.DIAGNOSTICO.find({ descripcion: /leve/i })

// 80. Mostrar consultorios con número igual o mayor a 300
db.CONSULTORIO.find({ numero: { $gte: 300 } })

// 81. Contar pacientes que se llaman "María"
db.PACIENTE.aggregate([
  { $match: { nombre: /María/i } },
  { $count: "totalMaria" }
])


// 82. Agrupar médicos por especialidad y contar cuántos hay en cada una
db.MEDICO.aggregate([
  { $group: { _id: "$especialidad", total: { $sum: 1 } } }
])


// 83. Proyectar solo nombre y especialidad de los médicos
db.MEDICO.aggregate([
  { $project: { _id: 0, nombre: 1, especialidad: 1 } }
])


// 84. Buscar pacientes con nombre que contenga "Laura" usando $regex
db.PACIENTE.aggregate([
  { $match: { nombre: { $regex: /Laura/i } } }
])


// 85. Agrupar pacientes por década de nacimiento
db.PACIENTE.aggregate([
  {
    $project: {
      nombre: 1,
      decada: { $concat: [{ $substr: ["$nacimiento", 0, 3] }, "0s"] }
    }
  },
  { $group: { _id: "$decada", total: { $sum: 1 } } }
])


// 86. Listar todos los turnos únicos de enfermeros
db.ENFERMERO.aggregate([
  { $group: { _id: "$turno" } }
])


// 87. Proyectar EPS en mayúscula y sin ID
db.EPS.aggregate([
  { $project: { _id: 0, nombre: { $toUpper: "$nombre" } } }
])


// 88. Unir pacientes con sus citas (requiere campo pacienteId en CITA)
db.CITA.aggregate([
  {
    $lookup: {
      from: "PACIENTE",
      localField: "pacienteId",
      foreignField: "id",
      as: "paciente_info"
    }
  },
  { $unwind: "$paciente_info" },
  {
    $project: {
      _id: 0,
      fecha: 1,
      motivo: 1,
      "paciente_info.nombre": 1
    }
  }
])


// 89. Contar camas por estado
db.CAMA.aggregate([
  { $group: { _id: "$estado", cantidad: { $sum: 1 } } }
])


// 90. Unir hospital con sus EPS (requiere relación)
db.HOSPITAL.aggregate([
  {
    $lookup: {
      from: "EPS",
      localField: "eps_id",
      foreignField: "id",
      as: "eps_info"
    }
  }
])


// 91. Agrupar medicamentos por presentación
db.MEDICAMENTO.aggregate([
  { $group: { _id: "$presentacion", total: { $sum: 1 } } }
])


// 92. Proyectar cuidado sin _id
db.CUIDADO.aggregate([
  { $project: { _id: 0, tipo: 1, observaciones: 1 } }
])


// 93. Buscar médicos con "Díaz" en el nombre
db.MEDICO.aggregate([
  { $match: { nombre: { $regex: /Díaz/i } } }
])


// 94. Agrupar personal por rol
db.PERSONAL.aggregate([
  { $group: { _id: "$rol", cantidad: { $sum: 1 } } }
])


// 95. Unir consultorios con hospital (requiere relación)
db.CONSULTORIO.aggregate([
  {
    $lookup: {
      from: "HOSPITAL",
      localField: "hospitalId",
      foreignField: "id",
      as: "hospital"
    }
  }
])


// 96. Mostrar horarios que empiecen antes de las 10:00
db.HORA.aggregate([
  { $match: { hora_inicio: { $lt: "10:00" } } }
])


// 97. Agrupar historias clínicas por año de apertura
db.HISTORIA_CLINICA.aggregate([
  {
    $project: {
      año: { $substr: ["$fecha_apertura", 0, 4] }
    }
  },
  {
    $group: {
      _id: "$año",
      total: { $sum: 1 }
    }
  }
])


// 98. Contar EPS cuyo nombre contenga "EPS"
db.EPS.aggregate([
  { $match: { nombre: { $regex: /EPS/i } } },
  { $count: "totalEPS" }
])


// 99. Buscar tratamientos con indicaciones que incluyan "cada"
db.TRATAMIENTO.aggregate([
  { $match: { indicaciones: /cada/i } }
])


// 100. Agrupar médicos por especialidad y ordenar por cantidad
db.MEDICO.aggregate([
  { $group: { _id: "$especialidad", cantidad: { $sum: 1 } } },
  { $sort: { cantidad: -1 } }
])
