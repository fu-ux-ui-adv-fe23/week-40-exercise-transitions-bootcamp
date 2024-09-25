# CSS Animation Bootcamp

## Transitions

### Hover Button
Gör en knapp som på ```:hover``` gör en mjuk övergång på följande egenskaper: 

* width x height ( alt. padding )
* background-color
* box-shadow


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
Varje menyalternativ ska slidea in med en delay för maximal coolhetsfaktor.

![screen](/övningar/02_slidein_menu/screen.png)


### Pride cards

Gör en kortlek med 9 kort som vid hover av body sprider ut sig i en solfjäder.

![screen](/övningar/03_cardspread/screen.png)
