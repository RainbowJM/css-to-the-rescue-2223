# Table Of Content
* [The Firework Show](https://github.com/RainbowJM/css-to-the-rescue-2223#the-firework-show)
    * [Progress](https://github.com/RainbowJM/css-to-the-rescue-2223#progress)
        * [Week 1](https://github.com/RainbowJM/css-to-the-rescue-2223/blob/main/README.md#week-1)
        * [Week 2](https://github.com/RainbowJM/css-to-the-rescue-2223/blob/main/README.md#week-2)
        * [Week 3](https://github.com/RainbowJM/css-to-the-rescue-2223/blob/main/README.md#week-3)
        * [Week 4](https://github.com/RainbowJM/css-to-the-rescue-2223/blob/main/README.md#week-4)
---
# The Firework Show

In this repository, you will be able to follow my progress is gaining more knowledge in CSS in general. At the beginning of this course, my knowledge of CSS was to only use `<div>` with `id` and `class`. But in this project you will see how I gained more knowledge about CSS, starting with CSS selectors. 

In this project, you will see how I learned to use all the different CSS selectors. All of this I have done it in an interactive firework show.

Main Goal:
Learn how to work with different CSS Selector and create a show with the knowledge that I get while learn CSS.

<img width="1352" alt="Screenshot 2023-03-08 at 10 11 46" src="https://user-images.githubusercontent.com/59873140/223681461-d73908e2-9392-4d35-a416-507b202a2c39.png">

## Progress
- [Week 1](https://github.com/RainbowJM/css-to-the-rescue-2223/blob/main/README.md#week-1)
- [Week 2](https://github.com/RainbowJM/css-to-the-rescue-2223/blob/main/README.md#week-2)
- [Week 3](https://github.com/RainbowJM/css-to-the-rescue-2223/blob/main/README.md#week-3)
- [Week 4](https://github.com/RainbowJM/css-to-the-rescue-2223/blob/main/README.md#week-4)
---
# Week 1
In the first week, we had to choose an assignment out of the 4 options.

The options were:
- 'Modulair bediennings paneel'
- 'Interactieve vuurwerkshow'
- 'Maak een 3D rubrik's kubus
- 'Tailwind zonder tailwind, met moderne CSS'

After checking all the options, I went with the *Interactive Firework Show*.

At first, I wanted to make a show with only emoji's. When I was browsering to find all the possibilities, I saw that there were so many things that you can do with CSS. That is why I decide to create a slideshow where I can show different show and technics that I have learn. 

The first thing that I did was to figure out how to make a slideshow. This is when I find out about `scroll-snap`. After I got that working, I started with the first show. In this show, I wanted to let something move. 
After the workshops and a little bit of research. I find out that you can do that by making an animation and by using `transform`.

<img width="1164" alt="Screenshot 2023-03-08 at 11 51 59" src="https://user-images.githubusercontent.com/59873140/223696449-250d4fe1-536f-4aa5-9c0b-2f9b7d1adeee.png">

What I did was that the box goes up, and then you have two others will move from the middle to the side and only a green box will be in the middle. It keep repeating itself.

 To make an animation in CSS you have to use `keyframes`. With this, you can tell the object what to do at what time.

<img width="1158" alt="Screenshot 2023-03-08 at 12 29 29" src="https://user-images.githubusercontent.com/59873140/223702272-79862b47-09e0-4da7-80ad-a081a8688abb.png">

---
# Week 2
One of the workshops I got the idea to make an animated pixel art.

For the pixel art I used `box-shadow` to create the heart shape and I used again `keyframes` to animate the colors of the heart shape.

Also, this week I tried to create e bouncing show of color. When I was making it, something  unexpected happened. Because I didn't use the correct CSS Selector, it effected the first two shows also. Check the pictures below.

<img width="1122" alt="Screenshot 2023-03-08 at 12 52 51" src="https://user-images.githubusercontent.com/59873140/223706634-44d6ad02-0308-40a1-8400-11feb8282aef.png">

<img width="1119" alt="Screenshot 2023-03-08 at 12 53 11" src="https://user-images.githubusercontent.com/59873140/223706676-c3cc3018-e0b2-420b-83d8-e304b9db2bce.png">

When I updated the CSS Selector for the bouncing show of color, I got another shape than what I was expecting. See below.

<img width="1121" alt="Screenshot 2023-03-08 at 12 58 19" src="https://user-images.githubusercontent.com/59873140/223707553-4dfcb71e-93b9-4b01-ba24-18f2a583a40a.png">

<img width="1352" alt="Screenshot 2023-02-16 at 23 48 59" src="https://user-images.githubusercontent.com/59873140/223707845-ed1225d5-997c-4779-b059-9f25d32833bd.png">

<img width="1352" alt="Screenshot 2023-02-16 at 23 49 36" src="https://user-images.githubusercontent.com/59873140/223707932-c2e19c18-8b89-4f31-a8e0-5ecb040f13de.png">

This saw because I didn't use the correct child of the `div` for this show, after a while discovered the error and fixed it.

---
# Week 3

## Wat heb ik geleerd.

Gedaan:
- motion-path
- Opstapelende geanimeerde Gradients
- interactie tovoegen


### Gradients
In de volgende vakjes van mijn vuurwerk showcase ging ik meer experimenteren met gradients. Ook heb ik de gradients geanimeerd en verschillende nieuwe dingen geleerd. Eerst heb ik een onderzoek gedaan over gradients in css om de samenstelling  van de properties beter te begrijpen en daarna in de schowcase te implementeren. Verder heb ik ook de workshop over gradients deelgenomen om meer gericht kennis krijgen. 

Hieronder zijn verschillende experimenten die ik heb geprobeerd:

#### 6 gradients
- `Linear-gradient()`
- `radial-gradient()`
- `conic-gradient()`
- `repeating-linear-gradient()`
- `repeating-radial-gradient()`
- `repeating-conic-gradient()`

Om de gradients te animeren kan ik de position en de size animeren. 

<img src="./images/gradient-v1.png">
<img src="./images/gradients-v2.png">
<img src="./images/gradient-v3.png">
<img src="./images/gradient-v5.png">



---

### Motion-path
De volgende trucje voor mijn slideshow was dat ik iets met motion path zou doen. Dit was een uitdaging meaar is wel uiteindelijk gelukt.  Ik heb eerst in illustrator de lijn getekend, en daarna in de code geplaats in een svg eleemnt. Wat ik wilde doen was de ster de path van de lijn volgen. m dat te bereiken heb ik de property `offset-path: path()` gebruikt bij de ster. Om de ster te maken heb ik de de `clip-path: polygoon()` property gebruikt. D path van de lijne heb ik in de offset-path gezet en de ster laten animeren met offset-distance. Van 0% tot 100%. Dus de ster beweegt van 
```html

   <figure class="stars"> </figure>
<svg id="Layer_2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 325.85 202.29">
      <path class="cls-1"  d="m59.22,186.26c56.79,7.03,178.43,13.28,213.4-55.31,46.12-90.47-45.28-117.08-45.28-117.08,0,0-94.27-28.97-140.4,7.69-46.12,36.66-41.83,84.43-17.74,111.76,39.62,44.94,224.65,36.26,249.46-31.34,9.05-24.66,1.72-45.73-6.19-59.22"> </path>         </svg>
               

```




```css
/* Hier volg de ster  de path van de lijn  */

section:nth-of-type(5) div figure {
    z-index: 1;
    position: absolute;
    top: 0;

    clip-path: polygon(50% 0%, 61% 35%, 98% 35%, 68% 57%, 79% 91%, 50% 70%, 21% 91%, 32% 57%, 2% 35%, 39% 35%);
    width: 10em;
    height: 10em;
    background-color: #c8ff00;

  /* De path van de lijn  */
    offset-path: path("m59.22,186.26c56.79,7.03,178.43,13.28,213.4-55.31,46.12-90.47-45.28-117.08-45.28-117.08,0,0-94.27-28.97-140.4,7.69-46.12,36.66-41.83,84.43-17.74,111.76,39.62,44.94,224.65,36.26,249.46-31.34,9.05-24.66,1.72-45.73-6.19-59.22");
    /* offset-rotate: auto; */
    animation: follow-path 4s linear alternate infinite;
}



@keyframes follow-path {
    0% {
        offset-distance: 0%;
    }

    100% {

        offset-distance: 100%;
    }
}

```
<img src="./images/gradient-v5.png">


--- 
# Meer interactie
VAls laatste heb ik meer interactie toegevoegd in mijn slideshow. Ik heb het zo gedaan dat je met de check box de animatie laten spelen en pauseren. Dit waren allemaal mogelijk met de has selector. 


--- 
# Voortgang 3

In de derde voortgang heb ik mijn voortgang besproken. Ik heb nieuwe verandering aan het groep gepresenteerd.
- nieuwe gradient trucjes
- De opstapelede box-shadows
- Motion path
- Nieuwe vorm van interactie

## Feedback van  voortgang 3

- Uitkijken voor mensen met epilepsie
- Iets laten gebeuren als het reponsive is
- De rest van de vakje vullen met experimenten.

---
## Wat heb ik geleerd en gemaakt
 - De titel geanimeerd met een gradient effect
 - De achtergond van de pagina naar een donker blauw verandert
 - Heb ik de zesde vakje gevuld met animaties
 - Ik had de color scheme gezet naar donker.


 ### Andere achtergrond
 De donkere achtergrond zorgt ervoor dat vakjes meer opvallender zijn. Hiermee kan meer focussen op de vuurwerkshow. 

<img src="./images/andere-achtergrond.png">

### Vuurwerk in de Park
Ik heb de zesde vakje gevuld met een andere animatie. Het landschap gemaakt met gradients en een picnic tapijt, dus jij (de kijker), zit je vuurwerk te kijken in de park.
<img src="./images/picnic-show.png">

#### Wat heb ik gebruikt:
- `radial-gradient()`
-  `linear-gradient()`
- `conic-gradient()`
- `box-shadows`

Bij deze link krijg je het uitgebreide code te zien:
- [Vuurwerk in de park code](https://github.com/K3A101/css-to-the-rescue-2223/wiki/animaties#vuurwerk-in-de-park)

---
## Soort van responsive
Verder heb ik de showcase responsive gemaakt door de vakjes onder elkaar te zetten bij kleinere scheremen. Het is niet niet helemaal perfect maar alle animaties zijn te zien. Maar mijn focus ligt aan de desktop versie.

<img src="./images/responsive.png">

---
# Week 4 
Dit is de laatste week voor de beeordelingsgesprek. In deze week heb ik  gefocust op de details en puntjes op de i.

## Wat ik heb gedaan
- De laatste vakje gevuld met animatie
- Een beschrijving per vuurwerkshow
- Code opschonen
- Readme Updaten met nieuwe informatie

---

### Laatste show: Vuurwerk achter de berg
De laatste vuurwerkshow is een combinatie van alle CSS technieken die ik de laatste vier weken had geleerd. Ik hebe gebruikt gemaakt van gradients, 3D transforms en box-shadows. Wat je ziet is vuurwerkshow die plaatsneem achter de bergen. 

De onderdelen:
- De landschap die bestaat uit twee linear gradients, een voor de lucht en de andere voor de grond.
- De bergen,  zijn driekhoeken gevormd door  clip-paths
- De sterrebn gemaakt met kleine witte box-shadows
- De vuurwerk zelf zijn de 3D transform animatie

![Laatste vakje](./images/vakje-7.png)

[Hier is de code]()

---

## Bronnen
- 
