---
title: 'Inicio'
date: 2023-10-24
type: landing

design:
  spacing: '4rem'

sections:
  - block: biography
    content:
      username: admin
      button:
        text: Descargar CV
        url: uploads/resume.pdf
    design:
      banner:
        filename: kalen-emsley-Bkci_8qcdvQ-unsplash.jpg
      biography:
        style: 'text-align: justify; font-size: 0.85em;'
      avatar:
        size: large
        shape: rounded

  - block: experience
    content:
      username: admin
    design:
      date_format: 'Jan 2006'
      is_education_first: false

  - block: skills
    content:
      title: Aptitudes e Intereses
      username: admin

  - block: languages
    content:
      title: Idiomas
      username: admin

  - block: collection
    content:
      title: Proyectos
      subtitle: Trabajos destacados
      query:
        filter:
          folder: project
      count: 6
      sort_by: date
      sort_ascending: false
      view: showcase
    design:
      spacing:
        padding: ["20px","0","20px","0"]
---
