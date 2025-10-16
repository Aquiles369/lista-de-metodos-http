# Changelog

Todas las versiones siguen el formato [SemVer].

## [v1.0.0] - 2025-10-14
### 🆕 Añadido
- ⚙️ **Lista de métodos HTTP — Tu llavero completo:** colección integral de métodos HTTP desde los definidos por RFC hasta extensiones oficiales y métodos “de la vida real” usados por CDNs, proxies y herramientas.
- 📚 **Clasificación táctica en 3 categorías:**
  - 🧩 **Core (RFC 9110):** GET, HEAD, POST, PUT, DELETE, CONNECT, OPTIONS, TRACE.
  - 📡 **Extensiones estándar:** PATCH, PROPFIND, PROPPATCH, MKCOL, COPY, MOVE, LOCK, UNLOCK, SEARCH, REPORT, MKCALENDAR, CHECKOUT, MERGE, MKACTIVITY, LABEL, BASELINE-CONTROL, ACL.
  - 🧪 **No estándar (wild):** PURGE, BAN, VIEW, EXEC, RUN, PIPE, REFRESH, RETRIEVE, STORE, FETCH, SAVE, PUSH, PULL, CLONE, SNAPSHOT, PRINT, PATCHSET, POSTMAN, INDEX, INDEXSEARCH, BMOVE, BCOPY, MONITOR, STREAM, TUNNEL, CONNECT-UDP, CONNECT-TCP, CONNECT-SCTP, RESUME, ABORT, CANCEL, CONTINUE, FINISH, NEGOTIATE.
- 🧠 **Resumen táctico:** explicación de cada grupo, uso principal y potencial ofensivo.
- 🛠️ **Casos de uso ofensivos:**
  - Descubrimiento de endpoints ocultos.
  - Bypass de restricciones cuando GET o POST están filtrados.
  - Fuzzing avanzado con métodos alternativos.
  - Pruebas específicas según semántica del método.
- 📦 **Demo en YouTube:** explicación detallada de la lista y su uso práctico en entornos de bug bounty.

### ✨ Cambiado
- N/A — Primera versión.

### 🐞 Corregido
- N/A — Primera versión.

### 📌 Notas
- Este repositorio sirve como referencia táctica para auditorías, fuzzing y bug bounty.
- Conocer estos métodos permite descubrir rutas olvidadas, comportamientos inesperados y vectores de ataque ignorados por la mayoría.
- “Cada método HTTP es una llave… y esta lista es tu llavero completo.”
