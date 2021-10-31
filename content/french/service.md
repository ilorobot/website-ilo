---
title: "Service"
description: "Voici ce que nous proposons avec ilo"
bg_image: "images/feature-bg.png"
layout: "service"
draft: false

########################### about service #############################
about:
  enable : false
  title : "Creative UX/UI Design Agency"
  content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Voluptate soluta corporis odit, optio
          cum! Accusantium numquam ab, natus excepturi architecto earum ipsa aliquam, illum, omnis rerum, eveniet
          officia nihil. Eum quod iure nulla, soluta architecto distinctio. Nesciunt odio ullam expedita, neque fugit
          maiores sunt perferendis placeat autem animi, nihil quis suscipit quibusdam ut reiciendis doloribus natus nemo
          id quod illum aut culpa perspiciatis consequuntur tempore? Facilis nam vitae iure quisquam eius harum
          consequatur sapiente assumenda, officia voluptas quas numquam placeat, alias molestias nisi laudantium
          nesciunt perspiciatis suscipit hic voluptate corporis id distinctio earum. Dolor reprehenderit fuga dolore
          officia adipisci neque!"
  image : "images/company/company-group-pic.jpg"


########################## featured service ############################
featured_service:
  enable : false
  service_item:
    # featured service item loop
    - name : "Interface Design"
      icon : "fas fa-flask"
      color : "primary"
      content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Saepe enim impedit repudiandae omnis est temporibus."

    # featured service item loop
    - name : "Product Branding"
      icon : "fas fa-leaf"
      color : "primary-dark"
      content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Saepe enim impedit repudiandae omnis est temporibus."

    # featured service item loop
    - name : "Game Development"
      icon : "fas fa-lightbulb"
      color : "primary-darker"
      content : "Lorem ipsum dolor sit amet, consectetur adipisicing elit. Saepe enim impedit repudiandae omnis est temporibus."


############################# Service ###############################
service:
  enable : true
  title : "Nos Services"
  description : "Nous voulons proposer un robot, son application mobile, et différents tutoriels pour les enseignants et les élèves. Nous voulons aussi proposer une service après vente pour assurer une utilisation durable du robot."
  service_item:
        # service item loop
    - icon : fas fa-bullseye #https://fontawesome.com/v5.15/icons
      name: éducation
      content: "Tous les élèves se doivent d'avoir accès à l'enseignement de la programmation"

    # service item loop
    - icon : fas fa-leaf #https://fontawesome.com/v5.15/icons
      name: Développement
      content: "Service après vente et droit de réparer"

############################# call to action #################################
cta:
  enable : true
  # call to action content comes from "_index.md"
---
