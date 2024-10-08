![screen](poster.png)

# CSS Animation Bootcamp

## Transitions Bootcamp

### Hover Button
Gör en knapp som på ```:hover``` gör en mjuk övergång på följande egenskaper: 

* width x height ( alt. padding eller scale )
* background-color
* box-shadow

Lägg gärna till fler saker som ändras för att testa vad som fungerar med transitions.

--------

### Slide in menu

Gör en meny som slide:ar in från valfri sida.

För att trigga animeringen togglar du CSS-classen ```.open``` på en ```<nav>``` genom att lägga in detta script längst ner i bodyn.

```html
<script>
    document.querySelector('nav')
    .addEventListener('click', (e) => {
        e.target.classList.toggle('open')
    })
</script>
```

#### Levelup
Varje enskilt menyalternativ ska slidea in med en individuell delay för maximal coolhetsfaktor.

![screen](/övningar/02_slidein_menu/screen.png)

--------

### Pride cards

Gör en kortlek med 9 kort som vid hover av section sprider ut sig i en solfjäder.

![screen](/övningar/03_cardspread/screen.png)

---------

### Freestyla själv

Skapa lite egna transitions som aktiveras antingen av hover, eller med hjälp av att lägga till en klass med JavaScript. Få saker att flytta på sig, rotera, experimentera lite med Cubic-Bezier eller utforska transform-origin. Kanske vill du skapa din egen hamburgermeny? Det är upp till dig själv!
