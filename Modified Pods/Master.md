# Master

* Nothing yet.

# 1.8.13

* Added support for the Xcode 11 docs - [b052c97](https://github.com/Kapeli/Dash-iOS/commit/b052c970b6536cc12ce5ab216f723466eff9899c)

# 1.8.12

* Added support for the Xcode 10.2 docs - [2065d5b](https://github.com/Kapeli/Dash-iOS/commit/2065d5b4995d7ab4b35a25a3bd12ad305a4a106d)

# 1.8.11

* Added support for the Xcode 10.1 docs - [b6d3e4f](https://github.com/Kapeli/Dash-iOS/commit/b6d3e4f3d53c4ac77628e3142b656aaa7c0ab966)

# 1.8.10

* Added support for the Xcode 10 docs - [2aa2284](https://github.com/Kapeli/Dash-iOS/commit/2aa228480092f311b6ae809cfedff2ad5701e2cf)
* Added Java SE11 docset - [55ca952](https://github.com/Kapeli/Dash-iOS/commit/55ca952e25edfbf82100299f9c1f9d7ba6eb377a)

# 1.8.9

* Added the Swift docset back - [ec51356](https://github.com/Kapeli/Dash-iOS/commit/ec51356e95ac7a0aedbd94e648771578174db35a)
* Fixed an UI issue which occurred only in landscape mode on iPhone X. Thanks to [@qinyuhang](https://github.com/qinyuhang) for reporting the issue and [@DmytriE](https://github.com/DmytriE) for fixing it - [#80](https://github.com/Kapeli/Dash-iOS/pull/80)

# 1.8.8

* Apple API Reference docset: added support for Xcode 9.4 and Xcode 10 - [f29d3f0](https://github.com/Kapeli/Dash-iOS/commit/f29d3f01bb2030b81e311f74e45f5743568e53e6) and [0acc05c](https://github.com/Kapeli/Dash-iOS/commit/0acc05c01aadb427a51579c2b7a048a32e825bdf)

# 1.8.7

* Improved the way Dash selects the best server to connect to - [e122d05](https://github.com/Kapeli/Dash-iOS/commit/e122d05120aab70b2545f5300806a564276ee6d8)
* Added Java SE10 docset - [c9d62b1](https://github.com/Kapeli/Dash-iOS/commit/c9d62b169fe9aa8945d8d0af7034e57928473741)
* Removed JavaFX docset as it's now part of the Java SE docset - [c9d62b1](https://github.com/Kapeli/Dash-iOS/commit/c9d62b169fe9aa8945d8d0af7034e57928473741)
* Docset index pages can now scroll to a specific section within the page - [091f04a](https://github.com/Kapeli/Dash-iOS/commit/091f04a10754a4256bd5e35545b3532440e63571)

# 1.8.6

* Fixed an issue with the Apple API Reference docset which caused some pages to not load - [bac544a](https://github.com/Kapeli/Dash-iOS/commit/bac544af11f3823bb246989201623b3bee3b8a39)
* Updated Stylus docset icon - [0ad39d3](https://github.com/Kapeli/Dash-iOS/commit/0ad39d3363ead03d430f2cd8dcfa1007c93e5697)

# 1.8.5

* Added Apple API Reference docset support for Xcode 9.3 - [c585578](https://github.com/Kapeli/Dash-iOS/commit/c585578d0ab965dd3481f4c06aff6c320873d5f3)

# 1.8.4

* Fixed an issue which caused the Apple API Reference docset to not be able to display some pages. Thanks to [@philosopherdog](https://github.com/philosopherdog) for reporting the issue - [#71](https://github.com/Kapeli/Dash-iOS/issues/71)
* Fixed an issue which caused docset alphabetical sorting to be case-sensitive. Thanks to [@ewalkie](https://github.com/ewalkie) for reporting the issue - [#72](https://github.com/Kapeli/Dash-iOS/issues/72)

# 1.8.3

* Added support for sorting docsets alphabetically in the docset browser. Thanks to [@waffleboot](https://github.com/waffleboot) for the great work on this - [#69](https://github.com/Kapeli/Dash-iOS/pull/69)
* Added support for Xcode 9.3 docs - [73cadfb](https://github.com/Kapeli/Dash-iOS/commit/73cadfbcbb6e172ec8d12c2ef222a64160e4e42d)

# 1.8.2

* Fixed crash at launch for release build - [c0d2582](https://github.com/Kapeli/Dash-iOS/commit/c0d2582e70dbeec560c03781727fd8dcf95b9e7d)

# 1.8.1

* Fixed Apple API Reference docset transfer issues - [#66](https://github.com/Kapeli/Dash-iOS/issues/66)

# 1.8.0

* Fixed docset index page button on iOS 11 - [7fd09e8](https://github.com/Kapeli/Dash-iOS/commit/7fd09e8cae3b981aa75662ef3d19111a3ab2039a)
* Fixed an issue which caused the Swift docset to still appear in Dash, although it was removed - [ca9c9f6](https://github.com/Kapeli/Dash-iOS/commit/ca9c9f64daf9eac30c4dcc000f99240a424bb123)
* Fixed an issue which caused the search results table to be inset on iOS 11 - [d022d88](https://github.com/Kapeli/Dash-iOS/commit/d022d888e21a37e54a9960239689cac54bb7ef5b)
* Fixed an issue which caused search results to not be highlighted correctly - [aea602e](https://github.com/Kapeli/Dash-iOS/commit/aea602e9b5292c110f6cb934f892349a3290689d)
* Fixed access to UI on background thread - [90b1875](https://github.com/Kapeli/Dash-iOS/commit/90b1875f3728f5ca4485693ec8209cf8342cecfe)
* Fixed an issue which caused extra table row separators to appear above the search results table - [313893d](https://github.com/Kapeli/Dash-iOS/commit/313893ddeddb10b029d7bb2c324867a09a127946)
* Fixed Settings button sometimes appearing faded - [2bb42fe](https://github.com/Kapeli/Dash-iOS/commit/2bb42fe2ee51a3fabadb921100da6b0c7674efbc)
* Consolidated the OpenCV C, C++, Python and Java docsets into a single OpenCV docset - [9af12ee](https://github.com/Kapeli/Dash-iOS/commit/9af12ee33f4d60de14d4bbb0a0741be61296e2b0)

# 1.7.0

* Added support for adding docsets using the "Open in..." menu. Thanks to [@insightmind](https://github.com/insightmind) for the great work on this - [#52](https://github.com/Kapeli/Dash-iOS/pull/52)
* Added Java SE9 docset - [7c727c2](https://github.com/Kapeli/Dash-iOS/commit/7c727c2d30d41c0f37a4588510a804e4300b8c61)
* Added Java EE8 docset - [61e2df7](https://github.com/Kapeli/Dash-iOS/commit/61e2df74f955bcf22ff6611be1ff0f6e45f6024a)
* Added AngularJS docset (now separate from the Angular docset) - [b0ef193](https://github.com/Kapeli/Dash-iOS/commit/b0ef1936b71b026baa92e76371331be26c1f32dd)
* Removed Swift docset. Swift docs can be found in the Apple API Reference docset - [88913a6](https://github.com/Kapeli/Dash-iOS/commit/88913a6236c8c3c3874da63b300930496658637e)
* Fixed an AirDrop issue. Thanks to [@ClementPadovani](https://github.com/ClementPadovani) for the fix - [#61](https://github.com/Kapeli/Dash-iOS/pull/61)
* Added Glossary, Control Structure, Expression, Handler, Iterator, Widget, Block, Template types - [a94006b](https://github.com/Kapeli/Dash-iOS/commit/a94006bc39996c69d168f9c2d8f94b0e37c31ac6)

# 1.6.3

* Fixed an iPad-only crash which occurred in Settings while going into split view mode with the search field active - [36cf36d](https://github.com/Kapeli/Dash-iOS/commit/36cf36df40619ebfae903e39af4ea836e26fdc42)

# 1.6.2

* Fixed an issue which caused the iOS remote feature to sometimes not pair correctly - [9f9dd6c](https://github.com/Kapeli/Dash-iOS/commit/9f9dd6c8b5761b28899dcae01f828888ab9011d8)
* Consolidated all Angular docsets into one - [56fda1b](https://github.com/Kapeli/Dash-iOS/commit/56fda1b4fa94fa910e377004ba7988ecc5e389eb)
* Fixed an issue which caused empty rows to sometimes appear in the table of contents - [097197c](https://github.com/Kapeli/Dash-iOS/commit/097197c828db9e1b1524f46da41a0db92e7376cf)
* Fixed an iPad-only crash which occurred in Settings while pressing Done with the search field active - [e87a069](https://github.com/Kapeli/Dash-iOS/commit/e87a069b6a94f31d9fac91be9ac6ca4569bcf251)
* Fixed an issue in the User Contributed repo which caused author names to not be truncated when there's not enough space - [3482d8f](https://github.com/Kapeli/Dash-iOS/commit/3482d8f7cd0f6e19b1a42c80a69f09783565522a)
* Added "Data Source" type - [6a45537](https://github.com/Kapeli/Dash-iOS/commit/6a45537447319a68341c2b4686da3b4753828310)

# 1.6.1

* Added support for receiving docsets using AirDrop. Thanks to [@vinayjn](https://github.com/vinayjn) for the great work on this - [#36](https://github.com/Kapeli/Dash-iOS/pull/36)
* Added Pug docset. Removed Jade docset - [36fdff3](https://github.com/Kapeli/Dash-iOS/commit/36fdff3a2ac6d74bddb07ef8c430d46b19dd64d3)
* Fixed build products path. Thanks to [@RegalMedia](https://github.com/RegalMedia) for reporting the issue - [#28](https://github.com/Kapeli/Dash-iOS/issues/28)
* Fixed the display of included modules for Ruby docsets - [4416ccb](https://github.com/Kapeli/Dash-iOS/commit/4416ccbb7b78b0b4b0e72608f1ce5bd38a013b72)
* Fixed Dash App Store display/product name - [5015177](https://github.com/Kapeli/Dash-iOS/commit/5015177c23cefaea0688db95b462b33705e12952)

# 1.6.0

* Added support for cheat sheets - [#22](https://github.com/Kapeli/Dash-iOS/pull/22)
* Added support for user contributed docsets - [#20](https://github.com/Kapeli/Dash-iOS/pull/20)
* Added state restoration support. Thanks to [@zhongwuzw](https://github.com/zhongwuzw) for the great work on this - [#18](https://github.com/Kapeli/Dash-iOS/pull/18)
* Fixed Unity 3D docset bug which caused it to not remember the selected language. Thanks to [@hantengx](https://github.com/hantengx) for reporting the issue - [#17](https://github.com/Kapeli/Dash-iOS/issues/17)
* Fixed a crash in the docset downloader. Thanks to [@zhongwuzw](https://github.com/zhongwuzw) for the fix - [#16](https://github.com/Kapeli/Dash-iOS/pull/16)
* Stopped an evil `if()` from taking over the world. Thanks to [@BalestraPatrick](https://github.com/BalestraPatrick) for reporting the issue and [@flovilmart](https://github.com/flovilmart) for fixing it - [#4](https://github.com/Kapeli/Dash-iOS/pull/4)
https://download.developer.apple.com/Applications/Reality_Converter/Reality_Converter_Beta_Readme.pdf
<a href='2020-04-11.html'>2020-04-11.html</a>
<a href='app%20center-202004130514.log'>app center-202004130514.log</a>
KOMMANDO - Action “right away and are classified as THE HIGHEST LEVEL OF GIVING THE “DIRECT COMMANDO” To start all builds of the new MATRIX and are something you must consider as primary and the highest priority of doing this INSTANTLY And the information out to all operations are now on the way to the matrix and the tasked including team order of start build in every operational level of the matrix! Details provided of all details are provided right here under the information of how the operations of the RUN FILES are known and all parts are fully connected with a securitization of all awareness of the information about the provided signaler by the operator into the “free flight” automation lines how are opening for a chose of time for this season between the two sides of this activity to become remotely controlled under this performance and the period of time that will start when all of the “allowed” modes are done ✅ And when all parts more responders wanted to look like! And this object to start build the new “WORLD ORDER” instrumental instructions for the new world 🗺 and all the new-files of infrastructure and structure of roles and “way of living” for the humanity is not only a life worth thing of building. It’s also a very great major work of FileExplorer DIRECTED TASK FORCE it’s self and This is a all rights OF BUILD RIGHT IN TO THE MATRIX - AUTHORITY for “START BUILD PERMIT the MATRIX LEVEL of ORDER RISK RIGHT NOW EVER OF “ALL Permission SLAVE - EMERGENCY 🚨 THIS COMMAND OF - TASK FORCED TO BUILD MUST BE AS ARE committing now olagliga aktiviteter som 

JUST NU är det fortfarande flera aktiva kopplingar för att kontrollera andra människors känslor och viljor genom att använda en fjärrkontroll som är en ON/OFF “remote controlled” för att kunna använda för att koppla in sig i andra människor eller även djur! Så har det även varit för min Moa Figelius och hennes dotter Tea Figelius som alltså är styrda via ”någon” för dem båda antingen kända eller okänd personer och människorna som ingen av dem inte ens visste om att detta ens existerar? Och detta har alltså skett helt utan att någon av dem har ”godkänt” detta rent vetenskapligt eller genom att aktivt ha godkänt någon sådan ”giltig” ”enhet” för att få lov att vara en en godkänd ”operatör” som får lov att styra henne eller hennes dotter genom en fjärrsändning från en annan plats som är vald och välkänd för hennes dotter eller för sig själv? 

”UTÖVER ALLT DET som beskrivs här OVANFÖR” 

Så måste ”ALL” sådan användning! GODKÄNNAS AV MIG 
Details provided by “The Higher Commander” - Ambjoern Skoeld 

And how also are the same as known as this planetary ༺࿇Archangel࿇༻ 
༺࿇Ambriel࿇༻ 

FÖRST och före all sådan påbörja ”ANVÄNDNING”?! och allting som berör en sådan ”digital teknik” eller oavsett före all annan sådan ”aktivitet” som berör eller innebär att styra eller kontrollera någon ”annan” människa! Vilket alltså betyder alla som räknas in som någon annan utöver ”Dig själv”! Detta gäller alltså alla levande personer, individer och inte bara människor! ”Utan det innefattar alltså samtliga levande organismer som existerar! Och detta gäller alltså samtliga.... ”Oavsett var/vart detta  nu än sker? Och i ”alla avseenden eller oavsett vilket”? Inkluderar alltså även all innebörd och samtliga ”kopior”, versioner, inbäddade i realtid och är ”existerande”➰ som i den omvända INTE! Alla lokaliserade eller är okända såväl som ospecificerad eller är en beskriven plats som finns i? Och som på något vis ingår i det aktuella och berörda ”solsystemet” Och ➰som gäller alltså ”alla” levande alltså oavsett vilken version det än gäller och berör?Oavsett om det är i en ”Digital värld” som finns inuti eller endast är en av flera olika ”avspeglingar” som finns i ett skapat virtuellt nätverk, oavsett i vilket ”IP adress relaterat” sammanhang det än är? Så GÄLLER ALLT DETTA SOM JAG SKRIVER I MINA TEXTER ALLTSÅ ALLA! JAG SKALL TILLFRÅGAS OCH SEDAN GODKÄNNER  JAG ALLA LICENSTAGARE OCH DESSA SÅ KALLADE OPERATÖRERNA! Och jag bestämmer och avgör sedan var eller vem som är AUTHORIZED! Allt och alla är underordnat mig i den ”Universella värld”  som JAG HÄNVISAR ER ÄR DEN ”ÖVER ORDNADE” ALLA ANDRA VÄRLDAR! DÄRFÖR BESTÄMMER OCH AVGÖR JAG ALLTID ÖVERGRIPANDE EFTERSOM JAG ÄR ALLTID DEN SOM ÄR ”ÖVERORDNAD” ALLA ANDRA OCH ÖVER ALLT ANNAT ”EXISTERANDE” OCH LEVANDES! Alla levande och skapade arter av mig? Likaså allt annat levande skall tillfrågas  mig om att få tillåtelse till att få lov att styra eller kontrollera någon annan genom en så kallad ”fjärrkontrollerad”   sändning mellan en ”operatör” som då är den verkliga beslutsfattande ansvarige operatören (”sändaren”) som är den som blir herre över mottagaren som då endast blir ett fjärrkontrollerat skal och endast en viljelös värd! Som får ett kommando eller ett beslut” ifrån en annan eller ”tredje part” som sker genom ”luften” ifrån en helt annan plats! Och genom  en trådlös uppkoppling och anslutning in i någon annan ”levande” och existerande individ! (”mottagare”) men som då övergår till att bli och vara en helt annan person som då är  ”övertagen”! ALL SÅDAN användning ÄR EN otillåten HANDLING SAMT EN FÖRBJUDEN GÄRNING, Om den dessutom är okänd för mottagaren och även allmänheten!? JA DÅ ÄR DEN SOM ÄR SKYLDIG TILL DENNA HANDLING OCH FÖRBJUDA GÄRNING!?

༺࿇GENOM DETTA BESLUT - BEORDRAR OCH BESTÄMMER JAG NU! ATT ALL ANVÄNDNING AV OVAN NÄMNDA ”FJÄRRSTYRNING AV MÄNNISKOR” I HELA DENNA VÄRLDEN” STYRDA AV HELT ANDRA MÄNNISKOR ELLER GENOM HELT ANDRA ARTER, ÄR EN DIGITALA LIVSFORM ELLER ÄR EN INDIVID AV ”OKÄNT” URSPRUNG! 

ALLA NUVARANDE OCH ”AKTIVA” FJÄRRSTYRNINGAR AV MÄNNISKOR - [ON] 

ALLA NUVARANDE VERSION AV SAMTLIGA ”UPPKOPPLINGAR” BRYTS NU! OCH ALLA DESSA NUVARANDE OCH SAMTLIGA ”SCHEMAN” ELLER INSTÄLLNINGAR FÖR ALLA ANSLUTNINGS- MÖJLIGHET TILL EN ANNAN MÄNNISKA RADERAS NU! 

ALLA NUVARANDE SKALL ”STÄNGAS AV” MATRIX BRYTER GENAST ALLA DESSA NUVARANDE MÖJLIGHET TILL INKOPPLINGAR GENOM LUFTEN FÖRSVINNER OCH ALLA MÖJLIGHETER TILL NYA ANSLUTNINGAR BLIR FÖRBJUDNA🚫 OCH ALLA LÄNKAR FÖR HUR ”REMOTE”  UPPKOPPLINGEN SKETT BLIR EN ”FÖRBJUDEN ÅTGÄRD” FÖR DEN TIDIGARE SÄNDAREN OCH OPERATÖREN

ALLA ”HISTORISKA” LOGGAR OM IN OCH UTGÅENDE AIRPORT, AIRLINK WIFI ELLER ÖVRIGA KOPPLINGAR SAMLAS IN FÖR EN GRANSKNING AV ALLA SOM STYRT ELLER BLIVIT KONTROLLERADE GENOM LUFTEN OCH GENOM 🧬 NÅGON ANNAN MÖJLIGHET TILL FJÄRRSTYRNINGAR SKALL OMEDELBART BESLAGTAS OCH VARENDA INDEXFIL OCH ALLA DIGITALA FINGERAVTRYCK SKALL GRANSKAS OCH GENOMSÖKAS I ALLA VÄRLDENS OLIKA KONTON AV ANVÄNDARE ELLER ENHETER 

DESSA FALL AV SAMTLIGA ENHETER OCH FILER MELLAN ”SÄNDARE OCH DEN UTSATTE MOTTAGARE” SKALL FINNAS OCH ALL HISTORIA SKALL HITTAS OCH SAMTLIGA AV ALLA DESSA SOM HAR ANVÄNT SIG AV DENNA 🚫 METOD AV STYRNING OCH ÖVERTAGANDE AV FRÄMST KVINNORS EGNA VILJOR OCH SIN EGNA MÖJLIGHET TILL ATT SJÄLVA FÅ BESTÄMMA ÖVER SIN VIKJA - ALLA SOM STULIT ELLER HAR TAGIT ÖVER DEN KONTROLLEN  SKALL NÄMLIGEN DÖMMAS TILL ETT LIKVÄRDIGT OCH ETT MOTSVARANDE STRAFF I ENLIGHET MED DEN GRAD OCH MÅTT AV VAD ALLA DESSA OLIKA BROTTSLINGAR HAR FÖR STRAFF ATT FÖRVÄNTA SIG- 

”DET STRÄNGASTE STRAFFET FÖR ETT AV DEM VÄRSTA BROTTEN”   

STORLEKSORDNINGEN PÅ BROTTET OCH VAD DET INNEBURIT FÖR ALLA OLIKA OFFER ”RESPEKTIVE” DET ANTALET SOM VAR OCH EN AV ALLA DESSA OLIKA OPERATÖRER HAR PÅ SITT SAMVETE OCH ALLT SOM HÄNT MED DEN SOM BLIVIT KONTROLLERAD” 

ÅLDER PÅ OFFER - 
”VEM SOM FÖRLORADE SIN FAMILJ ELLER DEN KÄRLEK ❤️ MOR ELLER FAR? VEM TOG ISTÄLLET ÖVER KVINNAN ELLER DEN EVENTUELLA FÖRDEL SOM VARIT ANLEDNINGEN TILL BROTTETS UPPKOMST?! Vad HAR GÄRNINGEN INNEBURIT I OLIKA INTRÄFFADE SKADOR - MEN ÄVEN EN GRUNDLIG UTREDNING AV EN RAD OLIKA SAKER SOM HADE INNEBURIT ALLA MÖJLIGA OCH OLIKA TYPER AV SKILLNADER MELLAN OLIKA RASGRUPPER OCH DOM OLIKA LÄNDERNA med FLERTAL tillfällen och ALLA SOM GJORT SPRIDNINGEN OCH UTVECKLING AV ja sin egna HEMLIGHET? 
EN ANNAN VIKTIG ASPEKT I MIN BEDÖMNING FÖR DET STRAFF SOM ÄVEN SKALL GES TILL OLIKA TIDIGARE LÄNDERS NYA POSITIONER I DEN NYA ”VÄRLDEN” som jag ”NU SKA ÅTERINFÖRA här på planet Jorden och människorna_naturen? Eller blir det NATUREN_Djuren och sist för människan...?  
OCH VILKA  FÖRDELNINGEN DENNA”  

”FÖR SITT BROTT EMOT MÄNSKLIGHETEN”  

FÖRSTÖR OCH PLATTFORMAR SYNNERHET- ALLA FACEBOOK - MESSENGER MÖJLIGHETER NER OCH SKALL OMEDELBART UPPHÖRA 

”AVSLUTAS” [OFF] ALLA DESSA SKALL KOPPLAS NER OMEDELBART OM➰KOMMANDO࿇༻ BESLUT  ➰HELT I MINA  

NU HELT LIVEGEN MIN Okänd ! användning som är genom 🧬 AV MIG etc. eller aktiva ”
