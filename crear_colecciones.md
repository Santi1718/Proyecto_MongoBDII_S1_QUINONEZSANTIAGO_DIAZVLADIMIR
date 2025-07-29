# Inserción Completa de Colecciones para el Sistema Hospitalario

## Colección: MINSALUD

```js
db.MINSALUD.insertMany([
  {"nombre": "Ministerio de Salud de Colombia"}
]);
```

## Colección: EPS

```js
db.EPS.insertMany([
  {"id": "eps01", "nombre": "Salud Total"},
  {"id": "eps02", "nombre": "Nueva EPS"},
  {"id": "eps03", "nombre": "Coomeva"},
  {"id": "eps04", "nombre": "Sura"}
]);
```

## Colección: HOSPITAL

```js
db.HOSPITAL.insertMany([
  {"id": "hos01", "nombre": "Hospital Central", "direccion": "Calle 100 #25-30"},
  {"id": "hos02", "nombre": "Clínica Norte", "direccion": "Carrera 45 #11-50"},
  {"id": "hos03", "nombre": "Hospital del Sur", "direccion": "Carrera 12 #65-12"},
  {"id": "hos04", "nombre": "Centro Médico San Juan", "direccion": "Calle 45 #30-20"}
]);
```

## Colección: PACIENTE

```js
db.PACIENTE.insertMany([
  {"id": "eb7fff59", "nombre": "Juan Ruiz", "nacimiento": "1998-01-13", "direccion": "Calle 8 #50-94"},
  {"id": "45000976", "nombre": "Pedro Ruiz", "nacimiento": "1959-10-13", "direccion": "Calle 98 #75-69"},
  {"id": "d11d2f31", "nombre": "María Fernández", "nacimiento": "1955-07-20", "direccion": "Calle 98 #36-44"},
  {"id": "534dc742", "nombre": "Laura Ramírez", "nacimiento": "1988-08-24", "direccion": "Calle 80 #38-85"},
  {"id": "d5a9645c", "nombre": "Andrés Suárez", "nacimiento": "1999-04-26", "direccion": "Calle 56 #10-89"},
  {"id": "449e8b46", "nombre": "Laura Fernández", "nacimiento": "1963-03-16", "direccion": "Calle 10 #95-10"},
  {"id": "14f8987c", "nombre": "Pedro Ramírez", "nacimiento": "2012-12-17", "direccion": "Calle 77 #55-37"},
  {"id": "d0463d78", "nombre": "Juan Ramírez", "nacimiento": "2008-04-08", "direccion": "Calle 35 #45-21"},
  {"id": "edcdb0dc", "nombre": "Luisa Fernández", "nacimiento": "1998-12-31", "direccion": "Calle 27 #98-89"},
  {"id": "76a62a3c", "nombre": "Laura Fernández", "nacimiento": "1950-03-25", "direccion": "Calle 14 #67-84"},
  {"id": "230d3679", "nombre": "María Ruiz", "nacimiento": "2006-04-16", "direccion": "Calle 11 #38-16"},
  {"id": "d58f3b09", "nombre": "Pedro Fernández", "nacimiento": "1966-12-23", "direccion": "Calle 50 #59-35"},
  {"id": "d0162bb8", "nombre": "Pedro Suárez", "nacimiento": "1958-05-29", "direccion": "Calle 10 #67-74"},
  {"id": "55a5f324", "nombre": "María Ramírez", "nacimiento": "1974-09-11", "direccion": "Calle 67 #73-54"},
  {"id": "13b2f810", "nombre": "María Suárez", "nacimiento": "1966-10-02", "direccion": "Calle 16 #91-92"},
  {"id": "123fd4ca", "nombre": "Andrés Suárez", "nacimiento": "1950-12-04", "direccion": "Calle 3 #39-36"},
  {"id": "6520abd5", "nombre": "Luisa Fernández", "nacimiento": "1951-06-14", "direccion": "Calle 3 #20-92"},
  {"id": "5962f650", "nombre": "María Suárez", "nacimiento": "1959-07-21", "direccion": "Calle 100 #88-2"},
  {"id": "5a8dd9f5", "nombre": "Andrés Ramírez", "nacimiento": "1961-05-18", "direccion": "Calle 50 #33-89"},
  {"id": "c0df74d0", "nombre": "María Fernández", "nacimiento": "1991-09-04", "direccion": "Calle 8 #33-28"},
  {"id": "efe59c86", "nombre": "Luisa Fernández", "nacimiento": "1978-10-10", "direccion": "Calle 1 #55-52"},
  {"id": "5de35b9b", "nombre": "María Ramírez", "nacimiento": "2002-01-13", "direccion": "Calle 86 #84-1"},
  {"id": "1745c048", "nombre": "Luisa Fernández", "nacimiento": "1952-04-07", "direccion": "Calle 100 #65-97"},
  {"id": "0abe8e94", "nombre": "María Ruiz", "nacimiento": "1951-07-04", "direccion": "Calle 78 #68-91"},
  {"id": "bffe29ff", "nombre": "Juan Ruiz", "nacimiento": "1996-08-04", "direccion": "Calle 47 #33-84"},
  {"id": "02a97b57", "nombre": "Juan Suárez", "nacimiento": "1987-03-05", "direccion": "Calle 57 #27-40"},
  {"id": "86150b60", "nombre": "Andrés Ramírez", "nacimiento": "2001-06-07", "direccion": "Calle 57 #38-81"},
  {"id": "ef1e30de", "nombre": "Juan Suárez", "nacimiento": "2006-12-25", "direccion": "Calle 76 #28-85"},
  {"id": "4941c974", "nombre": "Pedro Suárez", "nacimiento": "1951-04-24", "direccion": "Calle 72 #63-18"},
  {"id": "17b6de4f", "nombre": "Juan Ruiz", "nacimiento": "1962-10-08", "direccion": "Calle 68 #100-44"},
  {"id": "4dbb27bb", "nombre": "María Suárez", "nacimiento": "1995-09-24", "direccion": "Calle 97 #33-44"},
  {"id": "1bb06840", "nombre": "Luisa Ramírez", "nacimiento": "1977-02-15", "direccion": "Calle 68 #65-99"},
  {"id": "4ce80057", "nombre": "Laura Ruiz", "nacimiento": "1963-02-25", "direccion": "Calle 97 #58-60"},
  {"id": "565f724e", "nombre": "María Ruiz", "nacimiento": "1998-12-28", "direccion": "Calle 67 #74-82"},
  {"id": "a7a9a823", "nombre": "María Ramírez", "nacimiento": "1952-03-30", "direccion": "Calle 90 #19-73"},
  {"id": "436ad9f7", "nombre": "Juan Ruiz", "nacimiento": "1985-10-13", "direccion": "Calle 94 #99-100"},
  {"id": "5f3767ea", "nombre": "María Suárez", "nacimiento": "1992-06-14", "direccion": "Calle 85 #58-85"},
  {"id": "c99744d1", "nombre": "Laura Ramírez", "nacimiento": "2015-04-08", "direccion": "Calle 5 #38-40"},
  {"id": "4c57606a", "nombre": "Laura Suárez", "nacimiento": "1997-12-22", "direccion": "Calle 81 #81-65"},
  {"id": "e8a49216", "nombre": "Andrés Fernández", "nacimiento": "1986-05-26", "direccion": "Calle 83 #9-15"},
  {"id": "b0efb498", "nombre": "Juan Ramírez", "nacimiento": "1959-01-05", "direccion": "Calle 91 #75-28"},
  {"id": "51f863be", "nombre": "Pedro Ramírez", "nacimiento": "1998-11-28", "direccion": "Calle 63 #54-69"},
  {"id": "ef724923", "nombre": "Andrés Fernández", "nacimiento": "1981-07-18", "direccion": "Calle 81 #2-32"},
  {"id": "607a90bc", "nombre": "Andrés Suárez", "nacimiento": "1992-07-11", "direccion": "Calle 52 #39-11"},
  {"id": "be837125", "nombre": "Juan Fernández", "nacimiento": "1975-07-05", "direccion": "Calle 4 #93-95"},
  {"id": "f07b0ea8", "nombre": "Pedro Ruiz", "nacimiento": "1982-11-10", "direccion": "Calle 21 #15-81"},
  {"id": "354ced1c", "nombre": "Juan Suárez", "nacimiento": "2009-12-14", "direccion": "Calle 46 #60-88"},
  {"id": "d76a33ac", "nombre": "María Ramírez", "nacimiento": "1996-04-06", "direccion": "Calle 69 #15-65"},
  {"id": "ce2c9f06", "nombre": "Laura Fernández", "nacimiento": "1957-01-22", "direccion": "Calle 12 #92-17"},
  {"id": "3069a0ab", "nombre": "Pedro Ruiz", "nacimiento": "2014-03-13", "direccion": "Calle 93 #99-20"},
  {"id": "7fc88fec", "nombre": "Juan Suárez", "nacimiento": "2004-04-16", "direccion": "Calle 82 #62-61"},
  {"id": "c76d3a4d", "nombre": "Pedro Suárez", "nacimiento": "1958-01-02", "direccion": "Calle 34 #3-77"},
  {"id": "57a55683", "nombre": "Andrés Suárez", "nacimiento": "1979-10-14", "direccion": "Calle 3 #65-52"},
  {"id": "28004f70", "nombre": "María Ramírez", "nacimiento": "1960-04-22", "direccion": "Calle 53 #77-85"},
  {"id": "550ae032", "nombre": "María Ruiz", "nacimiento": "1951-10-15", "direccion": "Calle 13 #67-58"},
  {"id": "2e6e915a", "nombre": "María Ramírez", "nacimiento": "2011-01-04", "direccion": "Calle 57 #67-69"},
  {"id": "2f520bb9", "nombre": "Pedro Ramírez", "nacimiento": "1968-08-02", "direccion": "Calle 35 #46-79"},
  {"id": "647480d5", "nombre": "Pedro Fernández", "nacimiento": "1954-03-31", "direccion": "Calle 59 #11-94"},
  {"id": "d49b77ac", "nombre": "Laura Fernández", "nacimiento": "1974-08-04", "direccion": "Calle 15 #13-13"},
  {"id": "3ab2958b", "nombre": "María Ruiz", "nacimiento": "1962-05-11", "direccion": "Calle 38 #34-5"},
  {"id": "8ca7cb56", "nombre": "María Fernández", "nacimiento": "1995-04-30", "direccion": "Calle 93 #57-34"},
  {"id": "b6922883", "nombre": "Juan Suárez", "nacimiento": "2007-06-09", "direccion": "Calle 87 #13-9"},
  {"id": "5d1c68ea", "nombre": "Juan Ruiz", "nacimiento": "1991-04-07", "direccion": "Calle 88 #37-7"},
  {"id": "e2226910", "nombre": "María Suárez", "nacimiento": "1972-02-26", "direccion": "Calle 49 #27-25"},
  {"id": "adacddc9", "nombre": "Laura Suárez", "nacimiento": "2015-01-01", "direccion": "Calle 4 #10-89"},
  {"id": "f2c45a6c", "nombre": "María Ruiz", "nacimiento": "1968-08-22", "direccion": "Calle 3 #84-57"},
  {"id": "5b38a251", "nombre": "Andrés Suárez", "nacimiento": "1955-02-01", "direccion": "Calle 23 #68-30"},
  {"id": "5aaf75fb", "nombre": "Andrés Fernández", "nacimiento": "1983-06-21", "direccion": "Calle 55 #83-3"},
  {"id": "ec8082a9", "nombre": "Pedro Ramírez", "nacimiento": "1987-04-28", "direccion": "Calle 94 #80-69"},
  {"id": "29873815", "nombre": "Laura Ruiz", "nacimiento": "1961-01-01", "direccion": "Calle 1 #69-97"},
  {"id": "131f5977", "nombre": "Laura Fernández", "nacimiento": "1985-09-24", "direccion": "Calle 56 #67-59"},
  {"id": "c401fc6f", "nombre": "Laura Suárez", "nacimiento": "1973-01-22", "direccion": "Calle 43 #22-47"},
  {"id": "c3567cfc", "nombre": "Andrés Ruiz", "nacimiento": "1988-04-16", "direccion": "Calle 37 #27-50"},
  {"id": "351f9093", "nombre": "Andrés Ramírez", "nacimiento": "2004-08-15", "direccion": "Calle 35 #25-27"},
  {"id": "19240bdf", "nombre": "María Ramírez", "nacimiento": "1959-12-15", "direccion": "Calle 4 #88-24"},
  {"id": "3b878d9f", "nombre": "Pedro Suárez", "nacimiento": "1989-10-13", "direccion": "Calle 90 #79-33"},
  {"id": "41aee25a", "nombre": "María Fernández", "nacimiento": "2010-10-15", "direccion": "Calle 90 #2-80"},
  {"id": "44284db4", "nombre": "María Ramírez", "nacimiento": "2010-03-17", "direccion": "Calle 12 #75-87"},
  {"id": "c8edc40d", "nombre": "Laura Ruiz", "nacimiento": "1967-08-08", "direccion": "Calle 86 #54-47"},
  {"id": "3847f012", "nombre": "Pedro Suárez", "nacimiento": "1960-07-07", "direccion": "Calle 22 #14-50"},
  {"id": "9fe4e0d6", "nombre": "Andrés Fernández", "nacimiento": "1967-02-17", "direccion": "Calle 58 #39-79"},
  {"id": "da6dbea1", "nombre": "Juan Fernández", "nacimiento": "1977-01-09", "direccion": "Calle 100 #11-95"},
  {"id": "938e74d4", "nombre": "Laura Suárez", "nacimiento": "1986-12-02", "direccion": "Calle 48 #100-48"},
  {"id": "dfbd1407", "nombre": "Laura Ruiz", "nacimiento": "1961-07-31", "direccion": "Calle 46 #20-50"},
  {"id": "9f1b95c9", "nombre": "Luisa Ruiz", "nacimiento": "1952-05-30", "direccion": "Calle 96 #10-98"},
  {"id": "8fb6e1f8", "nombre": "Pedro Fernández", "nacimiento": "1959-04-24", "direccion": "Calle 65 #56-44"},
  {"id": "1da74d1e", "nombre": "Laura Suárez", "nacimiento": "1975-12-31", "direccion": "Calle 4 #35-88"},
  {"id": "88cba76f", "nombre": "Laura Fernández", "nacimiento": "2004-08-30", "direccion": "Calle 54 #45-36"},
  {"id": "dc165568", "nombre": "Andrés Ruiz", "nacimiento": "1970-02-15", "direccion": "Calle 55 #71-20"},
  {"id": "8b157d58", "nombre": "Pedro Ramírez", "nacimiento": "1962-03-18", "direccion": "Calle 56 #65-9"},
  {"id": "1b0d0571", "nombre": "Pedro Ruiz", "nacimiento": "1971-07-03", "direccion": "Calle 36 #90-100"},
  {"id": "9f2547b9", "nombre": "María Suárez", "nacimiento": "1980-04-26", "direccion": "Calle 81 #12-80"},
  {"id": "13f8bf59", "nombre": "Laura Ruiz", "nacimiento": "1955-06-20", "direccion": "Calle 3 #24-5"},
  {"id": "29f79835", "nombre": "Laura Suárez", "nacimiento": "1980-12-03", "direccion": "Calle 57 #12-99"},
  {"id": "51b0ac10", "nombre": "Luisa Suárez", "nacimiento": "1997-09-30", "direccion": "Calle 45 #15-61"},
  {"id": "6ab9fe55", "nombre": "Juan Ramírez", "nacimiento": "1957-03-28", "direccion": "Calle 58 #57-81"},
  {"id": "edc40735", "nombre": "Pedro Fernández", "nacimiento": "1979-05-12", "direccion": "Calle 31 #90-51"},
  {"id": "9c3135d5", "nombre": "Luisa Ramírez", "nacimiento": "1995-12-06", "direccion": "Calle 85 #78-15"},
  {"id": "3626a8cb", "nombre": "Laura Suárez", "nacimiento": "2010-10-27", "direccion": "Calle 87 #34-2"},
  {"id": "e82265b2", "nombre": "Juan Suárez", "nacimiento": "1973-10-15", "direccion": "Calle 28 #35-12"}
]);
```

