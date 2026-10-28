# Flexiones

Contador diari de flexions (objectiu: 50 al dia) amb calendari i historial. PWA sense dependències: HTML, CSS i JavaScript normals. Les dades es guarden només al teu mòbil (localStorage).

## Fitxers

```
flexiones/
├── index.html
├── manifest.webmanifest
├── sw.js
├── README.md
└── icons/
    ├── icon-192.png
    └── icon-512.png
```

## Publicar a GitHub Pages (des del mòbil)

1. Descomprimeix el ZIP: a la Samsung, obre **Mis archivos**, mantén premut el ZIP i toca **Extraer**.
2. A Chrome, entra a github.com i inicia sessió. Toca **+ › New repository**.
3. Nom del repositori: `flexiones` (en minúscules). Marca **Public**. Toca **Create repository**.
4. Dins del repositori toca **Add file › Upload files** i tria `index.html`, `manifest.webmanifest`, `sw.js` i `README.md`. Toca **Commit changes**.
5. Per a la carpeta d'icones: **Add file › Create new file**, escriu al nom `icons/.gitkeep` (la barra crea la carpeta) i toca **Commit changes**.
6. Entra a la carpeta `icons`, toca **Add file › Upload files**, tria `icon-192.png` i `icon-512.png` i fes **Commit changes**.
7. Ves a **Settings › Pages**. A *Build and deployment*, **Source: Deploy from a branch**, branca **main**, carpeta **/ (root)**, i toca **Save**.
8. Espera 1-2 minuts. L'adreça serà `https://EL_TEU_USUARI.github.io/flexiones/`.

Si Chrome et dificulta la pujada, activa **Sitio de escritorio** al menú ⋮ de Chrome.

## Instal·lar al Samsung

1. Obre l'adreça a **Chrome** i deixa que carregui del tot (així queda guardada per a ús sense connexió).
2. Menú ⋮ › **Instalar aplicación** (o **Añadir a pantalla de inicio**) › **Instalar**.
3. Obre Flexiones des de la icona de la pantalla d'inici.

## Actualitzacions

Si canvies un fitxer, edita `CACHE = 'flexiones-v1'` a `sw.js` (per ex. `v2`). L'app mostra la versió nova la segona vegada que l'obres.
