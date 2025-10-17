<h1 align="center"><img height="40" src="https://github.com/Aquiles369/iconos/blob/main/img/lobo1.gif"><img height="40" src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExNWx4YTl1dW9scXlqZDk2cTdyY2VvcXQwMG40OGoxY25rZzV0MDZhcCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/peSyJWjNTRfzaWh49M/giphy.gif">"Lista de metodos http"<img height="40" src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExNWx4YTl1dW9scXlqZDk2cTdyY2VvcXQwMG40OGoxY25rZzV0MDZhcCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/peSyJWjNTRfzaWh49M/giphy.gif"><img height="40" src="https://github.com/Aquiles369/iconos/blob/main/img/lobo1.gif"></h1>	


<br>


<p align="center">
 <img  height="470rem" alt="GIF" src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExdHR5d2hscHo4dGN4MmFzbTZoNHN2ZG94eXY5M2U4YXRpMDhkM3ZyciZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/DFfy8D4fkxC8CNi4si/giphy.gif"/>
</p>


<picture> <img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">  </picture>

 ### <picture> <img src = "https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExNmp2MW0xYzg1MnF6bjV2ZDh4cDNzYmR4MGVmNzI1cmlid25taXF1ciZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/3wX77eHF4yTiexNSYW/giphy.gif" width = 75px>  </picture> Lista de metodos http

<br>

 **Colección completa de métodos HTTP: desde los core definidos por RFC hasta extensiones oficiales y métodos “de la calle” usados por CDNs, proxies y herramientas reales. Esta lista es tu mapa táctico para entender cómo se comunican cliente y servidor, descubrir rutas ocultas, y encontrar comportamientos peligrosos que otros pasan por alto,<a href="https://youtu.be/hI9D3In4X9U" target="_blank" rel="noopener">demo lista metodos http Youtube</a>.** 
<br><br> 

<p align="center">
 <img  height="420rem" alt="GIF" src="https://github.com/Aquiles369/iconos/blob/main/demo_lista_http.gif"/>
</p>

<br>
<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExcTdxZzg2Nmhsa2k5ZTJ3dXp6eWw4emcwcDhxY2pkM2NmaG83bzRjNCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/IzU6RZvqxxRuDExMG1/giphy.gif" width = 75px>  </picture> Problema que resuelve<br><br>
**•La información sobre métodos HTTP suele estar dispersa en wikis, RFCs y notas sueltas. Esto complica el trabajo en bug bounty y auditorías, donde necesitás saber qué métodos existen, cuáles están activos y qué impacto tienen. <br><br>
• Esta lista reúne todo en un solo lugar, ahorrando tiempo y evitando omisiones críticas.** 

<br>

### <picture> <img src = "https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExdXR0OGRrYnM4ZHk5a2M2dnFjODgxcnZ3b2lwM2Zmd25pamFsd29xaiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/02iB5X78Zrr3Xg7K4n/giphy.gif" width = 75px>  </picture> Qué aporta y cómo beneficia <br><br>
**• Descubrimiento de superficie oculta: detectar endpoints no documentados y funciones olvidadas.<br><br>
• Bypass de restricciones: aprovechar métodos alternativos cuando GET o POST están filtrados.<br><br>
• Fuzzing inteligente: probar el backend con métodos que el desarrollador nunca pensó que alguien usaría.<br><br>
• Análisis profundo: entender la semántica de cada método para identificar vectores de ataque reales.<br><br>
• Pentest preciso: separar core, extensiones y no estándar para planificar pruebas específicas.** 

<br>


<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExb3JjOTcydzVpZXZta2owcHc2cjFkZmQ3eHBxeG83d3c1cHU4NXk1MiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/LHTYbmSwbh9Oo/giphy.gif" width = 80px>  </picture> Resumen rápido
<br><br>

- Estos métodos HTTP son esenciales para auditorías, fuzzing y bug bounty. Conocerlos permite detectar comportamientos inesperados, endpoints olvidados o funciones internas peligrosas en APIs y servidores.<br><br>

## Lista de metodos http: <br>

```yaml
GET
HEAD
POST
PUT
DELETE
CONNECT
OPTIONS
TRACE
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

```
<br>

## Explicacion de cada caracter y categoría de la lista.<br>

```yaml
Core (RFC 9110 – estándar base)
GET
HEAD
POST
PUT
DELETE
CONNECT
OPTIONS
TRACE

Extensiones estándar (RFC adicionales, WebDAV, CalDAV, etc.)

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

No estándar “de la vida real” (usados por CDNs, proxies, herramientas)

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

```

<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
<br>

### <picture> <img src = "https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExc3YwbG9zbmU1amprdTJsbmxzYnpobzd5eGtnazB6b2FmdnllaTRhZyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/h8UlsEpqiCISTKUzvz/giphy.gif" width = 80px>  </picture> “Domina el lenguaje del servidor: cada método HTTP es una llave… y esta lista es tu llavero completo.”


<picture> <img src="https://user-images.githubusercontent.com/74038190/212284115-f47cd8ff-2ffb-4b04-b5bf-4d1c14c0247f.gif" width ="1050" > </picture>
