# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 5 correctas de 8 queries

## ❌ Query 1: Incorrecto
```diff
--- 
+++ 
@@ -1,13 +1,13 @@
-apellido1 | apellido2 | nombre
-Domínguez | Guerrero | Antonio
-Gea | Ruiz | Sonia
-Gutiérrez | López | Juan
-Heller | Pagac | Pedro
-Herman | Pacocha | Daniel
-Hernández | Martínez | Irene
-Herzog | Tremblay | Ramón
-Koss | Bayer | José
-Lakin | Yundt | Inma
-Saez | Vega | Juan
-Sánchez | Pérez | Salvador
-Strosin | Turcotte | Ismael
+nombre | apellido1 | apellido2
+Antonio | Domínguez | Guerrero
+Sonia | Gea | Ruiz
+Juan | Gutiérrez | López
+Pedro | Heller | Pagac
+Daniel | Herman | Pacocha
+Irene | Hernández | Martínez
+Ramón | Herzog | Tremblay
+José | Koss | Bayer
+Inma | Lakin | Yundt
+Juan | Saez | Vega
+Salvador | Sánchez | Pérez
+Ismael | Strosin | Turcotte
```

⏱ Tiempo: 0.44 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.31 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.29 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ❌ Query 6: Incorrecto
```diff
--- 
+++ 
@@ -1,13 +1,4 @@
-apellido1 | apellido2 | nombre | departamento
-Fahey | Considine | Antonio | Economía y Empresa
-Hamill | Kozey | Manolo | Informática
-Kohler | Schoen | Alejandro | Matemáticas
-Lemke | Rutherford | Cristina | Economía y Empresa
-Monahan | Murray | Micaela | Agronomía
-Ramirez | Gea | Zoe | Informática
-Ruecker | Upton | Guillermo | Educación
-Schmidt | Fisher | David | Matemáticas
-Schowalter | Muller | Francesca | Química y Física
-Spencer | Lakin | Esther | Educación
-Stiedemann | Morissette | Alfredo | Química y Física
-Streich | Hirthe | Carmen | Educación
+nombre | apellido1 | apellido2 | departamento
+Cristina | Lemke | Rutherford | Derecho
+Zoe | Ramirez | Gea | Economía y Empresa
+David | Schmidt | Fisher | Agronomía
```

⏱ Tiempo: 0.42 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.53 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_asignatura,id_curso_escolar, PRIMARY, PRIMARY,nif

---

## ❌ Query 8: Error
- **Descripción**: 'NoneType' object is not iterable

