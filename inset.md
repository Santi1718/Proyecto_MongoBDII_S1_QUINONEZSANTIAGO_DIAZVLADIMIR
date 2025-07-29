# Inserciones MongoDB

## 1. MINSALUD

### Descripción

Contiene la entidad reguladora del sistema de salud colombiano.

```javascript
// Inserción de MINSALUD
db.MINSALUD.insertMany([
  {
    "nombre": "Ministerio de Salud de Colombia"
  }
]);
```

## 2. EPS

### Descripción

Entidad Promotora de Salud afiliada a pacientes.

```javascript
// Inserción de EPS
db.EPS.insertMany([
  { "id": "1", "nombre": "Salud Total" },
  { "id": "2", "nombre": "Sura" },
  { "id": "3", "nombre": "Sanitas" },
  { "id": "4", "nombre": "Nueva EPS" }
]);
```

## 3. HOSPITAL

### Descripción

Contiene información de los hospitales registrados.

```javascript
// Inserción de HOSPITAL
db.HOSPITAL.insertMany([
  {
    "id": "1",
    "nombre": "Hospital Central",
    "direccion": "Calle 123 #45-67, Bogotá"
  },
  {
    "id": "2",
    "nombre": "Clínica del Norte",
    "direccion": "Carrera 89 #12-34, Medellín"
  }
]);
```

## 4. PERSONAL

### Descripción

Contiene información sobre el personal administrativo u operativo.

```javascript
// Inserción de PERSONAL
db.PERSONAL.insertMany([
  { "id": "p1", "nombre": "Carlos Rueda", "rol": "Administrativo" },
  { "id": "p2", "nombre": "Ana López", "rol": "Auxiliar" }
]);
```

## 5. MEDICO

### Descripción

Contiene información de los médicos.

```javascript
// Inserción de MEDICO
db.MEDICO.insertMany([
  { "id": "m1", "nombre": "Juan Pérez", "especialidad": "Pediatría" },
  { "id": "m2", "nombre": "Laura Torres", "especialidad": "Cardiología" }
]);
```

## 6. PACIENTE

### Descripción

Contiene información de los pacientes afiliados a EPS y hospitales.

```javascript
// Inserción de PACIENTE
db.PACIENTE.insertMany([
  {
    "id": "p1001",
    "nombre": "Andrés González",
    "nacimiento": ISODate("1990-04-12"),
    "direccion": "Calle 8 #14-52, Cali"
  },
  {
    "id": "p1002",
    "nombre": "María Fernanda Ramírez",
    "nacimiento": ISODate("1985-11-20"),
    "direccion": "Carrera 23 #67-10, Bucaramanga"
  }
]);
```

## 7. CITA

```javascript
// Inserción de CITA
db.CITA.insertMany([
  { "id": "c1", "fecha": ISODate("2025-07-01"), "motivo": "Dolor de cabeza" },
  { "id": "c2", "fecha": ISODate("2025-07-03"), "motivo": "Chequeo general" }
]);
```

## 8. CONSULTORIO

```javascript
// Inserción de CONSULTORIO
db.CONSULTORIO.insertMany([
  { "id": "cs1", "numero": 101, "piso": "1" },
  { "id": "cs2", "numero": 202, "piso": "2" }
]);
```

## 9. HORA

```javascript
// Inserción de HORA
db.HORA.insertMany([
  { "hora_inicio": "08:00", "hora_fin": "09:00" },
  { "hora_inicio": "09:00", "hora_fin": "10:00" }
]);
```

## 10. HISTORIA\_CLINICA

```javascript
// Inserción de HISTORIA_CLINICA
db.HISTORIA_CLINICA.insertMany([
  { "id": "hc1", "fecha_apertura": ISODate("2023-01-01") },
  { "id": "hc2", "fecha_apertura": ISODate("2023-02-15") }
]);
```

## 11. DIAGNOSTICO

```javascript
// Inserción de DIAGNOSTICO
db.DIAGNOSTICO.insertMany([
  { "descripcion": "Gripe" },
  { "descripcion": "Bronquitis" }
]);
```

## 12. TRATAMIENTO

```javascript
// Inserción de TRATAMIENTO
db.TRATAMIENTO.insertMany([
  { "indicaciones": "Reposo por 3 días" },
  { "indicaciones": "Tomar antibítico cada 8 horas" }
]);
```

## 13. MEDICAMENTO

```javascript
// Inserción de MEDICAMENTO
db.MEDICAMENTO.insertMany([
  { "nombre": "Acetaminofén", "presentacion": "Tableta", "concentracion": "500mg" },
  { "nombre": "Amoxicilina", "presentacion": "Cápsula", "concentracion": "250mg" }
]);
```

## 14. CUIDADO

```javascript
// Inserción de CUIDADO
db.CUIDADO.insertMany([
  { "tipo": "Postoperatorio", "observaciones": "Paciente estable" },
  { "tipo": "Curación", "observaciones": "Herida cicatrizando bien" }
]);
```

## 15. SERVICIO

```javascript
// Inserción de SERVICIO
db.SERVICIO.insertMany([
  { "nombre": "Urgencias" },
  { "nombre": "Pediatría" },
  { "nombre": "Cirugía" }
]);
```

## 16. CAMA

```javascript
// Inserción de CAMA
db.CAMA.insertMany([
  { "id": "cam1", "estado": "Disponible", "numero": 1 },
  { "id": "cam2", "estado": "Ocupada", "numero": 2 }
]);
```
