# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 18 correctas de 22 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.37 ms
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

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.34 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_departamento, PRIMARY

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.54 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_asignatura,id_curso_escolar, PRIMARY,nif, PRIMARY

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: id_profesor,id_grado, PRIMARY,id_departamento, PRIMARY

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_curso_escolar, PRIMARY

---

## ✅ Query 10: Correcto

⏱ Tiempo: 0.37 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 11: Correcto

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.31 ms
✅ Se usó índice(s) en la consulta: id_departamento

---

## ✅ Query 13: Correcto

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: id_profesor, PRIMARY

---

## ✅ Query 14: Correcto

⏱ Tiempo: 0.30 ms
✅ Se usó índice(s) en la consulta: id_profesor, PRIMARY

---

## ✅ Query 15: Correcto

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: id_departamento, id_profesor, id_asignatura

---

## ✅ Query 16: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 17: Correcto

⏱ Tiempo: 0.28 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 18: Correcto

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: id_departamento, PRIMARY

---

## ❌ Query 19: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'SELECT grado.nombre AS grau, COUNT(asignatura.id) AS total FROM grado
LEFT JOIN ' at line 6


## ❌ Query 20: Error
- **Descripción**: 1064 (42000): You have an error in your SQL syntax; check the manual that corresponds to your MySQL server version for the right syntax to use near 'GROUP BY departamento.nombre
-- 21. Retorna un llistat amb el nom de tots els gr' at line 1


## ❌ Query 21: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-grau | total
-Grado en Ingeniería Informática (Plan 2015) | 51.00
+id | nif | nombre | apellido1 | apellido2 | ciudad | direccion | telefono | fecha_nacimiento | sexo | tipo
+1.00 | 26902806M | Salvador | Sánchez | Pérez | Almería | C/ Real del barrio alto | 950254837 | 1991-03-28 | H | alumno
```

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ❌ Query 22: Error
- **Descripción**: 'NoneType' object is not iterable

