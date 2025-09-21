# Vefforritun 1, 2025, hópverkefni 1

Verkefnið felst í því að smíða vef eftir forskrift.

Hönnun er í vinnslu og hægt er að skoða hana í [Figma](https://www.figma.com/design/4BvcCrMKEQ9MHQw1xd4W5J/vef1-2025-h%C3%B3pverkefni-1).

## Hópavinna

Verkefnið skal unnið í hóp með 3-4 einstaklingum. Hafið samband við kennara ef ekki er mögulegt að vinna í hóp. Hægt er að leita að félögum á slack á rásinni `#vef1-2025-vantar-hop`.

Notast skal við Git og GitHub. Engar zip skrár með kóða ættu að ganga á milli í hópavinnu, heldur á að „committa“ allan kóða og vinna gegnum Git.

Sjást ætti á _commit history_ að allir meðlimir hóps hafi tekið þátt í verkefni.

Útbúa þarf a.m.k. fimm Pull Request (PR) þar sem búið er að fara yfir af öðrum meðlim í hóp og yfirferð ásamt gagnrýni sést á GitHub.

## Lýsing á verkefni

`README.md` skrá skal vera í rót verkefnis og innihalda:

- Upplýsingar um hvernig keyra skuli verkefnið
  - `npm run dev` eða `npm start`
  - `npm run lint` skal vera til staðar og keyra stylelint á Sass
- Létt lýsing á uppsetningu verkefnis, hvernig því er skipt í möppur, hvernig CSS/Sass er skipulagt og fleira sem á við
- Upplýsingar um alla sem unnu verkefni, nöfn, HÍ notendanöfn og GitHub notendanöfn

## Tæki og tól

Verkefnið skal innihalda `package.json` og `package-lock.json` sem innihalda öll notuð tól.

Þegar verkefnið er sótt verður `npm install` keyrt á undan öllum öðrum skipunum.

Setja skal upp Sass og stylelint.

## Efni

Allt efni er í Figma hönnun en endurtekið hér.

### Síður

Efni fyrir síður eru í markdown skrám í `efni` möppu. Það sem er innan sviga eru leiðbeiningar:

- [Forsíða, `index.md`](efni/index.md)
- [Um okkur, `um-okkur.md`](efni/um-okkur.md)
- [Lausnayfirlit, `lausnir.md`](efni/lausnir.md)
- [Lausn, `lausn.md`](efni/lausn.md)

### Haus og valmynd

Haus samanstendur af merki, heiti og valmynd.

Merkið er einfaldlega lambda táknið: `λ`.

Heitið er „Forritarafjelagið“.

Valmynd skal innihalda tengla á:

- Forsíðu (tengill á forsíðu)
- Lausnir (tengill á lausnayfirlitssíðu)
- Um okkur (tengill á um okkur síðu)
- Starfsfólk (tengill á forsíðu)

### Fótur

Fótur skal innihalda fjóra flokka:

- Merki og tengingar á samfélagsmiðla í formi merkja þeirra. Þurfa ekki að vera virkir tenglar.
- „Verkefni“ sem fyrirsögn og síðan listi með tenglum á fjögur verkefni sem eru nefnd „Verkefni 1“ og svo framvegis. Tenglar á forsíðu.
- „Lausnir“ sem fyrirsögn og síðan listi með tenglum á fimm lausn sem eru nefndar „Lausn 1“ og svo framvegis. Tenglar á lausnasíðu (alltaf sami).
- „Síður“ sem fyrirsögn og síðan listi með tenglum á forsíðu, lausnayfirlit, um okkur og starfsfólk. (tenglar eins og í valmynd)

### Myndir

- [Ales Nesetril](https://unsplash.com/@alesnesetril?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash) á [Unsplash](https://unsplash.com/photos/gray-and-black-laptop-computer-on-surface-Im7lZjxeLhg?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash)
- [Max Duzij](https://unsplash.com/@max_duz?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash) á [Unsplash](https://unsplash.com/photos/man-facing-three-computer-monitors-while-sitting-qAjJk-un3BI?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash)
- [Michael Dziedzic](https://unsplash.com/@lazycreekimages?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash) á [Unsplash](https://unsplash.com/photos/clear-glass-ball-with-box-gEN5Btvf2Eg?utm_content=creditCopyText&utm_medium=referral&utm_source=unsplash)
- Avatar mynd úr Figma hönnun

## Leiðbeiningar með figma skjali

(Einnig í Figma skjali)

Hönnun byggir á „[Simple Design System](https://www.figma.com/community/file/1380235722331273046)“ frá Figma.

Kveikja á grid með ctrl+g eða show layout guides. Grid á að vera 12 dálkar með 32 px gutter. Hámarksbreidd á efni er 1200px. ALLT ætti að fylgja grind, ef það eru hlutir sem eru ekki að jafnast (aligna) við aðra hluti er það vitlaust í hönnunarskjali.

Setja skal að minnsta kosti 16px padding vinstra og hægra megin frá viewporti.

Hlekkir fara á viðeigandi síðu ef hún er til. Ef síða er ekki til skal hlekkur fara á forsíðu.

Síður sem eru tilbúnar í forritun eru merktar með ✅ ef þær eru ennþá í vinnslu eru þær merktar með ❌.

Þar sem efni er ekki eins í desktop og mobile ræður desktop. Oft á tíðum er bara fyrsta stakið afritað í mobile (er það sniðugt??)

Myndir eru nokkrar en ekki fyrir allt efni, má endurtaka fyrri myndir eða nota „placeholder“ mynd.

Það er ekki allt augljóst eða rétt. Spyrjið eða túlkið, markmiðið er ekki að fá fullkomna eftirmynd af þessum skjölum heldur ferlið og lærdómurinn sem þið dragið af því.

### Lausnir

Ekki láta form gera neitt, bara útfæra útlit.

Í mobile þarf ekki að birta neitt undir „config“, bara að hafa takkann.

Ekki elta að fá nákvæmlega eins form input, skoðið og sjáið að það er flókið en ekki fara í fyrr en flest allt annað er komið.

### Lausn

Ekki láta form gera neitt, bara útfæra útlit.

## Mat

- 10% - README eftir forskrift, tæki og tól uppsett, vefur keyrir á Netilfy.
- 10% - Git og GitHub, a.m.k. fimm Pull Request.
- 10% – Snyrtilegt, gilt (skv. stylelint) CSS/Sass, gilt og aðgengilegt HTML.
- 20% – Almennt útlit (haus, fótur, meginmál) og skalanleiki.
- 15% – Forsíða.
- 10% – Efníssíða.
- 15% – Lausnayfirlit.
- 10% – Síða fyrir lausn.

## Sett fyrir

Verkefni fyrst sett fyrir í fyrirlestri mánudaginn 15. september 2025.

## Skil

Tilnefna skal hópstjóra sem skráir sig í ákveðinn hóp undir „Hópverkefni 1“ í Canvas. Aðrir nemendur skrá sig í framhaldinu í sama hóp, hópstjóri getur líka skráð aðra nemendur í hópinn.

**Útbúa skal hóp jafnvel ef verkefnið er unnið sem einstaklingsverkefni**.

Hópstjóri skal skila fyrir hönd allra í Canvas í seinasta lagi fimmtudaginn 23. október 2025.

**Mikilvægt er að öll skil séu gerð í hóp annars munu ekki allir nemendur fá einkunn.**

Skil skulu innihalda:

- GitHub notendanöfn allra (passa þarf að allir nemendur séu í hópnum!)
- Slóð á verkefnið keyrandi í hýsingu
- Slóð á GitHub repo fyrir verkefni. Dæmatímakennurum skal hafa verið boðið í repo. Notendanöfn þeirra eru:
  - `klingsterina`
  - `kristinfrida`
  - `osk`
  - `reynirjr`

## Einkunn

Sett verða fyrir tíu minni verkefni þar sem átta bestu gilda 5% hvert, samtals 40% af lokaeinkunn.

Sett verða fyrir tvö hópverkefni þar sem hvort um sig gildir 10%, samtals 20% af lokaeinkunn.

> Útgáfa 0.2

## Útgáfusaga

| Útgáfa | Lýsing                             |
| ------ | ---------------------------------- |
| 0.1    | Fyrsta útgáfa verkefnisins         |
| 0.2    | Bæta við öllu efni úr figma skjali |
