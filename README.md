# OpenClassroom P2 Project Reservia
Second project of web development course at OpenClassrooms:  "Transformez une maquette en site Web"
Goal is to integrate the model of a website called 'Reservia' for holiday bookings.

## Tools & Software used
- Visual Studio Code with extensions Prettier & Live Server
- Git & Github
- Gimp

## Items delivered by virtual company.
- Models for desktop & mobile sizes is given.
- Site images are made available for different size format: sm, md, l & xl.
- Icons come from [Font Awesome](https://fontawesome.com/)
- Colors used are : blue #0065FC - light blue #DEEBFF - grey #F2F2F2
- Police Raleway https://fonts.googleapis.com/css2?family=Raleway:wght@400;700&display=swap

## Specifications
- HTML5 & CSS3 must be used to integrate, without any framework (bootstrap for example)
- Search field must be input filed, where some text can be edited. Nevertherless, Search function must not be implemented.
- Each lodging or activity card must be clickable. For now, links are empty.
- Filters, although not functional, must change style when hover.
- In the navigation menu, links “Hébergements” et “Activités” are anchors linking to corresponding page sections.
- Even if no model for tablet size is given, integration must include it.
- Images size must be chosen so that they are retty and don't impact download time
- Code must use semantic tags & pass successfully W3C HTML & CSS validators
- Site will be compatible with Chrome & Firefox last versions.
- HTML & CSS must be separated in different files & directory must be organized properly
- Code must be versioned using git and must hae a remote respository on Github or Gitlab

## Tools & Software used
- Visual Studio Code with extensions Prettier & Live Server
- Git & Github
- Gimp

## Main design choices
- Reset CSS is used to protect from any web browser specificty
- Flexbox is used for the efficiency to align, justify and support responsive designs
- Relative sizing is mainly preferred: rem & vw/vh are used, except for radius and border (px)
- Responsive is achieved using Flexbox and 3 media queries : large screens (from 1590px), tablets (below 1030px) and mobile (below 760px) 

## Testing
- Initial testing is made using Life server on Viual Studio Code using Edge, Chrome & Firefox
- codepen.io is used when specific behaviour needs to be analyzed
- Raspberry Pi web server installed on local network is used to test with Safari and Opera on real smartphones ot tablets
- Screenfly web site tool cover any resolution
- webpagetest.org is used to test performance


