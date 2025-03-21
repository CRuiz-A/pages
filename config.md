<!--
Configuración global para Franklin.jl
-->
+++
author = "Cruiz"
mintoclevel = 2

# Define el prepath si el sitio está en un subdirectorio de GitHub Pages
prepath = "pages"

# Archivos o directorios que Franklin debe ignorar
ignore = ["node_modules/", "__site/"]

# Configuración del RSS (Requiere website_{title, descr, url})
generate_rss = true
website_title = "CRuiz Page"
website_descr = "Sitio web personal de CRuiz con Franklin.jl"
website_url   = "https://cruiz-a.github.io/pages/"
+++

<!--
Definiciones de comandos LaTeX globales para todo el sitio
-->
\newcommand{\R}{\mathbb{R}}
\newcommand{\scal}[1]{\langle #1 \rangle}
