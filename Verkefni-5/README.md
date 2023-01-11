# Myndvinnsla og innsetning mynda í vefsíðu

### Markmið

Nemendur geta:

* unnið myndir fyrir vef í [myndvinnsluforriti](https://www.photopea.com/)
* látið myndir af sömu stærð raðast inn eftir skjástærð 
* látið texta flæða með mynd (_float_)
* notað &lt;picture> tagið til að birta stóra mynd sem vafrinn sækir eftir skjástærð 

![Octocat](github-octocat.svg)

Taktu nokkrar myndir sem koma til greina á vefnum þínum og breyttu myndunum í myndvinnsluforriti þannig að þær virki eins og [sýnt er í sýnidæmi](https://vefgrunnur.github.io/synidaemi/verkefni-5/). 
- Um er að ræða eina stóra mynd á forsíðu sem er í fjórum mismunandi stærðum. 
- Veldu 6 myndir sem eiga allar að vera í sömu stærð og þær eiga síðan að birtast eftir skjástærð þrjár í röð, síðan tvær í röð og í einum dálki. 
- Síðan er ein mynd valin og bakgrunnur hennar tekin út og hafður gegnsær (_transparent_). 

Það þarf að breyta stærð myndanna í myndvinnsluforriti þannig að þær séu þjappaðar í réttri stærð og fljótar að hlaðast inn á vefsíðuna. 
 
1. **Stór forsíðumynd**
    * Myndin er vistuð í fjórum stærðum og vafrinn velur rétta stærð miðað breidd skjásins. 
    * Viðmið: [0 - 30em] – [30 - 48em] – [48 - 80em] – [80em +]
    * Með &lt;picture> taginu í vefsíðu er hægt að sortera myndir eftir breidd skjásins
1. **Myndaröð** 
    * 6 myndir eru vistaðar í sömu stærð  (500 x 500px) og þeim raðað mismunandi upp í vefsíðu eftir breidd skjásins
1. **Mynd með gagnsæjum (_transparent_) bakgrunni**
    * Hreinsið út bakgrunn úr mynd í myndvinnsluforriti 
    * Látið myndina inn í textadálk og látið textann flæða umhverfis myndina (css `float:left`)

* Vefmyndir geta verið þjappaðar saman í .jpg (kb) sem er langmest notað í vefsíðum. 
* Myndir í .png formati geta verið með gagnsæjan bakgrunn og ~ 25% þjöppun
* Myndir í .gif formati geta verið með gagnsæjan bakgrunn en með 0% þjöppun
* [Photopea](https://www.photopea.com/) er myndvinnsluforrit (_app_) sem keyrir í vafra.
    * Myndir skornar:  _Toolbar -> Crop Tool_
    * Myndir settar í rétta stærð: _Image -> Canvas size_.
    * Þjöppun fyrir vef  í Photopea  -> _Export -> .jpg eða .png_
    
Myndir sem settar eru á vefsíðu eiga ekki að vera breiðari en ramminn sem myndin birtist í. En nú getur stærð rammans verið mismunandi og þá er mikilvægt að **hafa eftirfarandi grunnstillingu á öllum myndum í stílsíðu** 

```CSS
    img { 
        max-width:100%;
        height: auto;
    }
```

### Námsmat 12% af heildareinkunn 

1. **Stór forsíðumynd 4%**
    * Myndin er vistuð í fjórum stærðum og vafrinn velur rétta stærð miðað breidd skjásins. 
    * Viðmið: [0 - 30em] – [30 - 48em] – [48 - 80em] – [80em +]
1. **Myndaröð – 6 myndir 4%**
    * 1 mynd: [0 - 37.5] – 2 myndir: [37.5 - 48em] – 3 myndir: [48 - 80em] – miðjusett: [80em +]
1. **Mynd með gegnsæjum bakgrunni	(_.png_) 4%**
    * myndin er sett í textadálk og textinn umvefur myndina	

### Verkefnaskil:  

Skilaðu öllum vinnugögnum sem tilheyra verkefninu í Github verkefnageymsluna, 

#### Einkunn verður birt í Innu

_Gangi þér vel._



