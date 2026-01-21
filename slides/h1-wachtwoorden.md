---
title: "Hoofdstuk 1: wachtwoorden"
---

# Hoofdstuk 1: wachtwoorden

---

<img src="./img/h1/how_hacking_works.png" class="r-stretch" />

---

<img src="./img/h1/wooclap.png" />

https://app.wooclap.com/KHODEI

---

## Wat is volgens jou een goed wachtwoord?

- Musti2012 &rarr; <span style="color:red">te kort, voorspelbaar</span>
- A8!Kgh3 &rarr; <span style="color:red">te kort</span>
- Ikstudeerophogent &rarr; <span style="color:red">voorspelbaar</span>
- SchoonmeersenHOGENT &rarr; <span style="color:red">voorspelbaar</span>
- 8765 &rarr; <span style="color:red">te kort, weinig complexiteit</span>
- LiefKleinKonijntje &rarr; <span style="color:green">lang, NL (zolang de woorden random gekozen zijn)</span>
- LiefKlijnKoneintje &rarr; <span style="color:green">lang, NL, typfout (zie hierboven)</span>
- Shadow1Hogent &rarr; <span style="color:red">Truucjes helpen niet</span>
- Shadow1Facebook &rarr; <span style="color:red">Truucjes helpen niet</span>
- kmAIw0IlCUvX5nk9 &rarr; <span style="color:green">Ok! Kan je het onthouden?</span>

---

- Experimenteer even met volgende links, maar steek hier niet jouw echte wachtwoorden in!
  - https://bitwarden.com/password-generator/
  - https://bitwarden.com/password-strength/

---

<img src="./img/h1/Hive-Systems-Password-Table-2024-Rectangular.png" class="r-stretch" />

Notes:

- https://www.hivesystems.io/blog/are-your-passwords-in-the-green

---

<img src="./img/h1/est-password-recovery-times.jpeg" class="r-stretch" />

Notes:

- https://twitter.com/TerahashCorp/status/1155112559206383616/photo/1
- Dit is een richtlijn, de daadwerkelijke tijd hangt af van het system, software, ... waarmee je het wachtwoord zou willen kraken.

---

- De **lengte** is dus heel belangrijk!
- Nog beter dan een wachtwoord is een **wachtzin** (**passphrase**)
  - "Purple Elephants Sliding Over Clouds"
  - "3@pples&Or@nges#Ban@nas"
  - "Chocolate Cake Is My Favourite dess3rt"
- https://useapassphrase.com

![](./img/h1/password-length.gif)

---

## Password policies: not done anymore