## Colección: MEDICO

```js
db.MEDICO.insertMany([
  {"id": "13b70898", "nombre": "Dr. Marta Díaz", "especialidad": "Traumatología"},
  {"id": "5c3d726e", "nombre": "Dr. Jorge Rodríguez", "especialidad": "Oncología"},
  {"id": "6e65fc47", "nombre": "Dr. Carlos Gómez", "especialidad": "Cardiología"},
  {"id": "3ab5609b", "nombre": "Dr. Ana Rodríguez", "especialidad": "Dermatología"},
  {"id": "62219929", "nombre": "Dr. Marta Gómez", "especialidad": "Neurología"},
  {"id": "444509cc", "nombre": "Dr. Jorge Gómez", "especialidad": "Psiquiatría"},
  {"id": "d3d15498", "nombre": "Dr. Luis Rodríguez", "especialidad": "Traumatología"},
  {"id": "b7a6302e", "nombre": "Dr. Carlos Rodríguez", "especialidad": "Cardiología"},
  {"id": "71c994b2", "nombre": "Dr. Lucía Rodríguez", "especialidad": "Medicina Interna"},
  {"id": "51e4abd8", "nombre": "Dr. Ana Pérez", "especialidad": "Traumatología"},
  {"id": "083e8151", "nombre": "Dr. Carlos Díaz", "especialidad": "Medicina Interna"},
  {"id": "dd34413f", "nombre": "Dr. Lucía Díaz", "especialidad": "Psiquiatría"},
  {"id": "d049af94", "nombre": "Dr. Carlos Rodríguez", "especialidad": "Cardiología"},
  {"id": "c7da90de", "nombre": "Dr. Ana Díaz", "especialidad": "Oncología"},
  {"id": "f9903cae", "nombre": "Dr. Ana Rodríguez", "especialidad": "Traumatología"},
  {"id": "fc8e9a9f", "nombre": "Dr. Lucía Díaz", "especialidad": "Psiquiatría"},
  {"id": "fe91726a", "nombre": "Dr. Jorge Pérez", "especialidad": "Psiquiatría"},
  {"id": "ab8a91a1", "nombre": "Dr. Lucía Rodríguez", "especialidad": "Ginecología"},
  {"id": "a86f33a1", "nombre": "Dr. Luis Gómez", "especialidad": "Pediatría"},
  {"id": "f3136437", "nombre": "Dr. Luis Rodríguez", "especialidad": "Pediatría"},
  {"id": "80e0f100", "nombre": "Dr. Luis Gómez", "especialidad": "Neurología"},
  {"id": "8d22b871", "nombre": "Dr. Jorge Díaz", "especialidad": "Ginecología"},
  {"id": "72079370", "nombre": "Dr. Carlos Rodríguez", "especialidad": "Dermatología"},
  {"id": "5bb3ef6c", "nombre": "Dr. Lucía Gómez", "especialidad": "Ginecología"},
  {"id": "b00965f8", "nombre": "Dr. Carlos Díaz", "especialidad": "Traumatología"},
  {"id": "925e0ccb", "nombre": "Dr. Ana Rodríguez", "especialidad": "Urología"},
  {"id": "942c8985", "nombre": "Dr. Marta Gómez", "especialidad": "Psiquiatría"},
  {"id": "791120f5", "nombre": "Dr. Carlos Pérez", "especialidad": "Medicina Interna"},
  {"id": "74b6dc9a", "nombre": "Dr. Carlos Rodríguez", "especialidad": "Ginecología"},
  {"id": "22d2585f", "nombre": "Dr. Jorge Rodríguez", "especialidad": "Dermatología"},
  {"id": "2bdee2cf", "nombre": "Dr. Luis Pérez", "especialidad": "Cardiología"},
  {"id": "b889eb27", "nombre": "Dr. Marta Gómez", "especialidad": "Oncología"},
  {"id": "6e1b1455", "nombre": "Dr. Luis Gómez", "especialidad": "Pediatría"},
  {"id": "27cee250", "nombre": "Dr. Luis Díaz", "especialidad": "Oncología"},
  {"id": "cd7ac285", "nombre": "Dr. Ana Gómez", "especialidad": "Dermatología"},
  {"id": "11b2d9b8", "nombre": "Dr. Jorge Pérez", "especialidad": "Ginecología"},
  {"id": "ca310090", "nombre": "Dr. Lucía Rodríguez", "especialidad": "Urología"},
  {"id": "c29e3d9c", "nombre": "Dr. Lucía Pérez", "especialidad": "Pediatría"},
  {"id": "46355b7b", "nombre": "Dr. Carlos Díaz", "especialidad": "Cardiología"},
  {"id": "b4c0cf00", "nombre": "Dr. Lucía Gómez", "especialidad": "Cardiología"},
  {"id": "1a4de3a5", "nombre": "Dr. Carlos Díaz", "especialidad": "Urología"},
  {"id": "2d7d737a", "nombre": "Dr. Carlos Díaz", "especialidad": "Neurología"},
  {"id": "ce5e297f", "nombre": "Dr. Jorge Díaz", "especialidad": "Oncología"},
  {"id": "b38e968a", "nombre": "Dr. Luis Rodríguez", "especialidad": "Dermatología"},
  {"id": "c89ae538", "nombre": "Dr. Carlos Rodríguez", "especialidad": "Dermatología"},
  {"id": "47a11a64", "nombre": "Dr. Marta Díaz", "especialidad": "Ginecología"},
  {"id": "99232b7d", "nombre": "Dr. Carlos Gómez", "especialidad": "Neurología"},
  {"id": "1d963c46", "nombre": "Dr. Marta Pérez", "especialidad": "Ginecología"},
  {"id": "d73b3798", "nombre": "Dr. Carlos Gómez", "especialidad": "Medicina Interna"},
  {"id": "de10c5a8", "nombre": "Dr. Jorge Pérez", "especialidad": "Traumatología"}
]);
```

