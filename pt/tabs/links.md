---
layout: links
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_links

# publish date (used for seo)
# if not specified, site.time will be used.
#date: 2022-03-03 12:32:00 +0000

# for override items in _data/lang/[language].yml
#title: My title
#button_name: "My button"
# for override side_and_top_nav_buttons in _data/conf/main.yml
#icon: "fa fa-bath"

# seo
# if not specified, date will be used.
#meta_modify_date: 2022-03-03 12:32:00 +0000
# check the meta_common_description in _data/owner/[language].yml
#meta_description: ""

# optional
# if you enabled image_viewer_posts you don't need to enable this. This is only if image_viewer_posts = false
#image_viewer_on: true
# if you enabled image_lazy_loader_posts you don't need to enable this. This is only if image_lazy_loader_posts = false
#image_lazy_loader_on: true
# exclude from on site search
#on_site_search_exclude: true
# exclude from search engines
#search_engine_exclude: true
# to disable this page, simply set published: false or delete this file
#published: false


# you can always move this content to _data/content/ folder
# just create new file at _data/content/links/[language].yml and move content below.
###########################################################
#                Links Page Data
###########################################################
page_data:
  main:
    header: "Enlaces"
    info: "Enlaces de interés."

  # To change order of the Categories, simply change order. (you don't need to change list order.)
  category:
    - title: "Programación"
      type: id_programming
      color: "#F4A273"
    - title: "Repositorios"
      type: id_repositories
      color: "#62b462"
    - title: "Personal"
      type: id_personal
      color: "gray"

  list:
    -
    # programming
    - type: id_programming
      title: "ResearchGate"
      url: "https://www.researchgate.net/"
      info: "ResearchGate es una página web en donde investigadores pueden colaborar en muchos campos de la ciencia."
    - type: id_programming
      title: "Stack OverFlow"
      url: "https://stackoverflow.com/"
      info: "Stack Overflow es una página web con interacción pregunta-respuesta para programadores de diferentes lenguajes de programación."

    # repositories
    - type: id_repositories
      title: "NCBI"
      url: "https://www.ncbi.nlm.nih.gov/"
      info: "National Center for Biotechnology Information (NCBI) es un repositorio que contiene muchos conjuntos de datos biológicos de especial interés para la bioinformática.."
    - type: id_repositories
      title: "Kaggle"
      url: "https://www.kaggle.com/"
      info: "Kaggle es un repositorio en donde se pueden encontrar una gran variedad de conjuntos de datos que son útiles para probar los algoritmos de machine learning."

    # personal
    - type: id_personal
      title: "ORCID"
      url: "https://orcid.org/my-orcid?orcid=0000-0003-2501-3265"
      info: "Página personal de ORCID."
    - type: id_personal
      title: "Google Scholar"
      url: "https://scholar.google.com/citations?hl=es&user=Ho4p9ugAAAAJ"
      info: "Página personal de Google Scholar."
    - type: id_personal
      title: "GitHub"
      url: "https://github.com/RaulGalindoIIMAS"
      info: "Página personal de GitHub."
    - type: id_personal
      title: "LinkedIn"
      url: "https://mx.linkedin.com/in/raul-galindo-562351191"
      info: "Página personal de LinkedIn."
---
