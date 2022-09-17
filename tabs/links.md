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
    header: "Professional Development"
    info: "Here you will find information on my Professional Development."

  # To change order of the Categories, simply change order. (you don't need to change list order.)
  category:
    - title: "Certifications"
      type: id_certifications
      color: "#62b462"
    - title: "Education/Training"
      type: id_education
      color: "#F4A273"
    - title: "Resume"
      type: id_resume
      color: "gray"

  list:
    # Certifications
    - type: id_certifications
      title: "CISSP - ISC(2)"
      url: "https://www.credly.com/badges/56c43c47-8cc7-41e4-b581-e44138752d00/public_url"
      info: "You can verify this certification through Credly by clicking on the link to the left - (Credential ID: FNX6Y2MK3BBE15WR)"
    - type: id_certifications
      title: "AWS-Certified Solutions Architect"
      url: "https://www.credly.com/badges/1c73b6ff-c61f-4e4c-b4d0-22a5d413337c/public_url"
      info: "You can verify this certification through Credly by clicking on the link to the left - (Credential ID: 714277)"
    - type: id_certifications
      title: "CompTIA - Security +"
      url: "https://www.credly.com/badges/52919758-c15b-47cd-8db5-3c8a5905e711/public_url"
      info: "You can verify this certification through Credly by clicking on the link to the left - (Verification Code: 2WQVW5MPPHREQ6G8)"
    - type: id_certifications
      title: "CompTIA - Network +"
      url: "https://www.credly.com/badges/fc596b26-7964-4089-bccc-0fd04049df04/public_url"
      info: "You can verify this certification through Credly by clicking on the link to the left - (Verification Code: Y3R9JMJHGCQE18G5)"
    - type: id_certifications
      title: "CompTIA - A+"
      url: "https://www.credly.com/badges/c81f00ae-b8f1-41f2-ab77-cc566900e566/public_url"
      info: "You can verify this certification through Credly by clicking on the link to the left - (Verification Code: L81GJERNHLE1129P)"  

    # education/training
    - type: id_education
      title: "Colorado State University - Global Campus"
      url: "https://csuglobal.edu/"
      info: "Graduation Year - 2018 - Bachelor of Science Degree - Information Technology/Cyber Security. Relevant Coursework: Information Systems and Security, Network Enterprise Solutions, Intermediate Networking, Basic Programming, Database Management, Digital Forensics and Investigations, Principles of Cyber Security, Ethical Hacking and Penetration Testing, Information Technology Project Management."
    - type: id_education
      title: "Florida State University"
      url: "https://www.fsu.edu/"
      info: "Graduation Year - 2011 - Bachelor of Science Degree - Criminology."
    - type: id_education
      title: "Gulf Coast State College"
      url: "https://www.gulfcoast.edu/"
      info: "Graduation Year - 2009 - Associate of Arts Degree - Information Technology/Cyber Security."

    # resume
    - type: id_resume
      title: "Resume"
      url: "https://initcyber.com/assets/resume.pdf"
      info: "Here you can find a PDF copy of my resume."    
    - type: id_resume
      title: "LinkedIn"
      url: "https://www.linkedin.com/in/justinjohnson86/"
      info: "LinkedIn also reflects my professional development throughout my career."
---
