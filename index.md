---
layout: home
header:
  title: NODUS
  text:
  action: # action button is optional
    label: Services
    url: '#services'


sections:
  - type: call-to-action.html
    section_id: about
    background_style: bg-white text-dark
    title: The Core
    text: At Nodus, we bridge the gap between complex biological systems and cutting-edge technology. We believe that the future of conservation lies in data. By integrating advanced analytics with field ecology, we provide the insights needed to understand and protect our planet’s most vital ecosystems.
    actions:
      - title: Get Started!
        url: '#services'
        class: btn-light

  - type: services.html
    section_id: services
    title: Services
    subtitle: 
    services:
      # TARJETA 1: 
      - title: AI Detection Models
        text: Automated wildlife identification and monitoring using state-of-the-art machine learning.
        image: /assets/img/services/jaguar-ai.png 
        icon: bi bi-camera 
        url: "/servicios/monitoreo"

      # TARJETA 2: 
      - title: Acoustic & Visual Monitoring
        text: Large-scale biodiversity assessment through trap cameras and passive acoustic sensors.
        image: /assets/img/services/monitoreo-acustico.png
        icon: bi bi-mic
        url: "/servicios/estudios"

      # TARJETA 3: 
      - title: Spatial Analytics & Remote Sensing
        text: Precision mapping and ecosystem health evaluation via satellite imagery and GIS data.
        icon: bi-activity
        image: /assets/img/services/analisis-espacial.png 
        icon: bi bi-geo-alt 
        url: "/servicios/ciencia"

      # TARJETA 4:
      - title: Ecosystem Health Indicators
        text: Identifying and analyzing bioindicators to measure and predict environmental resilience.
        icon: bi-heart-fill
        image: /assets/img/services/indicadores.png 
        icon: bi bi-laptop 
        url: "/servicios/capacitaciones"


  - type: timeline.html
    section_id: timeline
    title: Trajectory & Research
    subtitle: Converging data into scientific knowledge
    central_node: "NODUS CORE"
    projects:
      - title: "First verified high-elevation record of the jaguar (Panthera onca) on the eastern slope of the Western Andes, Colombia"
        text: "Published."
        tag: "Camera trapping"
        paper_url: "https://doi.org/10.21068/2539200X.1321"
        position: "top-left"
        icon: "bi-camera" 
      - title: "Echoes of the poison's return: Passive Acoustic Monitoring and community involvement in the reintroduction of Oophaga lehmanni"
        text: "In progress."
        tag: "Acoustics"
        paper_url: ""
        position: "top-right"
        icon: "bi-mic" 
#      - title: "Jaguar Machine Learning"
 #       text: "State-of-the-art models for individual Panthera onca ID."
  #      tag: "Computer Vision"
   #     paper_url: "#"
    #    position: "bottom-left"
#      - title: "Remote Sensing Health"
#        text: "Satellite imagery & GIS for ecosystem health evaluation."
#        tag: "GIS & Remote Sensing"
#        paper_url: ""
#        position: "bottom-right"
#      - title: "Ecological Restoration"
#        text: "Data-driven indicators for ecosystem recovery."
#        tag: "Restoration"
#        position: "mid-left" # Nueva posición
#      - title: "Urban Biodiversity"
#        text: "Monitoring wildlife in peri-urban corridors."
#        tag: "Urban Ecology"
#        position: "mid-right" # Nueva posición


  - type: members.html
    section_id: members
    title: Our Crew!
    background_style: bg-light text-dark
    members:
      - title: John Sebastian Ovalle
        text: Biologist & MSc Engineering
        image: assets/img/members/person1.jpg
        url: '#'
      - title: Isabella López
        text: Biologist
        image: assets/img/members/person2.jpeg
        url: '#'

  - type: contact.html
    section_id: contacts
    title: Let's Get In Touch!
    text: >-
      Ready to start your next project with us? Give us a call or send us an email
      and we will get back to you as soon as possible!
    actions:
    - title: Call Us
      icon: bi-telephone-fill
      url: tel:57 3167659832
    - title: E-Mail
      icon: bi-envelope-fill
      url: mailto:nodus.bio@gmail.com
#    - title: Twitter
#      icon: bi-twitter
#      url: '#'
#    - title: Facebook
#      icon: bi-facebook
#      url: '#'

---
