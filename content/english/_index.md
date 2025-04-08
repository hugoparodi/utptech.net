---
###################### hero slider ###########################
slider:
  enable : true
  slider_item:
  # slider item loop
  - bg_image : images/banner/empowering-1.jpg
    animation_from : left
    subtitle : Empowering Your Vision
    title : Technology That Works for You
    content : Always Up to Par, Always Ahead. 
    pagination_icon : ti-comments # themify icon pack : https://themify.me/themify-icons
    pagination_name : Consultation
    button:
      enable : true
      label: More details
      link : "about/"
      
  # slider item loop
  - bg_image : images/banner/up-topar-2A.jpg
    animation_from : up
    subtitle : Industry Solutions
    title : Empowering Every Sector
    content : From healthcare to finance — Up To Par Technologies delivers IT solutions tailored to your industry.
    pagination_icon : ti-briefcase # themify icon pack
    pagination_name : Industries
    button:
      enable : true
      label: Explore Verticals
      link : "industries/"
        
  # slider item loop
  - bg_image : images/banner/itsolutions-1.jpg
    animation_from : down
    subtitle : Services We Offer
    title : Smart IT Solutions, Delivered
    content : Managed IT, Cloud, Cybersecurity & more — we bring scalable, secure tech services to power your growth.
    pagination_icon : ti-settings # themify icon pack
    pagination_name : Services
    button:
      enable : true
      label: View Services
      link : "service/"
      
  # slider item loop
  - bg_image : images/banner/banner-4.jpg
    animation_from : right
    subtitle : Products That Perform
    title : Explore Our Tech Solutions
    content : Discover powerful, ready-to-deploy software and hardware solutions designed to elevate your business.
    pagination_icon : ti-package # still relevant for "products"
    pagination_name : Products
    button:
      enable : true
      label: View Products
      link : "products/"

  # slider item loop
  - bg_image : images/banner/banner-6.jpg
    animation_from : left
    subtitle : Let’s Connect
    title : Ready to Elevate Your IT?
    content : Talk to our experts about solutions that move your business forward. We're here to help — anytime.
    pagination_icon : ti-headphone # themify icon for contact/support
    pagination_name : Contact Us
    button:
      enable : true
      label: Get in Touch
      link : "contact/"
########################################## Service ####################################
service:
  enable : false
  title: "Service We Provide"
  subtitle: "Best Service"
  section: "service" # showing items from service section
  # service item comes from "content/service" folder

######################################## About #########################################
about:
  enable : false
  bg_image : "images/background/about-bg.jpg"
  title : "Who We Are?"
  content : "Excepteur sint occaecat cupidatat non proident sunt culpa qui officia deserunt mollit anim id est laborum."
  # bullet point
  bullet_point:
  - "Business Services"
  - "Audit & Assurance"
  - "IT Control Solutions"
  - "Business Services"
  - "Audit & Assurance"
  - "IT Control Solutions"
  button:
    enable : true
    label : "Explore More"
    link : "about/"

##################################### Skill ##############################################
skill:
  enable : false
  subtitle : Our Skills
  title : Why Choose Us
  content: Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed eiusmod tempor incididunt laboris nisi ut aliquip ex ea commodo consequat. <br><br> Duis aute irure dolor in reprehenderit voluptate velit esse cillum dolore fugiat nulla pariatur. Excepteur sint ocaecat cupidatat non proident sunt culpa qui officia deserunt mollit anim id est laborum. sed perspiciatis unde omnisiste natus error sit voluptatem accusantium.doloremque ladantium totam rem aperieaque ipsa quae ab illo inventore.veritatis. et quasi architecto beatae vitae dicta sunt explicabo.
  # funfacts
  funfacts :
  - icon : ti-server # themify icon pack : https://themify.me/themify-icons
    title : Projects Done
    count : 230
    
  - icon : ti-face-smile # themify icon pack : https://themify.me/themify-icons
    title : Satisfied Clients
    count : 789
    
  - icon : ti-thumb-up # themify icon pack : https://themify.me/themify-icons
    title : Cup Of Coffee
    count : 580

  # progressbar
  progressbar : 
  - title : Branding
    progress : 85%
    
  - title : Consulting
    progress : 90%
    
  - title : Business
    progress : 75%
    
  - title : Promotion
    progress : 90%
      
