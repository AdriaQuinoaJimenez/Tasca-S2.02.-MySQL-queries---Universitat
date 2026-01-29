# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 0 correctas de 1 queries

## ❌ Query 1: Incorrecto
```diff
--- 
+++ 
@@ -1,13 +1,25 @@
 apellido1 | apellido2 | nombre
 Domínguez | Guerrero | Antonio
+Fahey | Considine | Antonio
 Gea | Ruiz | Sonia
 Gutiérrez | López | Juan
+Hamill | Kozey | Manolo
 Heller | Pagac | Pedro
 Herman | Pacocha | Daniel
 Hernández | Martínez | Irene
 Herzog | Tremblay | Ramón
+Kohler | Schoen | Alejandro
 Koss | Bayer | José
 Lakin | Yundt | Inma
+Lemke | Rutherford | Cristina
+Monahan | Murray | Micaela
+Ramirez | Gea | Zoe
+Ruecker | Upton | Guillermo
 Saez | Vega | Juan
 Sánchez | Pérez | Salvador
+Schmidt | Fisher | David
+Schowalter | Muller | Francesca
+Spencer | Lakin | Esther
+Stiedemann | Morissette | Alfredo
+Streich | Hirthe | Carmen
 Strosin | Turcotte | Ismael
```

⏱ Tiempo: 0.41 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
🚨 `JOIN` sin índice. Revisar claves foráneas e índices.

---