## Colección: ENFERMERO

```js
db.ENFERMERO.insertMany([
  {"id": "enf01", "nombre": "Pedro Jiménez", "turno": "Diurno"},
  {"id": "enf02", "nombre": "Luisa Torres", "turno": "Nocturno"},
  {"id": "enf03", "nombre": "Carlos Herrera", "turno": "Mixto"},
  {"id": "enf04", "nombre": "Natalia López", "turno": "Diurno"}
]);
```

## Colección: CITA

```js
db.CITA.insertMany([
  {"id": "cit01", "fecha": "2025-08-01", "motivo": "Chequeo general"},
  {"id": "cit02", "fecha": "2025-08-02", "motivo": "Consulta de control"},
  {"id": "cit03", "fecha": "2025-08-03", "motivo": "Evaluación postoperatoria"},
  {"id": "cit04", "fecha": "2025-08-04", "motivo": "Dolor abdominal"}
]);
```

## Colección: CONSULTORIO

```js
db.CONSULTORIO.insertMany([
  {"id": "con01", "numero": 101, "piso": "1"},
  {"id": "con02", "numero": 202, "piso": "2"},
  {"id": "con03", "numero": 305, "piso": "3"},
  {"id": "con04", "numero": 410, "piso": "4"}
]);
```

## Colección: HISTORIA_CLINICA

