# Verkefni 1. Undirbúningur 

### Markmið:
- Nemendur stofna vefumsjónarkerfi með Visual Studio Code og Github. 
- Nemendur finna umfjöllunarefni sem notað verður í verkefnavinnunni

### Námsmat 12%

- Innsetning forrita 2%
- Nýskráning Github reiknings 2%
- Vinnulag og verkefnaskil 2%
- Uppsetning vefsíðu 2%
- Efnisval og gagnasöfnun 4%
---

### Innsetning forrita

1. Byrjum á að hlaða inn [Visual Studio Code](https://code.visualstudio.com/) og setjum það inn (_install_) í tölvuna okkar
1. Í Windows PC hlöðum við inn skipanalínuforritinu [GIT BASH](https://git-scm.com/) og setjum það í tölvuna, munið að velja [_Visual Studio Code as default editor_](https://vefgrunnur.github.io/verkefnaskil/git_innsetning.html)
1. GIT er til í Linux og Macintosh tölvum og við notum skipanalínuforritið "_Terminal_" til að framkvæma GIT skipanir

---

### Nýskráning Github reiknings

- Nemendur verða að vera með Github reikning (_Github user account_)
- Til að stofna Github reikning verður þú að vera með tölvupóstfang (_E-mail account_). Þú getur notað skólapóstfang sem þér er úthlutað við innskráningu í Tækniskólann. [Hér eru leiðbeiningar á vef Tækniskólans um hvernig nemendur fá skólapóstfang](https://tskoli.is/nethjalp/um-skolanetfang/). Með því að nota skólapóstfangið getur þú fengið [Github Student Developer Pack](Namsefni-1/GithubStudentDeveloperPack.md) sem getur nýst þér vel í námi á tölvubraut.

1. Við skráningu Github reiknings verður að koma **skýrt fram hver er eigandinn**. Námsaðstoð fer í gegnum Github verkefnageymslu (_repository_) og þá er mikilvægt að kennari geti séð hver er eigandi reiknings. Kennari getur hafnað reikningi ef það er ekki gert.
    * Í **Stillingar (_Settings_)** er skráð fullt nafn.
1. Eftir nýskráningu færðu tölvupóst frá Github þar sem beðið er um staðfestingu (_confirm your email account_) á að þú sért að stofna reikninginn. 
1. Bættu við tölvupóstfanginu í **Profile -> Settings -> Emails** í Github reikningi þínum 

---

### Vinnulag og verkefnaskil

1. Til að Git geti tengst við Github þá verður að skrá Github notandanafnið þitt og tölvupóstfang í GIT BASH (_terminal_) [$ git config --global](https://vefgrunnur.github.io/verkefnaskil/git_innsetning.html) 
1. Þú stofnar verkefnageymslu (_Repository_) á Github reikningnum þínum. Geymslan á að vera lokuð **_"Privat"_**. Engin nema þú og kennarinn eiga að hafa aðgang að geymslunni
1. Til að kennari geti haft aðgang að verkefnageymslunni þarf að opna aðgang fyrir hann
   * Farðu í _Settings_ og þar velur þú _Collaborators and teams_ 
   * Veldu _Add peoble_ og skráðu notandanafn kennara (t.d. GJG) og síðan veluru _"Add this member to this repository"_
1. Það er hægt að vinna verkefni beint í Github geymslunni en það er ekki skynsamlegt.  Best er að afrita verkefnageymsluna yfir á þína tölvu, vinna verkefnin og skila síðan jafnóðum.  [Náðu í geymsluna yfir í þína tölvu](https://vefgrunnur.github.io/verkefnaskil/git_verklag.html)
1. Opnaðu Visual Studio Code, veldu **"File -> "Open folder"** og vísaðu VSC á Verkefnageymsluna þína 
1. Núna ertu tilbúinn að vinna í verkefnum áfangans.
1. Í Innu, verkefni 1 skilar þú nafni reikningsins (_Github username_)


```

Github.com/notendanafnið þitt
   |___ .gitignore
   |___ README.md
   |___ vef1vg (verkefnageymsla - repository)

       
Staðvært umhverfi (local environment) = tölvan þín.
   |___	vef1vg (verkefnageymsla - repository clone)
   
```
---

## Uppsetning vefsíðu á (notandi).github.io  

Github býður viðskiptavinum sínum að búa til vef sem tengist reikningi þeirra. Eina sem þarf að gera er að virkja veftenginguna í Github notendastillingum (Settings). 

dæmi:  
1.	Gitub reikningur: **Notandi** 
1.	heiti geymslu: **notandi**.github.io
1.	Í valslá ferðu í **Settings)** og velur **Pages**
1. Síðan velur þú "Branch": **Main**. Github býr til tengingu á milli geymslunnar og vefsvæðis þins á github.io 
1.	Nú getur þú birt verkefnin á eigin vefsíðu.
1.	Skilaðu tengli (_link_) í Innu sem vísar á vefsíðuna þína

---

## Efnisval og gagnasöfnun

Nemendur finna texta, ljósmyndir, tónlist og video sem þarf að vinna og skila eftir verkefnalýsingum áfangans. Nemendur bæta og breyta efni vefsins eftir því sem þurfa þykir út alla spönnina.

### Þema: Tónlist

- Tónslistarstefna þar sem fjallað um þróun tónlistar eftir tímabilum og listamönnum sem hafa mótað hana
- Umfjöllun um hljómsveit eða einstakan listamann, ferilskrá, frægð og hversvegna lögin þeirra urðu vinsæl
- Tilgreindu hvaða efni þú ætlar að vinna með í áfanganum í README skránni sem þú skilar í github.io 
   
   #### Engin á að fjalla um sama efni. 

<!--
Github vefsíður eru "Static" og bjóða ekki upp á neina gagnvirkni við notendur en það er hægt að kalla fram gagnvirka vefsíðu í &lt;iframe> glugga í Github vef, sjá  [dæmi um póstform hér](https://dev.to/charalambosioannou/create-a-static-webpage-with-a-contact-form-on-github-pages-3532)
-->
