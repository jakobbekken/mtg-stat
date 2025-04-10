# MTG STAT

## Hvorfor?
Magic: The Gathering er alle kortspillenes far lagd for over 30 år siden. Spillet kombinerer sjanse og ferdighet og har vokst til å bli ikke bare verdens største kortspill, men også til å ha et stort og rikt konkurransemiljø. Det spilles ukentlige konkurranser lokalt over hele verden, store turneringer nasjonalt og massive profesjonell turnéer i utlandet. 

De fleste plassene er det også premiering om du spiller bra. Det er alt fra sjeldne og dyre kort til 1,000,000$ i pengepremie for Pro Touren. For å vinne må du blant annet minske sjansene du tar med kunnskap om hva som ligger på toppen av kortstokken. Ved å bruke statistikk kan man bruke et utvalg av data til å bestemme hva kort du vil bruke, slik at du alltid trekker det du trenger, og at du tar i bruk de beste kortene i spillet.

## Hva?
### Drafting
En måte å spille på hvor du bygger kortstokken du skal spille med "on the spot".

Hver av de 8 spillerene har 3 pakker på 15 tilfeldige kort hver og gjør en prosess per pakke for å velge kort å brue:
1. Pakken åpnes og hver spiller velger ett kort.
2. Hver spiller bevarer det valgte kortet og sender resten mot venstre.
3. Hver spiller motar ny pakke og velger ett kort på nytt.
4. Hver spiller repeterer til alle kort er valgt.
5. Åpner neste pakke, repeterer prosess, men sender kort rundt andre veien.

Etter alle kort er delt ut starter spillere å sette sammen deckene sine og spiller turnering etterpå. 

### Viktig info

#### Kort-typer
- **Land** er spillets penger og er det du brukre på å betale for å spille kort. Landene i seg selv er gratis å spille, men du er begrenset til kun ett land hver tur. Med andre ord ønsker du alltid å spille et land hver eneste tur. Når de er i spill får du 1 mana (tenk på det som en mynt) per land hver tur til å betale for andre kort, og ubrukt mana spares ikke til neste tur.
- **Spells** er kortene du spiller som gjør ting og vinner deg spillet. Hvert kort har en tall kostnadd og for å spille de må du betale med landene dine

#### Kort 

#### Spill-start
Spillet starter med at hver spiller trekker 7 kort hver. Spillerene ønsker at hånden skal ha en god flyt, såkalt curve, slik at du har mulighet til å spille ett land hver eneste tur og spiller spells slik at all mana er brukt opp og klar til neste runde.

Om en spiller ikke er fornøyd med kortene sine kan spilleren gjøre en mulligan, altså trekke på nytt. Når trekker de 7 nye kortene må du legge fra deg et av de på bunnen av bunken igjen. Dette kan gjøres så mange ganger man vil, men du må legge ett ekstra kort på bunnen for hver gang.

#### Spillets gang
Hver tur starter med at spilleren trekker et kort (bortsett fra første spiller sin første tur). De har så muligheten til å spille opp til ett land fra hånda om de har og så mange spells de har rå til ut ifra land i spill.

## Problemer
### Land curve
Hvor mange land du trenger for høyest sjanse til å kunne spille ett land hver tur?

Ta i betraktning:
- Farger på land og fargefordeling på spells.

### Spell curve
Hva kostnadder skal kortene mine ha for høyest sjanse til å utnytte all mana hver tur?

Ta i betraktning:
- Farger på land og fargefordeling på spells.

### Mest valgt
Hvilke kort er mest plukket?

Ta i betraktning:
- Ulike farger og fargekombinasjoner

### Mest vinnende kort
Hvilke kort har vunnet mest?

Ta i betraktning:
- Ulike farger og fargekombinasjoner

### Mest vinnende fargekombinasjoner
Hvilke farger er best og hvordan kombinasjoner har vunnet mest?

## Hvordan?

Verktøy:
- 17 lands data for drafts
- SQL for raske queries i store datasett
- Python for utregning

Metoder:
- Hypergeometri
- Monte Carlo
- Bayes
- Regresjon
- Frekvens
- Poisson
