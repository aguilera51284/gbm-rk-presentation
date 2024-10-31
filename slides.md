---
# You can also start simply with 'default'
theme: default
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://gbm.com/wp-content/uploads/2022/09/hero-scaled.jpeg
# some information about your slides (markdown enabled)
title: Desafío de implementación de Vite en RecordKeeping Portal
# apply unocss classes to the current slide
class: text-center
# https://sli.dev/features/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations.html#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/features/mdc
mdc: true
# take snapshot for each slide in the overview
overviewSnapshots: true
---

# Implementacion de Vite en RecordKeeping Portal

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Comenzar <carbon:arrow-right class="inline"/>
  </span>
</div>

---
transition: fade-out
class: bg-[#d9d9d9] font-bold text-gray-900
---

# Prologo

<div v-click> La aventura comienza </div>
<div v-click> En búsqueda del Santo Grial </div>
<div v-click> Formación contra Dragón </div>
<div v-click> El mago Gandalf </div>
<div v-click> Enfrentándose al Dragón </div>
<div v-click> Más allá del viaje </div>
<div v-click> Preguntas </div>


<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-blue-500 bg-opacity-10">
    Siguiente <carbon:arrow-right class="inline"/>
  </span>
</div>


---
class: bg-[#d9d9d9] font-bold text-gray-900
layout: image-right
image: https://gbm.com/academy/wp-content/uploads/sites/5/2022/11/gbm-app.png
---
# La aventura comienza

<div>
    <span class="text-gray-900 font-medium text-xs">Todo parte de una necesidad de negocio. cuando se nos llama a realizar un feature llamado Prestamos.</span>
</div>

<div class="pt-2">
    <span class="text-gray-900 block">Que es prestamos en RecordKeeping</span>
    <span class="text-gray-900 font-medium text-sm block">
        El servicio de Préstamos de Record Keeping ofrece a los clientes un sistema que les permite gestionar y ofrecer préstamos a sus participantes.
    </span>
    <ul>
        <li class="text-gray-900 font-medium text-sm block">
            <span class="text-gray-900 block">
                <span class="font-bold">Flex</span> En los préstamos Flex, el cliente genera el plan de pagos y lo comparte con el asesor de GBM, quien lo ingresa al sistema mediante Shell.
            </span>
        </li>
        <li class="text-gray-900 font-medium text-sm block">
        <span class="text-gray-900 block">
            <span class="font-bold">PISI</span> Para el préstamo PISI, un asesor de GBM debe configurarlo en el sistema usando Shell. Esta configuración, previamente acordada con el cliente, puede incluir una descripción del préstamo y reglas basadas en porcentajes del saldo disponible o en fechas específicas en las que el proceso de solicitud estará activo.
        </span>
        </li>
    </ul>
</div>


---
class: bg-[#d9d9d9] font-bold text-gray-900
layout: image-right
image: https://gbm.com/academy/wp-content/uploads/sites/5/2022/11/gbm-app.png
---

### La Aventura del Descubrimiento de Préstamos

<div class="my-4">
<span class="text-gray-900 font-medium text-xs">Durante el trayecto del discovery del nuevo feature, se aborda la parte visual, y es en ese momento donde los sabios del consejo toman una decisión crucial.</span>
</div>

### Homogeneizar la identidad de GBM.

<div class="my-4">
<span class="text-gray-900 font-medium text-xs">
Impulsados por el éxito de la app Evolution en GBM, se planea unificar todos los productos bajo el Design System desarrollado por el equipo de diseño, incorporando Record Keeping en esta iniciativa. Además, el nuevo feature de préstamos dará inicio a la renovación del look and feel de Record Keeping.</span>
</div>

---
class: bg-[#d9d9d9] text-gray-900 font-bold
layout: image-left
image: https://agence-polux.fr/wp-content/uploads/2023/05/design-system-min.png
---

# En búsqueda del Santo Grial

<div>
    Desing System: 
    <span class="text-sm font-medium text-gray-800">
        Un Design System para frontend es un conjunto de componentes y guías de estilo que aseguran coherencia y eficiencia en el desarrollo de interfaces.
    </span>
</div>

<div v-click> ¿Entonces GBM cuenta con un Design System? </div>
<div v-click>
    <span class="text-6xl text-[#007aff] font-bold">
        Si
    </span>
    <iframe src="https://giphy.com/embed/5GoVLqeAOo6PK" width="100%" height="auto"  frameBorder="0" class="giphy-embed bg-[#d9d9d9]" allowFullScreen></iframe>
</div>



---
class: bg-[#d9d9d9] text-gray-900 font-bold
---
<div class="my-4">
    <span class="font-bold text-6xl text-center">
        StarmanNext
    </span>
</div>

<div class="my-4">
    <span class="font-normal text-lg text-center ">
        StarmanNext es una iniciativa de GBM para mejorar la experiencia de usuario de GBM. y para lograrlo, se ha desarrollado un Design System que se integra con GBM y con otros productos de la empresa.
    </span>
    <span class="text-sm font-bold text-gray-800">
        Características:
    </span>
    <ul class="list-disc text-sm text-[#007aff] block">
        <li class="font-medium text-sm block text-[#007aff]">
           * Documentacion en figma
        </li>
        <li class="font-medium text-sm block text-[#007aff]">
            * Componentes de react
        </li>
        <li class="font-medium text-sm block text-[#007aff]">
            * Basado en tokens
        </li>
    </ul>
    <!-- imagen de startman next  -->
</div>


---
class: bg-[#d9d9d9] text-gray-900 font-bold
layout: image-right
image: https://images8.alphacoders.com/133/1339620.png
---

# Formación contra Dragón

<div>
    <span class="text-sm font-medium text-gray-800">
        ¿Qué armas tenemos?
    </span>
    <ul>
        <li class="font-medium text-sm block text-[#007aff]">
            * Craco v6
        </li>
        <li class="font-medium text-sm block text-[#007aff]">
            * Node v14
        </li>
        <li class="font-medium text-sm block text-[#007aff]">
            * Postcss v7  
        </li>
    </ul>
</div>


<div v-click> 
    <span class="font-semibold">
     Que es CRACO?
     </span>
</div>
<div v-click> 
    <span class="font-normal text-sm leading-relaxed">
      Es una herramienta que te permite personalizar diversas configuraciones en aplicaciones creadas con Create React App sin necesidad de "eject".
     </span>
</div>

<div v-click> 
    <span class="font-semibold">
     y Postcss?
     </span>
</div>
<div v-click> 
    <span class="font-normal text-sm leading-relaxed">
     Añade automáticamente prefijos a las reglas CSS según la popularidad de los navegadores y el soporte de propiedades. Autoprefixer hace esto por ti utilizando datos de "Can I Use".
     </span>
</div>

<div v-click> 
   Y por ultimo...
    <span class="font-normal text-sm leading-relaxed">
     StarmanNext
     </span>
</div>


---
class: bg-[#d9d9d9] text-gray-900 font-bold
---

### El dilema del guerro.

<div class="my-4">
    <span class="font-normal text-lg text-center ">
        Habia un detalle que se paso por alto y es que CRACO en su versión 6 no soporta postcss v7 ni archivos `.mjs` por lo que no podía utilizar el nuevo design system de StarmanNext.
    </span>
    <div class="text-center w-full flex justify-center my-4">
    <iframe src="https://giphy.com/embed/3orieZz9evyENLUpDq" width="200px" height="auto" class="bg-[#d9d9d9]" frameBorder="0"  ></iframe>
    </div>
</div>

<div class="bg-[#FDEDE2] p-4 my-4 rounded-lg">
    <span class="text-xs font-normal text-gray-900">
        Los archivos .mjs son archivos de módulo en JavaScript que utilizan la sintaxis de módulos ECMAScript (ESM). Esta extensión se introdujo para diferenciar los módulos ESM de los archivos JavaScript tradicionales, que suelen tener la extensión .js.
    </span>
</div>



---
class: bg-[#d9d9d9] text-gray-900 font-bold
layout: image-left
image: https://vite.dev/og-image.jpg
---

# El mago Gandalf (vite)

<div class="my-4">
    <span class="font-normal text-xs leading-none  ">
Vite es una herramienta para desarrollar aplicaciones web que hace que el proceso sea más rápido y eficiente. Utiliza un servidor de desarrollo que carga los cambios al instante, lo que significa que puedes ver los resultados en tu navegador inmediatamente mientras trabajas.  </span>
</div>

 <span class="font-bold block">Caracteristicas</span> 

<div v-click> 
    <span class="font-semibold">
        Recarga Instantáne
    </span>
</div>

<div v-click> 
    <span class="font-semibold">
        Construcción Rápida
    </span>
</div>

<div v-click> 
    <span class="text-bold  text-[#007aff]">
        Soporte de Módulos ES
    </span>
</div>

<div v-click> 
    <span class="font-semibold">
        Configuración Sencilla
    </span>
</div>

<div v-click> 
    <span class="font-semibold">
        Soporte para Frameworks
    </span>
</div>

<div v-click> 
    <span class="font-semibold">
        Optimización para Producción
    </span>
</div>

<div v-click> 
    <span class="font-semibold">
        Plugins Extensibles
    </span>
</div>

<div v-click> 
    <span class="font-semibold">
        Compilación de Recursos Estáticos
    </span>
</div>

---
class: bg-[#d9d9d9] text-gray-900 font-bold
layout: image-right
image: https://e0.pxfuel.com/wallpapers/358/849/desktop-wallpaper-dark-souls-iii-dragon-raining-warrior-big-sword-for-imac-27-inch-2560-x-1440-dark-souls.jpg
---

# Enfrentándose al Dragón


<div class="my-4">
    <span class="font-normal text-xs leading-none  ">
Lo primero que se hizo fue evaluar el impacto tangible de migrar a vite con los recursos que teniamos en esos momentos.</span>
</div>

<div v-click> 
    <span class="font-semibold">
     Se tomo la descicion de migrar primero el portal y dejar al administrador de rk atras.
     </span>
</div>


<div v-click class="mt-4"> 
    <span class="font-semibold">
        Posteriormente se hizo eligio a la persona  para realizar la migracion.
    </span>
</div>



<span class="font-normal text-[#d1cbcb] text-sm">
    Ivan Pineda murio en el combate con el dragon u.u .
</span>


---
class: bg-[#d9d9d9] text-gray-900 text-[10px]
---

# El corazón de Gandalf

<div class="my-4">
    <span class="font-normal text-lg leading-none">
        Lo primero que se noto fue lo facil que era el archivo de configuración de vite, lo que nos permitió comenzar a trabajar con vite.
    </span>
</div>

````md magic-move {lines: true}
```ts {*|2|*}
// Craco
module.exports = {
  webpack: (config) => {
    config.module.rules.push({
      test: /\.mjs$/,
      use: {
        loader: 'babel-loader',
        options: {
          presets: ['@babel/preset-env']
        }
      }
    });
    return config;
  }
}
```

```ts {*|1-2|3-4|3-4,8|5-6|*}
// Craco with babel-minify-webpack-plugin
const { override, addWebpackPlugin } = require('customize-cra');
const BabelMinifyWebpackPlugin = require('babel-minify-webpack-plugin');

module.exports = override(
  addWebpackPlugin(new BabelMinifyWebpackPlugin()),
  (config) => {
    config.module.rules.push({
      test: /\.mjs$/,
      use: {
        loader: 'babel-loader',
        options: {
          presets: ['@babel/preset-env']
        }
      }
    });
    return config;
  }
);
```

```ts
// Vite
import { defineConfig } from 'vite';
import react from '@vitejs/plugin-react';

export default defineConfig({
  plugins: [react()],
  resolve: {
    extensions: ['.js', '.jsx', '.ts', '.tsx', '.mjs']
  }
});
```
````

---
class: bg-[#d9d9d9] text-gray-900 font-bold
---

## Las estadísticas del combate

<div class="my-4">
    <span class="font-normal text-xl leading-none  ">
        A continuación se presentan las estadísticas de combate con el dragón. en las que se puede observar tangiblemente el impacto de la migración a vite.
    </span>
</div>


<div v-click class="mt-4"> 
    <span class="font-semibold">
        Se modificaron <span class="text-[#007aff] font-bold">100</span> líneas de código.
    </span>
</div>

<div v-click class="mt-4"> 
    <span class="font-semibold">
        Se modificaron <span class="text-[#007aff] font-bold">100</span> archivos.
    </span>
</div>


<div v-click class="mt-4"> 
    <span class="font-semibold">
        Se actualizaron <span class="text-[#007aff] font-bold">8</span> dependencias.
    </span>
</div>


<div v-click class="mt-4"> 
    <span class="font-semibold">
        Se necesitaron  <span class="text-[#007aff] font-bold">3</span> sprints.
    </span>
</div>


<div v-click class="mt-4"> 
    <span class="font-semibold">
        Se consumieron  <span class="text-[#007aff] font-bold">100</span>  tazas de café.
    </span>
    <iframe src="https://giphy.com/embed/zWwngnPi6vWfe" width="480" height="355" style="" frameBorder="0" class="giphy-embed absolute right-10 bottom-10 bg-[#d9d9d9]" allowFullScreen></iframe>

</div>


---
class: bg-[#d9d9d9] text-gray-900 font-bold
---

## Más allá del viaje.

<span class="font-semibold">
    Para concluir el viaje, se realizo una regresión completa del portal y del administrador de rk. Para asegurar que el proceso de migración fue exitoso.
</span>
<span class="font-semibold">
    Se noto el cambio  del proceso de compilacion entre vite y craco.
</span>
<div class="my-4">
    Imagen
</div>


### En el futuro

<span class="font-semibold">
    En el futuro se pretende realizar una migración a vite de toda la aplicación de RK el administrador de rk.
</span>
---
class: bg-[#d9d9d9] text-gray-900 font-bold
---

## Preguntas

<img src="https://pbs.twimg.com/media/GEiyeuhXkAA9owa.jpg"  class="w-1/2 mx-auto">