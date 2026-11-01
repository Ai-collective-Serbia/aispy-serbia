# AI SPY: nominacije govornika

Stranica za nominacije govornika za **AI SPY** (AI Collective Serbia, 29. novembar 2026, Startit, Beograd).

- Sajt: https://aispy-serbia.netlify.app
- Engleska verzija: https://aispy-serbia.netlify.app/?lang=en
- Hosting: Netlify (projekat `aispy-serbia`)
- Forma: Netlify Forms, forma `nominate` (prijave stižu u Netlify Forms tab i na mejl chaptera)

## Kako menjati stranicu
Izmeni `index.html` i sačuvaj (commit). Kad je repozitorijum povezan sa Netlify-em, sajt se sam ažurira za minut.

## Tehnika
- `data-netlify="true"`, skriveno polje `form-name="nominate"`, honeypot `bot-field`
- Slanje preko fetch POST na `/` (urlencoded)
- U repozitorijumu nema ličnih podataka: prijave se čuvaju samo na Netlify-u.
