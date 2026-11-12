# Refleksjon: Grunnleggende JavaScript

Svar når du er ferdig med oppgavene i `oppg1_grunnleggende.js`. Skriv med egne ord, og ikke se i koden mens du svarer på del A. Korte svar er helt greit.

---

## A. Forklar med egne ord

**1. Hva er forskjellen på `let` og `const`? Når bruker du hvilken?**

>let er variabler som er endrbare og const er brukt for variabler som man ikke skal endre underveis i koden.

**2. Hvorfor ble `"5" + 5` til `55`, mens `5 + 5` ble `10`?**

>Det som skjer er at du prompter et nummer til å bli en string og etter det prompter du en string til å bli et number. Grunnen til hvorfor "5" + 5 = 55 er frodi programe kan ikke plusse samen number og string sån den kan med number så da blir de bare satt vesidenav hverandre.


**3. Hva gjør `%`? Gi et eksempel fra oppgavene der du brukte den.**

> Det man bruker % er for å sjekke om det er rester etter man har delt opp grupper feks oppgave 9, med 17 spillere som måte bli delt opp in i 4 lag 17 delt på 4 funker ikke uten å gå inn i desimaler så det ender opp med at det er 4 spillere for hver gruppe og en spiller som ikke kommer in.

**4. Hva er forskjellen på `=` og `===`?**

> = bruker man til å gi output for verdier og === blir brukt til å sammenligne om verdier er det samme

**5. Forklar de tre delene i denne linja:** `for (let i = 1; i <= 5; i++)`

> I = 1 bettyr at i har verdi 1 
> i<=5 betyr at i kan være en verdi ifra 5 og under
> i++ betyr at i blir økt med 1 hver gang den blir spillt inn som en runde

**6. Når er en `while`-løkke bedre enn en `for`-løkke? Hva kan gå galt med en `while`-løkke?**

> while spilles når noe er sant som kan gå ille vist man ikke kan stoppe det, ender opp med en evig loop. men er veldig praktisk for å feks for å sjekke hvor lenge bonus varer utifra en tilit tid og når tiden har gåd ut så blir det false og da stopper bonusen.

**7. Hvorfor er den første byen i lista `byer[0]` og ikke `byer[1]`?**

> fordi i java så starter indexen på null istedetfor 1

---

## B. Bruk det du har lært

**8. Hva skrives ut her? Svar før du tester.**

```js
const temp = -3;
if (temp < -5) {
  console.log("Veldig kaldt");
} else if (temp < 0) {
  console.log("Kaldt");
} else {
  console.log("Mildt");
}
```

> kaldt

**9. Hva skrives ut her? Svar før du tester.**

```js
const lag = ["Titans", "Ulvene", "Polarnatt"];
lag.push("Nordlys");
console.log(lag.length);
console.log(lag[1]);
```

> ulvene

**10. Denne koden skal skrive ut 1, 2 og 3, men gjør det ikke. Hva er feil?**

```js
for (let i = 1; i < 3; i++) {
  console.log(i);
}
```

> funker i > 3, funker ikke i < 3

---

## C. Om din egen læring

**11. Hvilken oppgave var vanskeligst, og hvordan løste du den?**

> det ble ikke en som var spesielt vankelig. kunskapen ble sakte bygd opp etter en hver oppgave men de som kombinerte de forselige tingene man har lært seg underveis er nok de vanskeligste

**12. Hvilken feilmelding fikk du oftest? Hva betydde den?**

> SyntaxError er ikke alltids så sikker på hvor man skall brukke disse {} () []

**13. Hva gjorde du når du sto fast? Hva vil du gjøre annerledes neste gang?**

> når jeg sto fast så brukte jeg en chatbot sån at jeg kan se hvrdan å bruke de tildelte byggesteinene riktig for å få større forståelse på hvordan koden burde funke.

**14. Hvor langt kom du?**

| Nivå | Kryss av |
|---|---|
| Grunnleggende |  |
| Middels |x|
| Avansert |  |

**15. Kryss av for det du kan nå.**

| Jeg kan... | Ja | Litt | Nei |
|---|---|---|---|
| lage variabler med `let` og `const` | x |  |  |
| bruke tekst og tall, og sette dem sammen med `${}` | x |  |  |
| ta valg med `if`, `else if` og `else` | x |  |  |
| skrive en `for`-løkke |  | x |  |
| hente, legge til og gå gjennom verdier i en array | x |  |  |
| lese en feilmelding og finne riktig linje |  | x |  |

**16. Hva vil du øve mer på før vi går videre til funksjoner?**

> Jeg endte opp med å gjøre mesteparten av oppgaven på kvelden, så jeg har lyst til å bli bedre på å jobbe effektivt når jeg har tildelt tid til det på skolen. Det er bare ikke alltids hodet vil gripe de forskjellige faguttrykende og oppsettet for ulike koder på best mulig måte. Sleit derfor litt med de avanserte oppgavene som jeg kunne gjort bedre.