# Perfil de David Alvarez

Página web personal que presenta el perfil de David Alvarez como coder en formación en desarrollo de software. Incluye sus habilidades, ruta de aprendizaje, horario de estudio y enlaces de contacto.

## Tecnologías

- HTML5
- Tailwind CSS 4, compilado localmente y aplicado mediante clases de utilidad.

## Diseño responsive

El diseño se adapta a pantallas móviles, medianas y grandes usando los prefijos responsive de Tailwind (`sm:`, `md:` y `lg:`). En pantallas medianas, las secciones de habilidades y aprendizaje se muestran en dos columnas; la tabla del horario puede desplazarse horizontalmente en pantallas estrechas.

## Cómo abrir

Abre `index.html` en un navegador. La hoja compilada está incluida, así que no se requiere conexión a internet ni proceso de compilación para ver la página.

Para regenerar los estilos después de cambiar clases de Tailwind, instala las dependencias y compila:

```bash
npm install
npm run build:css
```

## Estructura

```text
mi-perfil/
├── index.html
├── css/
│   ├── input.css
│   └── styles.css
├── img/
│   └── foto_perfil.png
├── package.json
└── README.md
```
