Fooþjónustan
====

## Keyrsla verkefnis
Til þess að setja síðuna upp á þinni tölvu þarftu að byrja á að klóna verkefnið héðan af github og setja upp dependencies. Til þess að keyra verkefnið upp þarf að nota skipunina `npm run dev`, opna `styles.scss` skránna og vista hana einu sinni. Hér fyrir neðan, í réttri röð, eru þær skipanir sem hægt er að nota á skipanalínu til að framkvæma þetta:

```
git clone git@github.com:HHProgWebDev/foo.git
cd foo
npm install
npm run dev
```
Ekki gleyma að opna `styles.scss` skránna og vista hana einu sinni. Þegar þetta hefur verið framkvæmt á verkefnið að vera uppsett og byrjað að keyra.

## Uppsetning verkefnis
Verkefnið samanstendur af tveimur möppum og rót.
Í rótinni er `styles.scss` skrá sem að heldur utan um alla stílana í verkefninu og importar aðrar nauðsynlegar stílskrár. Þar eru líka `styleguide.html` og `styleguide.css` sem að halda utan um Elements síðuna. Að auki eru allar `.html` skrár síðunnar í rótinni, svo og `README.md` skráin. Möppurnar eru `img` mappa sem inniheldur þær myndir sem birtast eiga á síðunni og svo er `scss` mappa sem að inniheldur þær `.scss` sem að `styles.scss` kallar í.

Scss-inu er skipt niður í einingar eftir hlutverki þess og/eða staðsetningu í verkefni. Þannig er navigation sláin í verkefninu með sér `nav.scss` sem að sér um flesta þá stíla sem henni við kemur. Þannig reyndum við að brjóta verkefnið niður í sem flestar heildstæðar einingar.

## Hópur
Nemendurnir sem unnu verkefnið eru:

- Hannes Þór Sveinbjörnsson - hths17@hi.is
- Ragnheiður Ásta Karlsdóttir - rak4@hi.is
