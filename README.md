# David · Finca Gaia

Humano digital 3D, experto en agroecología. Página de un solo archivo (`index.html`) con Three.js, boca sincronizada y conversación por voz con un agente de ElevenLabs.

## Publicar en GitHub Pages
1. Subí estos archivos a un repositorio nuevo (rama `main`).
2. Settings → Pages → Source: *Deploy from a branch* → `main` / `(root)`.
3. Abrí `https://TU_USUARIO.github.io/NOMBRE_DEL_REPO/`.

## Agente de voz
- Agente por defecto: `agent_5801m4xxqcvvem3tse0ph99dve0v`.
- Para usar otro sin tocar el código: `index.html?agente=TU_ID`.
- En ElevenLabs, pestaña Security: autenticación desactivada. Si activás la lista de dominios, agregá `TU_USUARIO.github.io`.

## Ajuste de sincronía
En `index.html`, buscá `LIP_OFFSET_MS`. Subilo si la boca va adelantada; bajalo si va atrasada.