```js
db.HISTORIA_CLINICA.insertMany([
  {"id": "his01", "fecha_apertura": "2024-12-01"},
  {"id": "his02", "fecha_apertura": "2025-01-10"},
  {"id": "his03", "fecha_apertura": "2025-02-15"},
  {"id": "his04", "fecha_apertura": "2025-03-01"}
]);
```

## Colección: DIAGNOSTICO

```js
db.DIAGNOSTICO.insertMany([
  {"descripcion": "Hipertensión arterial"},
  {"descripcion": "Asma leve"},
  {"descripcion": "Gastritis aguda"},
  {"descripcion": "Fractura de muñeca"}
]);
```

## Colección: TRATAMIENTO

```js
db.TRATAMIENTO.insertMany([
  {"indicaciones": "Tomar medicamento cada 8 horas"},
  {"indicaciones": "Evitar exposición a alérgenos"},
  {"indicaciones": "Aplicar hielo cada 6 horas"},
  {"indicaciones": "Tomar omeprazol en ayunas"}
]);
```

## Colección: MEDICAMENTO

```js
db.MEDICAMENTO.insertMany([
  {"nombre": "Losartán", "presentacion": "Tableta", "concentracion": "50mg"},
  {"nombre": "Salbutamol", "presentacion": "Inhalador", "concentracion": "100mcg"},
  {"nombre": "Ibuprofeno", "presentacion": "Tableta", "concentracion": "400mg"},
  {"nombre": "Omeprazol", "presentacion": "Cápsula", "concentracion": "20mg"}
]);
```

