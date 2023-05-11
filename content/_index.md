---
# Leave the homepage title empty to use the site title
title: Paulo R. S. S. Alves
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: Sobre
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      
  - block: features
    content:
      title: Habilidades  
      items:
      - description: Construção de instrumentos psicométricos e análise da dados quantitativos
        icon: chart-line
        icon_pack: fas
        name: Psicometria
      - description: Análises precisas com os métodos mais atualizados
        icon: r-project
        icon_pack: fab
        name: R
      - description: Análise de textos com Iramuteq
        icon: file-lines
        icon_pack: fas
        name: Análise textual quantitativa
    
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
      - company: Autônomo 
        company_logo: 
        company_url: ""
        date_end: ""
        date_start: "2022-10-01"
        description: |2-
            Serviços prestados: 
  
            * Análise de descritiva de dados ;
            * Execução de testes estatísticos inferenciais e preditivos;
            * Consultoria em análise de dados e interpretação de dados e resultados de pesquisa;
            * Produção de relatórios sobre as análises executadas; 
            * Revisão de redação de resultados de análises estatísticas para artigos científicos.
        location: Remoto 
        title: Psicometrista e analista de dados 
        
      - company: Autônomo 
        company_logo: 
        company_url: ""
        date_end: ""
        date_start: "2022-06-01"
        description: |2-
            Psicoterapeuta psicodinâmico de orientação predominantemente _reichiana_.
            Dialogo com outras abordagens, sobretudo (em ordem de frequência): psicologia anaĺitica, Gestalt terapia, TCC.
        location: Remoto 
        title: Psicoterapeuta 
      title: Experiência 
    design:
      columns: "2"
    
  - block: accomplishments
    content:
      date_format: Jan 2006
      items:
      - certificate_url: 
        date_end: "2023-05-04"
        date_start: "2023-03-02"
        description: "Análises estatísticas descritivas e inferenciais. Possuo também habilitação análoga para a linguagem de programação R."
        organization: Psicometria Online 
        organization_url: https://psicometriaonline.com.br/
        title: Análises Bi e Multivariadas 
        url: ""
        
      - certificate_url: 
        date_end: "2023-05-04"
        date_start: "2023-04-02"
        description: "Análises com dados não-estruturados para extrair padrões em textos usando métodos quantitativos."
        organization: Psicometria Online 
        organization_url: https://psicometriaonline.com.br/
        title: IRAMUTEQ - Análises Textuais 
        url: ""          
      subtitle: null
      title: Habilitações 
    design:
      columns: "2" 

#  - block: collection
#    id: posts
#    content:
#      title: Recent Posts
#      subtitle: ''
#      text: ''
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
#      # Filter on criteria
#      filters:
#        folders:
#          - post
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
#      # Choose how many pages you would like to offset by
#      offset: 0
#      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
#      # Choose a layout view
#      view: compact
#      columns: '2'
#  - block: portfolio
#    id: projects
#    content:
#      title: Projects
#      filters:
#        folders:
#          - project
#      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
#      default_button_index: 0
#      # Filter toolbar (optional).
#      # Add or remove as many filters (`filter_button` instances) as you like.
#      # To show all items, set `tag` to "*".
#      # To filter by a specific tag, set `tag` to an existing tag name.
#      # To remove the toolbar, delete the entire `filter_button` block.
#      buttons:
#        - name: All
#          tag: '*'
#        - name: Deep Learning
#          tag: Deep Learning
#        - name: Other
#          tag: Demo
#    design:
#      # Choose how many columns the section has. Valid values: '1' or '2'.
#      columns: '1'
#      view: showcase
#      # For Showcase view, flip alternate rows?
#      flip_alt_rows: false
#  - block: markdown
#    content:
#      title: Gallery
#      subtitle: ''
#      text: |-
#        {{< gallery album="demo" >}}
#    design:
#      columns: '1'
#  - block: collection
#    id: featured
#    content:
#      title: Featured Publications
#      filters:
#        folders:
#          - publication
#        featured_only: true
#    design:
#      columns: '2'
#      view: card
#  - block: collection
#    content:
#      title: Recent Publications
#      text: |-
#        {{% callout note %}}
#        Quickly discover relevant content by [filtering publications](./publication/).
#        {{% /callout %}}
#      filters:
#        folders:
#          - publication
#        exclude_featured: true
#    design:
#      columns: '2'
#      view: citation
#  - block: collection
#    id: talks
#    content:
#      title: Recent & Upcoming Talks
#      filters:
#        folders:
#          - event
#    design:
#      columns: '2'
#      view: compact
#  - block: tag_cloud
#    content:
#      title: Popular Topics
#    design:
#      columns: '2'
  - block: contact
    content:
      contact_links:
      - icon: square-instagram
        icon_pack: fab
        link: https://www.instagram.com/paulorssalves/ 
        name: Instagram
      - icon: linkedin 
        icon_pack: fab
        link: https://www.linkedin/com/in/paulorssalves/ 
        name: LinkedIn
      email: paulorssalves@gmail.com 
      phone: (21) 97662 5742
      subtitle: Sinta-se à vontade para entrar em contato comigo usando quaisquer um dos meios abaixo.
      title: Contato 
    design:
      columns: "2"
    id: contact  
    design:
      columns: '2'
---
