Příprava před kurzem
--------------------

Následující kroky proveď s předstihem ještě před první lekcí. V ideálním případě to zabere jen pár minut, ale je potřeba mít to připravené už před začátkem první lekce. Nenechávej to na poslední chvíli – něco se může zadrhnout a je lepší mít čas na řešení. Pokud by byl s něčím problém, napiš do Facebookové skupiny [Java 2 - webové aplikace online jaro 2021](https://www.facebook.com/groups/353725162408920). Na první lekci začneme tím, že si ověříme, že vše správně funguje.



### Účet na GitHubu

Nejprve si vytvoř účet na [GitHubu](https://github.com/) – pokud jej ještě nemáš. Při volbě uživatelského jména mysli na to, že odkaz na GitHub, ve kterém bude tvé přihlašovací jméno, budeš později nejspíš uvádět v životopisu, který budeš rozesílat firmám, až budeš shánět práci jako programátorka.

GitHub slouží jako úložiště zdrojových kódů a umožňuje spolupráci více lidí i velkých týmů na projektech. Není jediný svého druhu, ale je největší a nabízí prostor pro soukromé i veřejné projekty zdarma, takže je nejznámější. Zároveň je to tak trochu jako sociální síť, něco jako Facebook nebo možná spíš LinkedIn pro programátory. Je tedy běžné, že programátoři dávají odkaz na svůj GitHub do životopisu, aby se potenciální zaměstnavatel mohl podívat na jejich předchozí práci.

My budeme používat GitHub pro získávání zadání, na kterých budeme během lekcí pracovat, a také na odevzdávání úkolů. Využijeme jen zlomek toho, co GitHub nabízí – ale usnadní nám to práci a zároveň se naučíte základy práce s GitHubem.



### Doporučené: instalace JetBrains Toolbox

Programovat budeme v IDE [IntelliJ Idea](https://www.jetbrains.com/idea/) od [JetBrains](https://www.jetbrains.com/). Ideu si můžeš nainstalovat ručně, ale já doporučuji použít nástroj [JetBrains Toolbox App](https://www.jetbrains.com/toolbox-app/). Je to nástroj, který umožňuje snadnou instalaci všech produktů od JetBrains, jejich aktualizaci a práci s projekty.

JetBrains Toolbox App si [stáhni](https://www.jetbrains.com/toolbox-app/) (je k dispozici pro Windows, Mac i Linux) a nainstaluj. Na konci instalace zaškrtni, že se má Toolbox App rovnou spustit. Po spuštění se objeví jako ikona <img src="img/jetbrains-toolbox.svg" alt="logo JetBrains Toolbox"> v systémové oblasti (u hodin).

![Screencast instalace JetBrains Toolbox](img/toolbox.gif)



### Instalace IntelliJ Idea Ultimate

Vývojové prostředí [IntelliJ Idea](https://www.jetbrains.com/idea/) existuje ve dvou verzích. Verze *Community* je zdarma pro všechny, dá se použít pro vývoj jakékoli aplikace v Javě, ale nemá některé pokročilejší doplňky, které usnadňují vývoj třeba právě webových aplikací. Verze *Ultimate* má k dispozici spoustu dalších doplňků, normálně je placená – ale dobrá zpráva je, že JetBrains nám pro tento kurz poskytl licence zdarma. Děkujeme 🧡 Aktivaci licence provedeme na první lekci.

Pokud sis nainstalovala **JetBrains Toolbox**, stačí teď Toolbox otevřít, na záložce *Tools* najdeš *IntelliJ IDEA Ultimate* (nejspíš bude hned první) a zvolíš *Install*. Stažení a instalace trvá pár minut, stačí jen počkat, až se vše dokončí. Po dokončení instalace můžeš kliknutím na řádek *IntelliJ IDEA Ultimate* spustit.

Pokud cheš instalovat IntelliJ IDEA **ručně**, jdi na stránku pro [stažení IntelliJ IDEA](https://www.jetbrains.com/idea/download/) a stáhni si variantu **Ultimate**. Po stažení jenom spustíš instalační balík a počkáš, než se Idea nainstaluje. Na konci instalace zvol, že chceš Ideu rovnou spustit.

![Screencast ruční instalace IntelliJ Idea](img/idea-manual.gif)



### První spuštění

Při prvním spuštění se Idea bude shánět po licenci. Verzi Ultimate můžeš zkoušet třicet dní zdarma, takže pro začátek zvol … JetBrains nám pro tento kurz poskytl licence zdarma (díky 🧡), na první lekci tedy licenci zaregistrujeme. První spuštění Idey chvíli trvá, stejně jako restart po výběru, že chceš použít trial verzi – nelekni se toho, na obrazovce se nic dít nebude, ale Idea na pozadí startuje. Pokud by se ale nic nedělo déle než pět minut, je už to fakt divné 😀

![Screencast prvního spuštění IntelliJ Idea](img/idea-start.gif)



### Instalace Gitu

Pro spolupráci s GitHubem budeme potřebovat nástroj git pro verzování zdrojového kódu. Nebudeme s ním pracovat přímo, ale prostřednictvím Idey. A na začátku využijeme toho, že si ho Idea umí sama stáhnout a nainstalovat.

Na úvodní obrazovce Idey (kdy není otevřen žádný projekt) vyber na záložce *Projects* tlačítko *Get from VCS*. Idea nabídne možnost stáhnout projekt z nějakého verzovacího systému, např. z Gitu. To v tuto chvíli nechceme, ale využijeme toho, že Idea zjistí nainstalovanou verzi Gitu – a pokud Git nenajde, nabídne jeho stažení a instalaci. Počkej tedy, až vypíše *Git is not installed* a klikni na *Download and install*. Na Windows si instalátor Gitu vyžádá administrátorská oprávnění, jinak opět vše proběhned na pozadí a jen počkáš, než se na konci objeví v Idee text *Git has been installed*.

![Screencast instalace Gitu z IntelliJ Idea](img/git.gif)



### Instalace Javy

Pro vývoj v Javě budeme samozřejmě potřebovat i Javu 😀 Jedna Java je součástí IntelliJ Idea, je možné ji pro vývoj použít, ale my si radi nainstalujeme ještě svou verzi Javy, ať máme jistotu, že je to ta správná verze (konkrétně verze 11). Také ve stažení Javy nám pomůže IntelliJ Idea.

Na úvodní obrazovce Idey (kdy není otevřen žádný projekt) vyber na záložce *Projects* tlačítko *New project*. Normálně se tímto způsobem dá založit nový projekt, my to využijeme jenom pro stažení Javy (přesněji SDK). V okně *New project* ponech vlevo zvolenou variantu projektu *Java* a v pravé části rozbal nabídku *Project SDK* a vyber volbu *Download JDK*. V dialogu vyber *Version* **11** a v nabídce *Vendor* vyber **Amazon Corretto** a klikni na *Download*. Idea Javu stáhne a nainstaluje. Nyní můžeš okno *New Project* zavřít tlačítkem *Cancel*.

![Screencast instalace Amazon Corretto](img/amazon-corretto.gif)



### Volitelné: doplněk JetBrains Toolbox pro prohlížeč

Pokud máš nainstalovaný **JetBrains Toolbox**, můžeš si do prohlížeče nainstalovat rozšíření, které umožňuje jedním kliknutím otevřít projekt z GitHubu v lokální IntelliJ Idee. Rozšíření jménem **JetBrains Toolbox Extension** je dostupné v příslušných obchodech:

* [JetBrains Toolbox extension v internetovém obchodě Chrome](https://chrome.google.com/webstore/detail/jetbrains-toolbox-extensi/offnedcbhjldheanlbojaefbfbllddna) pro Chrome, Edge nebo Vivaldi

* [JetBrains Toolbox extension ve Firefox Add-ons](https://addons.mozilla.org/cs/firefox/addon/jetbrains-toolbox/)



### Volitelné: doplněk LiveReload pro prohlížeč

Při úpravách webových stránek je potřeba často stránku v prohlížeči obnovovat. Dělat to ručně každého přestane brzy bavit, naštěstí do prohlížečů existuje doplněk [LiveReload](http://livereload.com/extensions/), který stránku obnoví, když dojde k její změně:

* [LiveReload v internetovém obchodě Chrome](https://chrome.google.com/webstore/detail/livereload/jnihajbhpnppcggbcgedagnkighmdlei) pro Chrome, Edge nebo Vivaldi
* [LiveReload na Firefox Add-ons](https://addons.mozilla.org/en-US/firefox/addon/livereload/)
* [LiveReload pro Safari](http://download.livereload.com/2.1.0/LiveReload-2.1.0.safariextz)



### Aktualizace Zoom

Na on-line lekce se budeme připojovat pomocí [Zoomu](https://zoom.us/). Zoom se dá používat i z webového prohlížeče, ale doporučuji mít jej raději na počítači nainstalovaný – webová verze nemá všechny možnosti, které má desktopový klient. Klienta si stáhni zde: [Zoom Client for Meetings](https://zoom.us/download#client_4meeting). Pokud už Zoom klienta máš z dřívějška, zkontroluj si, že máš **aktuální verzi**, tedy verzi **5.6.0** (nebo vyšší). Zoom se neaktualizuje automaticky, je potřeba aktualizaci vyvolat ručně. Na ikoně Zoomu <img src="img/zoom.svg" alt="logo aplikace Zoom"> v task baru otevři kontextové menu a z něj zvol volbu *Check for Updates*. Zoom zkontroluje, zda máš poslední verzi – a pokud ne, rovnou stáhne aktualizaci a nainstaluje ji.
