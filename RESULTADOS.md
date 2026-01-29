# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 7 correctas de 9 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.40 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.36 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.31 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.38 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,id_departamento

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.57 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,id_asignatura,id_curso_escolar, PRIMARY,nif

---

## ❌ Query 8: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,22 @@
-nombre
-Informática
+nombre | nombre | id_profesor | nombre
+Informática | Álgegra lineal y matemática discreta | 3.00 | Grado en Ingeniería Informática (Plan 2015)
+Informática | Cálculo | 14.00 | Grado en Ingeniería Informática (Plan 2015)
+Informática | Física para informática | 3.00 | Grado en Ingeniería Informática (Plan 2015)
+Informática | Introducción a la programación | 14.00 | Grado en Ingeniería Informática (Plan 2015)
+Informática | Organización y gestión de empresas | 3.00 | Grado en Ingeniería Informática (Plan 2015)
+Informática | Estadística | 14.00 | Grado en Ingeniería Informática (Plan 2015)
+Informática | Estructura y tecnología de computadores | 3.00 | Grado en Ingeniería Informática (Plan 2015)
+Informática | Fundamentos de electrónica | 14.00 | Grado en Ingeniería Informática (Plan 2015)
+Informática | Lógica y algorítmica | 3.00 | Grado en Ingeniería Informática (Plan 2015)
+Informática | Metodología de la programación | 14.00 | Grado en Ingeniería Informática (Plan 2015)
+Informática | Arquitectura de Computadores | 3.00 | Grado en Ingeniería Informática (Plan 2015)
+Informática | Estructura de Datos y Algoritmos I | 3.00 | Grado en Ingeniería Informática (Plan 2015)
+Informática | Ingeniería del Software | 14.00 | Grado en Ingeniería Informática (Plan 2015)
+Informática | Sistemas Inteligentes | 3.00 | Grado en Ingeniería Informática (Plan 2015)
+Informática | Sistemas Operativos | 14.00 | Grado en Ingeniería Informática (Plan 2015)
+Informática | Bases de Datos | 14.00 | Grado en Ingeniería Informática (Plan 2015)
+Informática | Estructura de Datos y Algoritmos II | 14.00 | Grado en Ingeniería Informática (Plan 2015)
+Informática | Fundamentos de Redes de Computadores | 3.00 | Grado en Ingeniería Informática (Plan 2015)
+Informática | Planificación y Gestión de Proyectos Informáticos | 3.00 | Grado en Ingeniería Informática (Plan 2015)
+Informática | Programación de Servicios Software | 14.00 | Grado en Ingeniería Informática (Plan 2015)
+Informática | Desarrollo de interfaces de usuario | 14.00 | Grado en Ingeniería Informática (Plan 2015)
```

⏱ Tiempo: 0.40 ms
✅ Se usó índice(s) en la consulta: id_profesor,id_grado, PRIMARY,id_departamento, PRIMARY

---

## ❌ Query 9: Error
- **Descripción**: 'NoneType' object is not iterable

