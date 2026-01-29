# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 9 correctas de 11 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.46 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.31 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.44 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_departamento, PRIMARY

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.59 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_asignatura,id_curso_escolar, PRIMARY,nif, PRIMARY

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.40 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_departamento, id_profesor,id_grado, PRIMARY

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.37 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_curso_escolar, PRIMARY

---

## ❌ Query 10: Incorrecto
```diff
--- 
+++ 
@@ -1,13 +1,25 @@
 departamento | apellido1 | apellido2 | nombre
+Economía y Empresa | Fahey | Considine | Antonio
+Informática | Hamill | Kozey | Manolo
+Matemáticas | Kohler | Schoen | Alejandro
+Economía y Empresa | Lemke | Rutherford | Cristina
 Agronomía | Monahan | Murray | Micaela
-Economía y Empresa | Fahey | Considine | Antonio
-Economía y Empresa | Lemke | Rutherford | Cristina
+Informática | Ramirez | Gea | Zoe
 Educación | Ruecker | Upton | Guillermo
-Educación | Spencer | Lakin | Esther
-Educación | Streich | Hirthe | Carmen
-Informática | Hamill | Kozey | Manolo
-Informática | Ramirez | Gea | Zoe
-Matemáticas | Kohler | Schoen | Alejandro
 Matemáticas | Schmidt | Fisher | David
 Química y Física | Schowalter | Muller | Francesca
+Educación | Spencer | Lakin | Esther
 Química y Física | Stiedemann | Morissette | Alfredo
+Educación | Streich | Hirthe | Carmen
+NULL | Domínguez | Guerrero | Antonio
+NULL | Gea | Ruiz | Sonia
+NULL | Gutiérrez | López | Juan
+NULL | Heller | Pagac | Pedro
+NULL | Herman | Pacocha | Daniel
+NULL | Hernández | Martínez | Irene
+NULL | Herzog | Tremblay | Ramón
+NULL | Koss | Bayer | José
+NULL | Lakin | Yundt | Inma
+NULL | Saez | Vega | Juan
+NULL | Sánchez | Pérez | Salvador
+NULL | Strosin | Turcotte | Ismael
```

⏱ Tiempo: 0.42 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ❌ Query 11: Error
- **Descripción**: 'NoneType' object is not iterable