## Colección: CUIDADO

```js
db.CUIDADO.insertMany([
  {"tipo": "Postoperatorio", "observaciones": "Verificar signos vitales cada 4 horas"},
  {"tipo": "Preventivo", "observaciones": "Monitorear signos de alergia"},
  {"tipo": "Curación", "observaciones": "Revisar herida cada 2 días"},
  {"tipo": "Acompañamiento", "observaciones": "Supervisión en recuperación"}
]);
```

## Colección: PERSONAL

```js
db.PERSONAL.insertMany([
  {"id": "per01", "nombre": "Camila Rodríguez", "rol": "Médico"},
  {"id": "per02", "nombre": "Esteban Herrera", "rol": "Enfermero"},
  {"id": "per03", "nombre": "Andrés Beltrán", "rol": "Médico"},
  {"id": "per04", "nombre": "Julia Mejía", "rol": "Enfermero"}
]);
```

## Colección: SERVICIO

```js
db.SERVICIO.insertMany([
  {"nombre": "Urgencias"},
  {"nombre": "Consulta externa"},
  {"nombre": "Hospitalización"},
  {"nombre": "Pediatría"}
]);
```

## Colección: CAMA

```js
db.CAMA.insertMany([
  {"id": "cam01", "estado": "Ocupada", "numero": 12},
  {"id": "cam02", "estado": "Disponible", "numero": 15},
  {"id": "cam03", "estado": "Mantenimiento", "numero": 18},
  {"id": "cam04", "estado": "Ocupada", "numero": 21}
]);
```

## Colección: HORA

```js
db.HORA.insertMany([
  {"hora_inicio": "08:00", "hora_fin": "08:30"},
  {"hora_inicio": "09:00", "hora_fin": "09:30"},
  {"hora_inicio": "10:00", "hora_fin": "10:30"},
  {"hora_inicio": "11:00", "hora_fin": "11:30"}
]);
```