########################################## project ####################################
project:
  enable : false
  title: "Latest Projects"
  subtitle: "Our Works"
  section: "project" # showing items from project section
  # project item comes from "content/project" folder

########################################### Mission ###################################
mission:
  enable : false
  subtitle : Our Goal
  title : Company Mission
  content : Lorem ipsum dolor sit amet consectetur adipisicing elit sed eiusmod tempor didunt laboris nisi ut aliquip ex ea commodo consequat.
  image : images/chart.png
  accordion:
  - title : Our Company Mission
    description : Duis aute irure dolor in reprehenderit voluptate velit esse cillum dolore fugiat nulla pariatur.Excepteur sint ocaecat cupidatat non proident sunt culpa qui officia deserunt mollit anim id est laborum.
    
  - title : Our Company Vision
    description : Duis aute irure dolor in reprehenderit voluptate velit esse cillum dolore fugiat nulla pariatur.Excepteur sint ocaecat cupidatat non proident sunt culpa qui officia deserunt mollit anim id est laborum.
    
  - title : Our Company Goal
    description : Duis aute irure dolor in reprehenderit voluptate velit esse cillum dolore fugiat nulla pariatur.Excepteur sint ocaecat cupidatat non proident sunt culpa qui officia deserunt mollit anim id est laborum.

##################################### Promo video ####################################
promo_video:
  enable : false
  title : "We Are Alawys <br> Comited"
  bg_image : "images/background/promo-video.jpg"
  video_URL : "https://www.youtube.com/embed/ResipmZmpDU"
  video_title : "Lorem ipsum dolor <br> sit amet con."

##################################### call to action #################################
testimonial:
  enable : false
  subtitle : Clients
  title : What client Say
  image : images/client.png
  testimonial_item :
  - name : Julia Robertson
    content : Lorem ipsum dolor sit amet constur adipisicing elit sed eiusmtempor incid sed dolore magna aliqu enim minim veniam quis nostrud exercittion ullamco labo ris nisi aliquip excepteur.
    designation : Happy Clients
    
  - name : Julia Robertson
    content : Lorem ipsum dolor sit amet constur adipisicing elit sed eiusmtempor incid sed dolore magna aliqu enim minim veniam quis nostrud exercittion ullamco labo ris nisi aliquip excepteur.
    designation : Happy Clients
    
  - name : Julia Robertson
    content : Lorem ipsum dolor sit amet constur adipisicing elit sed eiusmtempor incid sed dolore magna aliqu enim minim veniam quis nostrud exercittion ullamco labo ris nisi aliquip excepteur.
    designation : Happy Clients

##################################### call to action #################################
call_to_action:
  enable : true
  bg_image : "images/background/cta.jpg"
  title : "Up to Par Technologies, give the smart IT solution for your business"
  button:
    enable : false
    label : "get a quote"
    link : "contact/"
      
########################################## blog ####################################
blog:
  enable : false
  title: "Company News"
  subtitle: "Latest News"
  section: "blog"
  # blog item comes from "content/blog" folder
  
################################ clints logo slider ################################
clients_logo_slider:
  enable : false
  client_logos:
  - logo: "images/client-logo/client-logo-1.png"
    link: "#"

  - logo: "images/client-logo/client-logo-2.png"
    link: "https://examplesite.com"

  - logo: "images/client-logo/client-logo-3.png"
    link: "#"

  - logo: "images/client-logo/client-logo-4.png"
    link: "https://examplesite.com"

  - logo: "images/client-logo/client-logo-5.png"
    link: "#"

  - logo: "images/client-logo/client-logo-3.png"
    link: "https://examplesite.com"

    
---