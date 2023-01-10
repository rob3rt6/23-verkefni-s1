
# Sveigjanleg hönnun vefs  (_Responsive Web Design_)
 
### Markmið:

Nemendur öðlast skilning á:

* hönnun svegjanlegs viðmóts (_Respnsive Web_)
* Hvernig hægt er að vinna með _Grid_ og _Flexbox_
* hvernig hægt er að setja bakgrunnsliti í vefsíðu


Skipulag vefsíðu með 2 dálkum eða fleiri gengur ekki upp í litlum farsímaskjáum. Til að hafa áhrif á skipulag HTML síðu setjum við inn viðmið (_breakpoints_) í CSS stílsíðuna.  

Við notum **_@media screen_** skipunina til að birta mismunandi skipulag eftir skjástærðum.  

## Sveigjanlegt dálkaskipulag (_Column grid_)

Við búum til vefsíðu sem inniheldur dálka. Við gerum dálkana sveigjanlega, dæmi:

```HTML
    <div class="col-2">
        <section>Lorem ipsum</section>
        <section>dolor sit amet</section>
    </div>
    <div class="col-3">
        <section>Lorem ipsum dolor </section>
        <section>sit amet consectetur</section>
        <section>adipisicing elit</section>
    </div>
    <div class="col-4">
        <section>Lorem ipsum dolor </section>
        <section>sit amet consectetur</section>
        <section>adipisicing elit</section>
        <section>Tempore, illum reiciendis</section>
    </div>
    <!-- Þegar "Lorem ipsum er skrifað í VSC þá býður ritstuðningur forritsins upp á heila málsgrein af "dummy" texta sem hentar vel í þetta vefdæmi -->

```

Við byrjum á að stíla dálkana eins og þeir eiga að birtast í litlum farsímaskjáum og síðan breytum fjölda dálka með css stílum eftir því sem skjáirnir stækka. Þessi aðferð er nefnd „_Mobile up_“ hönnun. 
Dæmi:

```CSS
    /* 0 - 37.5em */
    .col-2, .col-3, .col-4 {
        display: grid;
        grid-template-columns: 1fr;
    }
    @media screen and (min-width:37.5em){ 
        .col-2, .col-4  {
            /*dálkar sem er breytt miðað við 600px skjábreidd;*/
        } 
    }
    @media screen and (min-width:48em){ 
        .col-3, .col-4  {
            /*dálkar sem er breytt miðað við 760px skjábreidd;*/
        } 
    }

```

Bættu inn viðmiðum (_@media breakpoints_) í stílsíðuna þína til að fá fram eftirfarandi eiginleika í vefsíðuna.

* Viðmið: 0 – 37.5em, allir dálkar með 100% breidd (1fr)
* Viðmið: 37.5em – 48em, 2 og 4 dálkar með 50% breidd (1fr 1fr)
* Viðmið: 48em – 60em, 
    * 3 dálkar (repeat (3,1fr))
    * 4 dálkar (repeat (4,1fr))
* Viðmið: 60em + Efni vefsíðunnar er miðjusett (_max-width_) í vafranum 


Nú er komið að gera vefinn þinn sveigjanlegan. HTML tög eiga að hafa skiljanlega merkingu í uppsetningunni,  helstu tögin eru ` <header> <nav> <main> <section> <article> <aside> og <footer>`, [sjá öll tögin hér](https://www.w3schools.com/html/html5_semantic_elements.asp).  

Notaðu CSS Grid til að hanna eigið dálkaskipulag. Vefsíður þurfa að birtast í öllum helstu skjástærðum, búðu til viðmið (_breakpoint @media …_) til að stjórna skipulagi vefsíðunnar. 

#### Í efnisyfilirliti **&lt;nav>** þarf að nota `display:flexbox` vegna þess að fjöldi tengla getur breyst.

* 0 – 37.5em (allt efni í einum dálki) 
* 37.5em (td. article ofaná hliðardálkum)
* 48em (Efnisyfirlit, _nav_ og _footer_ er lárétt)
* 60em (_article_ og hliðardálkar í sömu röð)
* 80em (_max-width_ og efni vefsíðunnar er miðjusett í vafranum)
* [Sýnidæmi]()

### Námsmat 20% 

* **2% Dálkaskipulag.** Vefsíða með 2, 3 og 4 dálkum  
    * 0 – 37.5em (Allir dálkar skiptast í 1fr)
    * 37.5em (2, 4 dálkar skiptast í 1fr 1fr)
    * 48em (Allir dálkar skiptast rétt, 2, 3 og 4 dálkar)
* **8% Vefsíða með viðmiðum**
    * 0 til 37.5em (_grunnstillingar - base_)
    * 37.5em - 48em - 60em -80em 
    * Efni miðjusett í stærri skjáum 80em + (_max-width_)
*  **4% Efnisyfirlit og bakgrunnslitir**
    * Efnisyfirlit (nav) `display:flexbox;`
    * Mismunandi bakgrunnslitir í `header, main og footer`
* **6% Lykilmatsþáttur**
    * Umsjón og verklag í lagi (_git, vsc og github_) 
    * Unnið eftir undisbúningsgögnum
    * Skipulag og kóðun í lagi

### Verkefnaskil:  

Skilaðu öllum vinnugögnum sem tilheyra verkefninu í Github verkefnageymsluna.

#### Einkunn verður birt í Innu

_Gangi þér vel_
