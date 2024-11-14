Instalar TailwindCSS como dependencia de desarrollo

```sh
npm i -D tailwindcss
```

Crear el archivo de configuracion de TailwindCSS

```sh
npx tailwindcss init
```

Añadir las directivas Tailwind `/src/input.css`

```css
@tailwind base;
@tailwind components;
@tailwind utilities;
```

Generar el archivo de salida

```sh
npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
```