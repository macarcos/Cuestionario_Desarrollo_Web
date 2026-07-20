# Simulador · Desarrollo Web (UNEMI)

Simulador de práctica de opción múltiple. Todo está dentro de `index.html`
(preguntas, CSS y JavaScript incluidos), no necesita instalar nada.

## Contenido
- **Banco (Word):** 110 preguntas organizadas por las 9 unidades. Puedes
  practicar una unidad sola o todas juntas.
- **Banco (Imágenes):** 10 preguntas únicas del simulador (las de las capturas).

Las preguntas **y** las opciones (A/B/C/D) se barajan en cada intento y cada
vez que vuelves a entrar al quiz.

---

## Probar en tu computadora
Solo haz doble clic en `index.html`. Se abre en el navegador.

---

## Subir a Vercel (para compartir por link con tus compañeros)

### Opción 1 — Arrastrar y soltar (la más fácil, sin instalar nada)
1. Entra a https://vercel.com e inicia sesión (puedes usar tu cuenta de GitHub o Google).
2. En el panel, clic en **Add New… → Project**.
3. Busca la opción de importar/deploy manual y **arrastra esta carpeta completa**
   (o el archivo comprimido) a la zona de subida.
4. Vercel detecta que es un sitio estático automáticamente. Deja todo por defecto
   y pulsa **Deploy**.
5. En unos segundos te da un link tipo `https://simulador-desarrollo-web.vercel.app`
   que puedes pasar a tus compañeros.

### Opción 2 — Con la terminal (Vercel CLI)
```bash
npm install -g vercel     # instalar la CLI una sola vez
cd simulador-desarrollo-web
vercel                    # sigue las preguntas; acepta los valores por defecto
vercel --prod             # publica la versión final
```

### Opción 3 — Desde GitHub (deploy automático)
1. Sube esta carpeta a un repositorio en GitHub.
2. En Vercel: **Add New… → Project → Import** ese repositorio.
3. Deja la configuración por defecto y pulsa **Deploy**.
4. Cada vez que hagas cambios y los subas a GitHub, Vercel actualiza el sitio solo.

---

## Archivos
- `index.html` .... el simulador completo (esto es lo único imprescindible).
- `vercel.json` ... configuración para Vercel (opcional, ya viene lista).
- `README.md` ..... este archivo.
