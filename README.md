# Agustarello - Restaurant in Rome 

# Intro
This is a website for a restaurant in Rome. It's my father's restaurant, it used to be my grandfather's restaurant. A long tradition of genuine food and
typical cuisine... But he had never had a website.

![Image](#)

#### A live demo can be found [here](#)

# Table of content
- Intro
- Description
- UX
   - *User Stories*
   - *Strategy*
   - *Scope*
   - *Structure*
   - *Skeleton*
   - *Surface*
- Tecnologies
   - *Frameworks*
   - *Libraries and programs*
   - *Other resources*
- Testing
   - *User stories Testing*
   - *Website Testing*
- Project barrier and solutions
- Deployment
- Credits
   - *Media*
   - *Text*
   - *Code snippets*
   - *Thanks to*

# Description
Agustarello is a family-run restaurant in the center of Rome. Its strengths are in the quality of the food and in the rustic and welcoming environment. 
Agustarello is a reference point in Rome for both local customers and tourists and for all those who want to experience the atmosphere of an authentic Roman 
*trattoria*.

# UX
According to [research](https://restaurant.opentable.com/news/insider-information/heres-what-diners-do-online-before-they-eat-out-are-you-prepared/) 
commissioned by **Opentable**, over 80% of potential customers visit a restaurant's website before deciding whether or not to go there. 
On the data that emerged from the research and on my personal working experience I based the user stories.
## **User Stories**
  - **As a customer:**
    - I want to book a table by the restaurant website so I can check tha availabity of timing withouth calling the place
    - I want to check out a menu so I can see what kind of cuisine the restaurant is and how much is expensive
    - I want to get direction for the restaurant so I can decide wich way is the best to get there (car or public transport)
    - I want to see some picture of the place and the food so I can get an early idea of the place
    - I want to see some reviews from other customers who already been there because I trust of the reviews in internet

  - **As the owner:** 
    - I want to have a better web presence so I can be found when people looking for my restaurant.
    - I want to discourage phone calls so I can use my time otherways than answering phone calls.
    - I want to explain how to get to the restaurant, by public transport or car and where to park close to the restaurant so customers dosn't change their mind.
    - I want to introduce the history of the place and the type of traditional cuisine because I'm very proud of it.
## **Strategy**
The website was designed to meet the needs of the owner and the consumers. The main purpose is to increase the online presence of the business which allows 
potential customers to obtain information about the restaurant. The owner wanted to manage his online presence directly and not only through review sites 
or search engines. 
## **Scope**
The website wants to be a showcase of the restaurant. The visitor can get all the information he wants to get an idea and avoid contacting the owner directly 
for anything other than booking a table. 
A feature that is not present but that must be implemented in the future will be that of being able to make reservations through the website.
## **Structure**
The structure of the site is a prevalence of images over text. Very short paragraphs and captivating images of the dishes on the menu. A lot of attention
the other social profiles will be provided with the map of the area and the way to reach the restaurant.
## **Skeleton**
Scrolling website with four main section: HOME - OUR STORY - MENU - CONTACT

Wireframes:
- [Desktop](./assets/wireframes/desktop-wireframes.png)
- [Tablet](./assets/wireframes/tablet-wireframes.png)
- [Mobile](./assets/wireframes/mobile-wireframes.png)

In the mobile and tablet version there is a fifth page, a full-screen navigation menu that user can access from a *burger* icon.
- [Menu Tablet](./assets/wireframes/menu-tablet.png)
- [Menu Mobile](./assets/wireframes/menu-mobile.png)

In the desktop version ther is a fixed navigation bar on top:
- [Menu Desktop](./assets/wireframes/menu-desktop.png)
## **Surface**
color palette
Typography
Images

# Technologies Used
## **Languages**
- [HTML5](https://en.wikipedia.org/wiki/HTML5)
- [CSS3](https://en.wikipedia.org/wiki/CSS)
## **Frameworks, Libraries & Programs**
- [Bootstrap 4.6:](https://getbootstrap.com/docs/4.6/getting-started/introduction/)
   - Bootstrap is a free front-end framework used for responsiveness and styling.
- [Hover.css:](https://ianlunn.github.io/Hover/)
   - Hover.css was used for the followig effect...
- [Google Fonts:](https://fonts.google.com/)
   - Google fonts were used to import...
- [Font Awesome:](https://fontawesome.com/)
   - used for providing social media icons...
- [jQuery:](https://jquery.com/)
   - jQuery came with Bootstrap to make...
- [Git:](https://git-scm.com/)
   - Version Control.
- [GitHub:](https://github.com/)
   - Save the project online.
- [GitPod:](https://gitpod.io/)
   - Online IDE used with Code Institute Template.
- [Balsamiq:](https://balsamiq.com/)
   - Design the [wireframes](#).
- [Gimp:](https://www.gimp.org/)
   - Image Manipulation Program, used to edit photos.
- [Am I Responsive?](http://ami.responsivedesign.is/)
   - Check the responsiveness of the website.
- [Coolors](https://coolors.co/)
    - Color scheme generator.
## **Other Resources**
- [YouTube](https://www.Youtube.com)
- [W3Schools](https://www.w3schools.com/) Online web tutorial
- [Stack-Overlflow](https://stackoverflow.com/)
- [CSS-Tricks](https://css-tricks.com/)

## Project Barriers and solution
FontAwesome: Non riuscivo a visualizzare le icone. Dopo diversi tentativi di cambiare CDN, cercare sul sito ufficiale o su blog
sono riuscito a trovare la risposta che cercavo su Stack Overlflow. La versione di Fontawesome che ho utilizzato e' la 4 dove compare
la classe e' "fa" invece di "fas" della versione 5 e successive.

ColorOverlay: effetto filtro su immagine di fondo. linear gradient uguale starting e ending point

NAVbar. prima costruito navbar con logo a sinistra e burger icon a destra usando flexbox space between property. Poi ho visto che non mi piaceva il logo 
preferivo lasciare solo la burger icon per il menu. Ma nel momento in cui ho tolto il logo la burger icon si e' spostata a sinistra mentre la volevo sulla
destra. Ho risolto leggendo la documentazione bootstrap sulle navbar. Cancellato il flexbox nel CSS e usato le classi bootstrap per la creazione di una 
navbar non visibile su mobile ma solo il burger icon per il menu che poi si espande nelle versioni desktop.

Navbar2: Il testo della home page continuava a comparire al disotto della navbar quando era aperta sovrapponendosi ai link.
Dopo aver provato senza successo modificando lo z-index(soluzione trovata su stackoverlow) sono riuscito a risolvere grazie
aall'aggiunta di un div element con position fixed-top. Soluzione presa da Navbar external content su Bootstrap doc