# AGENTS.md

Guia para agentes que trabajen en este repositorio.

## Estructura

- `express/`: aplicacion Node.js/Express (CommonJS). Punto de entrada `express/index.js`.
- `tecbot/`: subproyecto del bot.

## Comandos

Trabajar dentro de cada subproyecto. Para `express/`:

- Instalar dependencias: `npm install`
- Desarrollo: `npm run dev` (nodemon)
- Produccion: `npm start`
- No hay script de tests ni de lint configurado.

## Convenciones

- No agregar comentarios al codigo salvo que se soliciten.
- No versionar secretos: `firebase_key.json` y archivos `.env` estan ignorados.
- Respetar el `.gitignore` de cada subproyecto.
- No crear commits sin pedido explicito.

## Verificacion

- `express/`: `npm start` debe levantar sin errores.
- No ejecutar `npm install` si `node_modules/` ya existe salvo que cambien dependencias.
