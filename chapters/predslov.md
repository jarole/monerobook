# Predslov

## Písanie knihy Mastering Monero

Som Nico (“SerHack”), taliansky výskumník, Monero prispievateľ a vydavateľ tejto knihy. Nájsť dobrý zdroj a naučiť sa niečo o kryptomenách, môže byť neľahká úloha. Pre nových užívateľov to je doslova výzva, dostať sa cez napísanú dokumentáciu na zrozumiteľnú technickú úroveň. Keď som začínal študovať Monero, strávil som veľa času hľadaním a vyhodnocovaním informácií k tejto téme, často pochádzajúcich z rôznych zdrojov.

Monero komunita sa rozhodla napísať knihu Mastering Monero aby vás previedla touto cestou, a je jedno či si nastavujete svoju prvú peňaženku, alebo sa len chcete pozrieť technickým detailom hlbšie “pod kapotu”. Prvé kapitoly sú písané pre každého, koho zaujíma prečo a ako používať Monero. Popri návodoch pre praktické použitie, obsahujú ľahko zrozumiteľné vysvetlenia a príklady. Ďalšie kapitoly prechádzajú do pokročilejších tém, informácií pre vývojárov, ktorí by chceli tvoriť a prispievať do projektu Monero.

Moje dobrodružstvo do sveta kryptomien začalo, keď som sa narazil na Bitcoin v januári 2016.

Od začiatku som bol znepokojený nad dôsledkami jeho transparentného úložiska  verejnej knihy (ledger). Od tej doby Bitcoin a mnoho iných kryptomien je postavených na otvorených a prepojiteľných adresách a coiny s priehľadnou históriou a transakciami často odhaľujú detaily ako finančné toky užívateľov. Každý zostatok na adrese je verejná informácia, ktorá hocikomu umožňuje vyhľadať a sledovať váš príjem, platby a množstvo vašich kryptomien. To môže viesť k nežiaducim dôsledkom, ako je aj manipulácia ceny na základe  zostatku v peňaženkách.

Myslel som si, že Bitcoin je jediná kryptomena, až kým mi priateľ nepredstavil Monero v Máji 2017. Strhla ma jeho nová paradigma: svet, kde nechránené detaily ako stav účtu a transakcie sú uchovávané v utajení, kvôli ochrane oboch strán - odosielateľa aj príjemcu. Ochrana súkromia je predvolená a vždy vyžadovaná. Celý Monero blockchain je zahalený a užívatelia nemajú možnosť ani neúmyselne poslať transakciu, ktorá by niečo odhalila.

Rozoznávajúc dôležitosť tohto projektu, začal som hľadať možnosti, ako prispieť komunite. Rýchlo som zbadal príležitosť podporiť masovú adopciu vytvorením platobných brán pre online biznis, a tak som sa zapojil do projektu Monero Integrations. Tento open-source kód je navrhnutý v tom istom duchu ako Monero - a to je ochrana súkromia. Žiadne prihlasovanie ani služby tretích strán, keďže prostriedky sú smerované rovno do príjemcovej peňaženky. Monero komunita vyjadrilla podporu tomuto úsiliu, a celý podnik bol vlastne financovaný z dobrovoľných príspevkov cez Monero Forum Funding System (FFS).

Kým som pracoval na projekte Monero Integrations, zistil som že absencia obsiahlejšieho knižného sprievodcu Monerom je prekážkou pre užívateľov ako aj prispievateľov. Potreba detailnej príručky ma inšpirovala k napísaniu tejto knihy, ako univerzálneho zdroja pre našu globálnu komunitu. Som vďačný za štedré dary a podporu FFS, ktoré to celé umožnili vydať ako bezplatnú eBook (a hmotnú knihu!) pre širšiu verejnosť. Či budete čítať  Mastering Monero rad radom, alebo skákať na témy, ktoré vás zaujímajú, dúfam, že si to čítanie užijete a dozviete sa niečo o Monero a jeho vzrušujúcich projektoch v rámci komunity.


## Usporiadanie knihy
Kniha je zostavená v línii, aby pokryla závislosti a náväznosti medzi jednotlivými témami.

Prvá kapitola ukazuje ako blockchain rieši niektoré problémy s ktorými zápasí štandardný ekonomickým model a bankový systém obzvlášť. Avšak, blockchain nie je úplné riešenie pre naše potreby. jeden problém tu pretrváva: Zabezpečiť súkromie pre online transakcie. S Monero, zisťujeme čo súkromie je a prečo sa o neho starať. To bude nápomocné pre nováčikov a užitočné pre užívateľov, ktorí niekedy zabúdajú na Monero princípy.

Druhá kapitola začne objavovaním “praktických” Monero aplikácií: zoznámime sa s rôznymi typmi existujúcich peňaženiek, naučíme sa ako si ju vytvoriť s Monero GUI a nakoniec zistíme ako získať svoje prvé Monero.

V tretej časti preskúmame ako Monero v súčasnosti funguje. Tu budeme odhaľovať ako Monero tím vyvinul kryptomenu, ktorá predvolene skrýva transakcie pred tretími stranami.

Štvrtá kapitola je pre všetkých, ktorí by chceli pomáhať komunite, prekladať, vyvíjať a vylepšovať Monero po každej stránke. Nemajte obavy o to ako môžeme pomôcť, dôležité je to robiť! Pripojíme sa k Monero komunite.

Piata kapitola je prehľad horúcej témy - proces ťažby, ktorý potvrdzuje transakcie ostatných užívateľov. Uvidíme čo to je a prečo je to dôležité pre zabezpečenie dôveryhodného systému pre naše transakcie.

Po piatich úvodných kapitolách o tom ako začať, o ťažbe , vývoji a učení ako Monero funguje, ponoríme sa do technológie hlbšie. Tu sa nevyhneme mnohým technickým detailom, špeciálne čo sa týka kryptografie. Tajné (Stealth) adresy , Kruhové (Ring) transakcie a Kruhové Dôverné (Ring Confidential) transakcie už nebudú len otrepanými frázami, pretože už budete informovaní, ako to v skutočnosti celé funguje. Pre vývojárov a expertov, tu máme šiestu kapitolu, ktorá detailne popisuje protokol CryptoNote. Ak neporozumiete nejakému vysvetleniu v tejto časti, nehovorte, že sme vás nevarovali. Táto kniha sa predsa volá Mastering Monero a to z nejakého dôvodu.

V siedmej kapitole sa vrátime späť, nahliadnuť na Monero sieť a podprojekt s názvom Kovri, čo je open-source C++ implementácia I2P. Povieme si prečo je dôležitá a prečo ešte stále vo vývoji. Budete expert na uzly (Nodes) a P2P protokol.

Akonáhle dokončíme prvých sedem kapitol tejto knihy, začneme premýšľať ako začleniť Monero do financií. Ak je Monero taká revolučná kryptomena, ako ho integrovať do svojho biznisu? O tom bude ôsma  kapitola a zodpovie vám práve takéto otázky. Od JSON RPC k OpenAlias, každý môže začať akceptovať Monero.
