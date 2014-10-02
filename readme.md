# NaWeb
##(Núcleo de Pesquisa em Ambientes Colaborativos na Web)

Projeto consiste numa plataforma de Wordpress para o núcleo de pesquisas NaWeb (Núcleo de Pesquisa em Ambientes Colaborativos na Web). Seu objetivo inicial é suprir a necessidade da equipe de ter um ambiente colaborativo central, onde haja trocas de informações entre os projetos do núcleo e a comunidade global. 

Essa plataforma é aberta a todos, e tem como objetivo trazer uma rica documentação e uma programação fácil de entender, para que outros núcleos ou laboratórios possam também modificar e utilizar conforme suas necessidades.

---
## Características
---

- Instalação rápida
- Fácil edição e customização
- Plataforma voltada para usuários comuns

---
## Instalação
--- 

### Requerimentos iniciais

- ~~Wordpress 4.0~~ (ainda não integrado)
- Node.js
- Gulp
    + Sass compile (gulp-ruby-sass)
    + Autoprefixer (gulp-autoprefixer)
    + Minify CSS (gulp-minify-css)
    + JSHint (gulp-jshint)
    + Concatenation (gulp-concat)
    + Uglify (gulp-uglify)
    + Compress images (gulp-imagemin)
    + LiveReload (gulp-livereload)
    + Caching of images so only changed images are compressed (gulp-cache)
    + Notify of changes (gulp-notify)
    + Clean files for a clean build (del)
- Projeto

*Objetivo é fazer a instalação automática com o plugin [Duplicator do Wordpress](https://wordpress.org/plugins/duplicator/)*

### Instalação do Node.js

Acesse o site [nodejs.org](http://nodejs.org/),faça o download do arquivo de instalação e instale na sua máquina.

### Instalação do Gulp

Abra o terminal:

- Instale o Gulp globalmente (talvez seja necessário o `sudo`)
`$ npm install gulp -g`

- Vá até a pasta do projeto e instale o Gulp local
`$ npm init`
`npm install gulp --save-dev`

- Instale os seguintes plugins
`$ npm install gulp-ruby-sass gulp-autoprefixer gulp-minify-css gulp-jshint gulp-concat gulp-uglify gulp-imagemin gulp-notify gulp-rename gulp-livereload gulp-cache del --save-dev`

- Pronto, agora com os arquivos do projeto em pasta, rode o comando
`gulp watch`

- Ele ficará rodando enquanto você altera os arquivos dentro da pasta "dist" e "src"

---
## Utilização
---

h1 - h6: Normais para texto
h1 - h6 .logo: Usado para fazer o logo do NaWeb

---
## Suporte
---



---
## Documentação
---

### 24/09/2014


### 25/09/2014
Instalação do Gulp e seus plugins
- Sass compile (gulp-ruby-sass)
- Autoprefixer (gulp-autoprefixer)
- Minify CSS (gulp-minify-css)
- JSHint (gulp-jshint)
- Concatenation (gulp-concat)
- Uglify (gulp-uglify)
- Compress images (gulp-imagemin)
- LiveReload (gulp-livereload)
- Caching of images so only changed images are compressed (gulp-cache)
- Notify of changes (gulp-notify)
- Clean files for a clean build (del)
*Referência [Mark Good Year Blog](http://markgoodyear.com/2014/01/getting-started-with-gulp/)*
Organização das pastas
- Dist: Pasta dos arquivos finais
- Src: Pasta dos arquivos brutos
Incorporação da estrutura de colunas do Boilerplate Skeleton

### 01/10/2014
Teste do BrowserSync, porém vou utilizar o LiveReload
Instalação e configuração do LiveReload
Teste do MAMP PRO em paralelo
    Vantagens
    - Não depende de uma pasta fixa
    - Sincronizo direto com o Dropbox
    - Utilizo o LiveReload sem precisar mover todo meu dev para uma pasta fixa

### 02/10/2014
Estudo da forma de documentação
