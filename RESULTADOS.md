# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 8 correctas de 10 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.41 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.34 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.34 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.31 ms
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
 apellido1 | apellido2 | nombre | departamento
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
+Lemke | Rutherford | Cristina | Derecho
+Ramirez | Gea | Zoe | Economía y Empresa
+Schmidt | Fisher | David | Agronomía
```

⏱ Tiempo: 0.37 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.50 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_asignatura,id_curso_escolar, PRIMARY,nif, PRIMARY

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.38 ms
✅ Se usó índice(s) en la consulta: id_profesor,id_grado, PRIMARY,id_departamento, PRIMARY

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_curso_escolar, PRIMARY

---

## ❌ Query 10: Error
- **Descripción**: 'NoneType' object is not iterable

