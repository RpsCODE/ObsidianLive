OBSIDIANLIVE WEB V0.1.1-alpha

1. Suba TODO el contenido de esta carpeta a la raíz pública de su hosting.
2. El archivo inicial debe ser index.html.
3. No cambie la estructura de assets/, css/ ni data/.
4. Esta versión usa assets reales de los resource packs aportados, pero los datos TPS/jugadores siguen siendo demostrativos.
5. BlueMap y la API real se conectarán en las siguientes fases.

Prueba local recomendada:
python -m http.server 8080
Luego abra http://localhost:8080

Nota: abrir portal.html directamente como file:// puede impedir fetch(data/assets.json) en algunos navegadores; usando hosting HTTP/HTTPS funciona correctamente.
