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
    background_style: bg-primary
    title: The Core
    text: At Nodus, we bridge the gap between complex biological systems and cutting-edge technology. We believe that the future of conservation lies in data. By integrating advanced analytics with field ecology, we provide the insights needed to understand and protect our planet’s most vital ecosystems.
    actions:
      - title: Get Started!
        url: '#page-top'
        class: btn-light

  - type: services.html
    section_id: services
    #background_style: bg-info
    title: At Your Service
    services:
      - title: AI Detection Models
        text: Automated wildlife identification and monitoring using state-of-the-art machine learning.
        icon: bi-gem text-info
        url: https://startbootstrap.com/
      - title: Acoustic & Visual Monitoring
        text: Large-scale biodiversity assessment through trap cameras and passive acoustic sensors.
        icon: bi-rocket-takeoff
      - title: Spatial Analytics & Remote Sensing
        text: Precision mapping and ecosystem health evaluation via satellite imagery and GIS data.
        icon: bi-activity
      - title: Ecosystem Health Indicators
        text: Identifying and analyzing bioindicators to measure and predict environmental resilience.
        icon: bi-heart-fill


  - type: portfolio.html
    # this section has always ID 'portfolio'
    #section_id: portfolio
    #background_style: bg-dark
    projects:
      - title: Project 1
        text: This is a very short project description.
        # the images are located in:
        # img/portfolio/fullsize
        # img/portfolio/thumbnails
        icon: 1.jpg
        url: '#'
      - title: Project 2
        text: This is a very short project description.
        icon: 2.jpg
        url: '#'
      - title: Project 3
        text: This is a very short project description.
        icon: 3.jpg
        url: '#'
      - title: Project 4
        text: This is a very short project description.
        icon: 4.jpg
        url: '#'
      - title: Project 5
        text: This is a very short project description.
        icon: 5.jpg
        url: '#'
      - title: Project 6
        text: This is a very short project description.
        icon: 6.jpg
        url: '#'

#  - type: aside.html
#    section_id: aside
#    title: Free Download at Start Bootstrap!
#    actions:
#      - title: Download Now!
#        url: https://startbootstrap.com/themes/creative/
#        class: btn-light

  - type: members.html
    section_id: members
    title: Our Crew!
    background_style: bg-light text-dark
    members:
      - title: John Sebastian Ovalle
        text: Lead Ecological Data Scientist
        image: assets/img/members/person1.jpg
        url: '#'
      - title: Isabella López
        text: Biodiversity Analyst
        image: assets/img/members/person2.jpg
        url: '#'


#  - type: timeline.html
#    section_id: timeline
#    title: Major Achievements!
#    background_style: bg-dark text-primary
#    last_image: assets/img/timeline-end.png
#    actions:
#      - image: assets/img/portfolio/thumbnails/1.jpg
#        title: >+
#          2017-2018
#          **Humble Beginnings**
#        text: >-
#          We begun with small group of people willing to work hard and make our
#          teaching skills worth , in front of all others!
#      - image: assets/img/portfolio/thumbnails/2.jpg
#        title: >+
#          November 2019
#          An Coaching started
#        text: >-
#          We started to gather like minded people and started our stategies
#          and future plans to them. As a result , interested people joined us!

  - type: contact.html
    section_id: contacts
    title: Let's Get In Touch!
    text: >-
      Ready to start your next project with us? Give us a call or send us an email
      and we will get back to you as soon as possible!
    actions:
    - title: +57 3167659832
      icon: bi-telephone-fill
    - title: E-Mail
      icon: bi-envelope-fill
      url: mailto:nodus.bio@gmail.com
    - title: Twitter
      icon: bi-twitter
      url: '#'
    - title: Facebook
      icon: bi-facebook
      url: '#'

---
