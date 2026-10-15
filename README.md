# ObsidianLive · GitHub Pages

Frontend público preparado para `https://rpscode.github.io/ObsidianLive/`.

## Publicar

Sube **el contenido de esta carpeta** a la raíz de la rama `main` del repositorio `rpscode/ObsidianLive`.

## Backend actual

`portal.html` usa temporalmente:

`https://xbox-voice-clusters-remedy.trycloudflare.com`

Mientras se use Quick Tunnel, cambia `OBSIDIAN_API_BASE` en `portal.html` cuando cambie la URL. Cuando exista un hostname estable, solo habrá que cambiarlo una vez.

## Seguridad

Este paquete no contiene `secret.key`, la API key del Bridge, `host.py`, datos persistidos ni el resource pack completo.

## Requisito del Host

El backend debe permitir CORS desde `https://rpscode.github.io`. Usa el Host 0.2.2 CORS incluido como paquete separado.