![](https://preview.redd.it/this-is-the-worst-password-requirement-i-have-ever-seen-v0-aa75btk4f90a1.jpg?auto=webp&s=0c03346d7b360c24c561e527c448d83d65d5f9ea) ![](https://i.chzbgr.com/full/7817598976/h49DE69DD/password-complexity-rules) ![](https://miro.medium.com/v2/resize:fit:840/0*wlHiqx3xsJL7SkF1.png)

Notes:

- https://www.starlab.io/blog/why-enforced-password-complexity-is-worse-for-security-and-what-to-do-about-it

---

- Bedrijven hebben vaak password policies waardoor je je wachtwoord **regelmatig** moet **wijzigen**
- Volgende wachtwoordwijziging doe je best niet elke maand of je personeel heeft wachtwoorden als ...
  - January123, February123, ...
  - Summer2023
- Op die manier heeft wachtwoorden wijzigen **geen zin**
- Wordt tegenwoordig ook **afgeraden** (bv. door NIST)
- https://neal.fun/password-game

Notes:

- https://arstechnica.com/information-technology/2016/08/frequent-password-changes-are-the-enemy-of-security-ftc-technologist-says/
- https://bitwarden.com/resources/world-password-day/
- https://www.beyondtrust.com/blog/entry/top-15-password-management-best-practices
- https://nordpass.com/poor-company-passwords/
- https://bishopfox.com/blog/password-security

---

## Hoeveel wachtwoorden?

<img src="./img/h1/xkcd-password-reuse.png" class="r-stretch" />

Notes:

- https://xkcd.com/792/

---

- https://haveibeenpwned.com/

<img src="./img/h1/have_i_been_pwned.png" class="r-stretch" />

---

- Gebruik voor elke website een **apart** wachtwoord!
- Bij **datalekken** worden vaak wachtwoorden op straat gegooid
  - Niet alle bedrijven zijn even zorgvuldig met hun beveiliging (of beveiligen niet!)
  - Hackers proberen deze wachtwoorden (geautomatiseerd) uit op andere sites
  - Hetzelfde wachtwoord gebruikt, kans groot dat ze op jouw andere accounts ook binnengeraken

---

- Gebruik **geen** trucjes
  - Bv. hogent19jan2023, google1nov1998, ...
  - Tools zoals hashcat en AI-hacktools herkennen dit meteen en kunnen zo al een gedeelte van het wachtwoord achterhalen
  - De effectieve ongekende lengte van het wachtwoord wordt een pak kleiner

Notes:

- `hogent19jan2023`, `google1nov1998` &rarr; website + dag + maand + jaar
  - 31 mogelijke dagen x 12 mogelijke maanden x 10000 mogelijke jaren == 3720000 mogelijkheden == 1 uur om te kraken bij 1000 mogelijkheden / sec
- 14 random karakters [kleine letters, hoofdletters, leestekens, ...
  - == 128^14 == 316912650057057350374175801344 mogelijkheden == +/- 10049234210332869000 jaar om te kraken bij 1000 mogelijkheden / sec

---

## Hoe onthouden?

- **Password managers** zijn zeker een goede oplossing
- Vullen wachtwoorden **automatisch** aan in de browser

<iframe width="1066" height="600" src="https://www.youtube.com/embed/hWqyPW0QJRk?si=PyDoAlUauL-L3Qhk" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

---

- Voordelen:
  - Jouw wachtwoorden worden **versleuteld** opgeslagen
  - Je kan voor elke login een **aparte** username en wachtwoord instellen (niet vertrouwen op geheugen of post-it op scherm)
  - Heeft een ingebouwde password **generator**

---

- Nadelen:
  - Je **master password** is nu extreem belangrijk
  - Je **vertrouwt** het bedrijf achter de password manager
  - De software / plugins moet je 100% vertrouwen, en deze kunnen ook **bugs** hebben

---

Beter een password manager dan overal hetzelfde wachtwoord of voor de hand liggende variaties!

<img src="https://res.cloudinary.com/bw-com/image/upload/v1/ctf/7rncvj1f8mw7/7MxCY8VttLPQLbByiotlug/912d4b50c0ddccbb93478c0d1fad3fe8/bitwarden.com.png?_a=DATAdtAAZAA0" width="800" /> <img src="https://res.cloudinary.com/dbulfrlrz/images/f_auto,q_auto/v1707563934/wp-pme/proton-pass-beta-blog@2x/proton-pass-beta-blog@2x.?_i=AA" width="800" />

---

## 2FA

- Multi-Factor Authentication (**MFA**/**2FA**)
  - What you **know**
    - Wachtwoorden, wachtwoordzinnen, pincodes, ...
  - What you **have**
    - Smartcards, beveiligingssleutelhangers, toegang tot GSM (authenticator app of SMS), toegang tot e-mailaccount (verificatie e-mail), ...
  - Who you **are**
    - Biometrie: een uniek fysiek kenmerk zoals vingerafdruk, netvlies, stem, ...
  - **Minstens 2 van de 3** nodig

---

<div class="multicolumn">
<div>
    <img src="./img/h1/totp.png" />
</div>
<div>
    <img src="./img/h1/yubikey.png" />
</div>
</div>

Notes:

- https://www.yubico.com/products/

---
