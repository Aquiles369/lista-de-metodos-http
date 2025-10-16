# Política de seguridad

## 🧠 Resumen
**Lista de métodos HTTP** es un recurso de referencia creado con fines educativos y de investigación.  
Su objetivo es servir como guía táctica para pentesters, bug bounty hunters y auditores, ayudándolos a comprender y probar comportamientos relacionados con métodos HTTP en entornos legales y controlados.

---

## 🔐 Principios de seguridad

- 🧪 **Uso ético y autorizado:** esta lista debe emplearse exclusivamente en entornos donde tengas permiso explícito (laboratorios, programas de bug bounty, auditorías).
- 📚 **Contenido seguro:** el repositorio no incluye exploits activos ni scripts automatizados.
- 🛡️ **Sin backend:** es 100% estático, no ejecuta código ni realiza peticiones externas.
- 📡 **Privacidad:** no se almacena información sensible ni se recopilan datos del usuario.

---

## ✅ Buenas prácticas recomendadas

- Validar el uso de cada método únicamente en sistemas autorizados.  
- Combinar esta lista con herramientas de fuzzing en entornos controlados antes de usarla en producción.  
- Documentar resultados y reportar comportamientos inesperados de forma responsable.  
- Revisar las políticas de seguridad y alcance del programa antes de realizar pruebas.

---

## 🐛 Reporte de vulnerabilidades

Si detectás errores, inconsistencias o comportamientos inesperados:

1. No publiques detalles sensibles en issues públicos.  
2. Contactá con el mantenedor mediante GitHub o Discord.  
3. Incluí detalles del método afectado, entorno y comportamiento observado.

---

## 🛡️ Alcance de seguridad

| Área                              | Estado                       |
|----------------------------------|-----------------------------|
| Backend / API                    | ❌ No aplica                |
| Ejecución de código             | ❌ No incluida             |
| Archivos ejecutables            | ❌ No incluidos            |
| Recursos externos               | ✅ Referencias seguras     |
| Datos sensibles                 | ❌ No deben almacenarse    |

---

## ⚠️ Descargo
Este proyecto tiene fines educativos y de investigación.  
El uso indebido de la información puede ser ilegal.  
El autor no se hace responsable de acciones no autorizadas derivadas del uso de esta información.

---

**“Domina el lenguaje del servidor: cada método HTTP es una llave… y esta lista es tu llavero completo.”**
