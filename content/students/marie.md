---

# FILENAME : please use your OpenClassrooms's name, available in your url.
# Example: https://openclassrooms.com/membres/celinemartinet
# must be the name of your file. If file name is celinemartinet.md, title is celinemartinet.
# lowercase, no blank space, Capital case or special character.
title: marie

# First name or full name
name: Marie
date: 2016-10-28 17:20

# One line.
# If you need more space, go to the next line and add 4 spaces on the left, as in 'description'.
objective: Devenir digital nomade !
short_description: J'aime l'informatique, je me lance dans le développement d'applications !

# don't touch that
template: students
description:
    Suite à une mauvause orientation, je n'ai pas fait d'études, donc je me 
    lance avec Openclassroom. Le format à distance me plaît, et le parcours
    développement d'applications me correspond.

# image must be located in content/images/students
# name should be the same as this file. Eg: celinemartinet.png
image: marie.jpg

# Change this to True when you do you pull request.
public: True

# You need to keep the exact same structure for each new project.
projects:
  - title: Présentez-vous !
    description: Une présentation de moi-même et un lien vers mon LinkedIn.
    # Create a new repository for your images. Name it the same as your nickname and profile picture.
    # Image must be here: content/images/students/yourrepo/project1.png
    image: marie/projet_1.jpg
    link: www.linkedin.com/in/marie-bricard-35749a15b
    # 'true' makes it fully available.
    # 'false' will add a black layer on the picture. IT WILL BE PUBLIC!
    finished: true
  - title: Intégrez la communauté !
    description: Modifier un projet Open Source pour comprendre le fonctionnement de Git, de Github et des pull requests. 
    image: marie/projet_2.jpg
    link: https://github.com/marielarry/alumnis
    finished: true
  - title: Aidez MacGyver à sortir !
    description: Création d’un jeu développé en Python et utilisant PyGame.
    image: marie/projet_3.jpg
    link: https://www.github.com
    finished: false
---
