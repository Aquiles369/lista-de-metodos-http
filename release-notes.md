# Release Notes — v1.0.0 (2025-10-14)

## 🏹 Resumen
**Lista de métodos HTTP** — Colección definitiva de métodos HTTP: desde los core definidos por los RFC hasta extensiones oficiales y métodos poco documentados usados por proxies, CDNs y herramientas reales.

📺 Demo completa disponible en el canal de YouTube.

---

## 🧠 Problema que resuelve
La información sobre métodos HTTP está dispersa en wikis, RFCs, artículos y notas aisladas.  
Esto dificulta el trabajo de un bug bounty hunter o pentester que necesita saber:

- Qué métodos existen realmente.
- Cuáles están activos en un servidor.
- Qué impacto puede tener cada uno.

Esta lista reúne **todo en un solo lugar**, eliminando la pérdida de tiempo y reduciendo el riesgo de omisiones críticas.

---

## ⚔️ Qué aporta
- 🔍 **Descubrimiento de superficie oculta:** detectar endpoints olvidados y funciones internas no documentadas.
- 🪄 **Bypass de restricciones:** usar métodos alternativos cuando GET o POST están filtrados.
- 🧪 **Fuzzing inteligente:** probar el backend con métodos inesperados.
- 🧠 **Análisis profundo:** entender la semántica ofensiva de cada método.
- 🎯 **Pentest preciso:** separar core, extensiones y no estándar para diseñar estrategias específicas.

---

## 📦 Contenido principal

### 🧩 Core (RFC 9110 – estándar base)
GET  
HEAD  
POST  
PUT  
DELETE  
CONNECT  
OPTIONS  
TRACE  

📌 **Uso:** interacción esencial cliente-servidor. Base de cualquier prueba web.

---

### 📡 Extensiones estándar (WebDAV, CalDAV, RFCs adicionales)
PATCH  
PROPFIND  
PROPPATCH  
MKCOL  
COPY  
MOVE  
LOCK  
UNLOCK  
SEARCH  
REPORT  
MKCALENDAR  
CHECKOUT  
MERGE  
MKACTIVITY  
LABEL  
BASELINE-CONTROL  
ACL  

📌 **Uso:** funcionalidades extendidas que permiten escribir, buscar, versionar, bloquear o gestionar recursos.

---

### 🧪 No estándar “de la vida real” (proxies, CDNs, herramientas)
PURGE  
BAN  
VIEW  
EXEC  
RUN  
PIPE  
REFRESH  
RETRIEVE  
STORE  
FETCH  
SAVE  
PUSH  
PULL  
CLONE  
SNAPSHOT  
PRINT  
PATCHSET  
POSTMAN  
INDEX  
INDEXSEARCH  
BMOVE  
BCOPY  
MONITOR  
STREAM  
TUNNEL  
CONNECT-UDP  
CONNECT-TCP  
CONNECT-SCTP  
RESUME  
ABORT  
CANCEL  
CONTINUE  
FINISH  
NEGOTIATE  

📌 **Uso:** comportamientos no documentados pero explotables. Alta probabilidad de bypass y vectores inesperados.

---

## 🧪 Uso recomendado
1. Incluir esta lista en tus fuzzers personalizados para ampliar superficie de ataque.  
2. Probar endpoints con métodos poco comunes en busca de respuestas diferentes.  
3. Detectar bypasses potenciales en WAF o configuraciones mal filtradas.  
4. Analizar diferencias de comportamiento entre métodos en APIs REST y GraphQL.

---

## 🛣️ Roadmap
- ✅ Publicación de la versión base con +60 métodos.  
- ⏭️ Próximamente: ejemplos prácticos por método y casos reales de bypass.

---

**“Domina el lenguaje del servidor: cada método HTTP es una llave… y esta lista es tu llavero completo.”**
