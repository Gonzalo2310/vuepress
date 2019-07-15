---
home: true
heroImage: /hero.png
actionText: Get Started →
actionLink: es/guide/
footer: MIT Licensed | Copyright © 2018-present Evan You
---

<div style="text-align: center">
  <Bit/>
</div>

<div class="features">
  <div class="feature">
    <h2>La simplicidad es lo primero</h2>
    <p>Una configuracion minima centrada en un projecto Markdown para ayudarle a centrarse en la escritura.</p>
  </div>
  <div class="feature">
    <h2>El poder de Vue</h2>
    <p>Disfrute de la experiencia de desarrollo de Vue + webpack, utilice los componentes de Vue en el Markdown y desarrolle temas personalizados con Vue.</p>
  </div>
  <div class="feature">
    <h2>Rendimiento</h2>
    <p>VuePress genera HTML estático pre-renderizado para cada página, y se ejecuta como un SPA una vez que se carga una página.</p>
  </div>
</div>

### Tan fácil como 1, 2, 3

``` bash
# instalacion
yarn global add vuepress@next 
# O npm install -g vuepress@next

# crea un archivo markdown
echo '# Hello VuePress' > README.md

# comienza a escribir
vuepress dev

# construir los archivos estáticos
vuepress build
```

::: warning COMPATIBILITY NOTE
VuePress requiere Node.js >= 8.6.
:::