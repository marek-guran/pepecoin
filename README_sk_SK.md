<h1 align="center">
<img src="https://i.imgur.com/yap2xAX.png" alt="Pepecoin" width="300"/>
<br/><br/>
Pepecoin Core [PEPE, ₱]  
</h1>

Zvoľte jazyk: [EN](./README.md) | [CN](./README_zh_CN.md) | [PT](./README_pt_BR.md) | [FA](./README_fa_IR.md) | [VI](./README_vi_VN.md) | SK

Pepecoin je komunitne sústredená kryptomena, vytvorená jedným z pôvodných členov komunity Dogecoin z roku 2013. Pepecoin bol vytvorený s jediným účelom - vytvoriť novú a zábavnú komunitu podobnú pôvodnej komunite Dogecoin.

Na rozdiel od všetkých predchádzajúcich iterácií je Pepecoin layer 1. To znamená, že neexistujú žiadne likvidačné pooly, žiadne blokovanie peňaženiek a žiadne zložité smart kontrakty. Pepecoin je jednoduchý blockchain.

Softvér Pepecoin Core umožňuje každému prevádzkovať tzv. uzol v sieti blockchainu a používa Scrypt hashovaciu metódu pre Proof of Work. Je adaptovaný z Dogecoin Core, Bitcoin Core a ďalších kryptomien.

Pre informácie o predvolených poplatkoch používaných v sieti Pepecoin kliknite na [odporúčané poplatky](doc/fee-recommendation.md).

**Webstránka:** [pepecoin.org](https://pepecoin.org)

## Rozdiel oproti Dogecoinu

Pepecoin je fork Dogecoinu. Pre účely dôveryhodnosti sa budeme snažiť udržať Pepecoin podobný Dogecoinu. 

Zmeny:

* Adresy začínajú na `P`, miesto písmena `D`
* Funkcie BIPS sa začnú používať na bloku číslo 1000
* AuxPow sa spustí na bloku číslo 42,000 (ID Reťazca: 63)
* Používateľské prostredie nadizajnované pre Pepecoin

## Použitie 💻

Aby ste začali svoju cestu s Pepecoin Core, preštudujte si [inštalačnú príručku](INSTALL.md) a [návod na začatie](doc/getting-started.md).

API JSON-RPC poskytované Pepecoin Core obsahuje vlastnú dokumentáciu, ktorá môže byť zobrazená pomocou príkazu `pepecoin-cli help`, podrobné informácie o každom príkaze môžete zobraziť pomocou `pepecoin-cli help <príkaz>`. Alternatívne, sa môžete pozrieť na [dokumentáciu Bitcoin Core](https://developer.bitcoin.org/reference/rpc/) - ktorá implementuje podobný protokol - a je spracovaná vo webovej verzii.

### Porty

Pepecoin Core štandardne používa port `33874` pre peer-to-peer komunikáciu, ktorá je nevyhnutná na synchronizáciu blockchainu "mainnet" a na zostanie v obraze o nových transakciách a blokoch. Okrem toho môže byť otvorený port JSONRPC, ktorý pre uzly mainnet štandardne používa port `33873`. Dôrazne sa neodporúča vystavovať porty RPC verejne mimo lokálnu sieť.

| Funkcia  | mainnet | testnet | regtest |
| :------- | ------: | ------: | ------: |
| P2P      |   33874 |   44874 |   18444 |
| RPC      |   33873 |   44873 |   18332 |

## Prebiehajúci vývoj 💻

Pepecoin Core je open source a je riadený komunitou. Vývojový proces je otvorený a verejne viditeľný, každý môže vidieť, diskutovať a pracovať na softvéri.

Hlavné zdroje pre vývoj:

* [GitHub Projekty](https://github.com/pepecoinppc/pepecoin/projects) sa používa na sledovanie plánovanej a prebiehajúcej práce pre nadchádzajúce vydania.
* [GitHub Diskusie](https://github.com/pepecoinppc/pepecoin/discussions) sa používa na diskusiu o funkciách, plánovaných aj neplánovaných, súvisiacich s vývojom softvéru Pepecoin Core, základnými protokolmi a aktívom PEPE.
* [PepecoinDev subreddit](https://www.reddit.com/r/pepecoindev/)

### Verzovanie
Čísla verzií nasledujú sémantiku ```hlavná.menšia.záplata```.

### Vetvy
V tomto repozitári existujú 3 typy vetiev:

- **master:** Stabilný, obsahuje najnovšiu verziu posledného vydania *major.minor*.
- **maintenance:** Stabilný, obsahuje najnovšiu verziu predchádzajúceho vydania, ktoré je stále aktívne udržiavané. Formát: ```<verzia>-maint```
- **development:** Nestabilná verzia, obsahuje nový kód pre plánované vydania. Formát: ```<verzia>-dev```

*Vetvy Master a Maintenance sú výhradne zmeniteľné vydaním. Plánované*
*vydania budú mať vždy vetvu Development a pull requesty by mali byť*
*odoslané proti nim. Vetvy Maintenance sú len pre **opravy chýb,***
*prosím, odosielajte nové funkcie na vetvu Development s najvyššou verziou.*

## Prispievanie 🤝

Ak nájdete chybu alebo máte problémy s týmto softvérom, prosím nahláste to
pomocou [systému hlásenia chýb](https://github.com/pepecoinppc/pepecoin/issues/new?assignees=&labels=bug&template=bug_report.md&title=%5Bbug%5D+).

Prosím, pozrite sa na [sprievodcu prispievania](CONTRIBUTING.md), aby ste zistili, ako sa môžete
zúčastniť na vývoji Pepecoin Core. Najčastejšie nájdete v tejto sekcii
[témy potrebujúce pomoc](https://github.com/pepecoinppc/pepecoin/labels/help%20wanted),
kde bude vaša pomoc, príspevky mať veľký dopad na vývoj a budú veľmi cenné.

## Komunity 🐸

Môžete sa pridať do komunít na rôznych sociálnych médiách.
Ak chcete vidieť, čo sa deje, stretnúť ľudí a diskutovať, nájsť najnovšie meme, dozvedieť sa
viac o Pepecoine, poskytnúť alebo požiadať o pomoc alebo zdieľať svoj projekt.

Tu nás nájdete:

* [r/Pepecoin](https://www.reddit.com/r/pepecoin/)
* [Discord](https://pepecoin.org/discord)

## Často kladené otázky ❓

Máte otázku týkajúcu sa Pepecoinu? Odpoveď je možno už v [FAQ](doc/FAQ.md) alebo v [sekcií otázok a odpovedí](https://github.com/pepecoinppc/pepecoin/discussions/categories/q-a) na diskusnom fóre!

## Licencia ⚖️
Pepecoin Core je vydaný pod podmienkami licencie MIT. Pozrite
[COPYING](COPYING) pre viac informácií alebo preštudujte
[opensource.org](https://opensource.org/licenses/MIT)