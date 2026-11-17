# Jami Training 🐾

PWA de entrenamiento canino positivo, pensada para sesiones breves de hasta diez minutos con Jami.

## Funciones
- Programa progresivo de cuatro semanas, sin avance automático obligatorio.
- Instrucciones detalladas y señales para bajar la dificultad.
- Temporizador de 10 minutos con pausa y reinicio.
- Registro de resultados y notas, historial y estadísticas.
- Datos almacenados localmente en el navegador; exportación JSON.
- Instalación en iPhone mediante Safari > Compartir > Agregar a pantalla de inicio.
- Caché offline tras la primera carga.

## Desarrollo
```bash
npm install
npm run dev
npm run build
```

## Vercel
Importá el repositorio como proyecto Vite. Build command: `npm run build`; output directory: `dist`. No necesita variables de entorno.

## Importante
No es un diagnóstico de conducta. Evitá castigos, tirones y saludos forzados. Si Jami presenta miedo intenso, rigidez persistente o agresividad, consultá a un profesional de comportamiento canino que trabaje con refuerzo positivo.

Los datos se guardan en el dispositivo. Si borrás los datos del navegador, podés perder el historial; exportá copias periódicas. Los recordatorios push no están implementados en esta versión.
