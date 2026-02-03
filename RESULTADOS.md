# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 17 correctas de 19 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.44 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.31 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.37 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.33 ms
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

⏱ Tiempo: 0.55 ms
✅ Se usó índice(s) en la consulta: PRIMARY,nif, PRIMARY, PRIMARY,id_asignatura,id_curso_escolar

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.37 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,id_departamento, id_profesor,id_grado

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,id_curso_escolar

---

## ✅ Query 10: Correcto

⏱ Tiempo: 0.41 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 11: Correcto

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.32 ms
✅ Se usó índice(s) en la consulta: id_departamento

---

## ✅ Query 13: Correcto

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: PRIMARY, id_profesor

---

## ✅ Query 14: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: PRIMARY, id_profesor

---

## ✅ Query 15: Correcto

⏱ Tiempo: 0.37 ms
✅ Se usó índice(s) en la consulta: id_departamento, id_profesor, id_asignatura

---

## ✅ Query 16: Correcto

⏱ Tiempo: 0.31 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 17: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 18: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-departamento | total
+nombre | total
 Educación | 3.00
 Informática | 2.00
 Matemáticas | 2.00
```

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: PRIMARY, id_departamento

---

## ❌ Query 19: Error
- **Descripción**: 'NoneType' object is not iterable

