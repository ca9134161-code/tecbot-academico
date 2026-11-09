# proyectos

Monorepo con los servicios y utilidades del proyecto.

## Estructura

- `express/`: servidor Node.js/Express (Firebase Admin, EJS, Bootstrap).
- `tecbot/`: espacio para el bot (Python/Node).

## Requisitos

- Node.js 18+
- Python 3.10+ (si se usa `tecbot`)

## Uso rapido

```bash
cd express
npm install
npm run dev
```

El servidor arranca con `npm start` o `npm run dev` (nodemon).

## Notas

- Las credenciales de Firebase no se versionan (`firebase_key.json` esta ignorado).
- Cada subproyecto mantiene su propio `.gitignore`.
