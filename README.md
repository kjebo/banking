# Projektuppgiften 
Går ut på att ta fram ett enkelt system för en fiktiv bank. Banken
har ett antal kunder och varje kund kan ha ett eller flera olika bankkonton

Banken erbjuder för tillfället endast konton av typen debitkonto (Account)
- Börja med att skapa en klass som definierar konto (Account), en klass som
definierar kund (Customer) samt en bank klass (Bank).
- Alla klasser ska fungera som moduler som importeras in i main script:et

I Banken ska man kunna:
- Printa en lista med bankens kunder (personnummer, för och efternamn)
- Lägga till en ny kund med ett unikt personnummer.
- Ändra en kunds namn (personnummer ska inte kunna ändras).
- Ta bort en befintlig kund, befintliga konton måste också avslutas.
- Skapa konto (Account) till en befintlig kund, ett unikt kontonummer genereras
(VG)(första kontot får nummer 1001, nästa 1002 osv.).
- Konton ska även kunna avslutas via kontonummer attributet, saldo skrivs ut
och kontot tas bort.
- (VG) Se alla transaktioner en kund har gjort med ett specifikt konto.

För varje kund ska man kunna utföra följande:
- Se information om vald kund inklusive alla konton
(kontonummer, saldo, kontotyp).
- Sätta in pengar på ett konto.
- Ta ut pengar från kontot (men bara om saldot täcker uttagsbeloppet).

Dokumentation
1. Skapa en grundläggande struktur för dokumentet som ska lämnas in (individuellt)
2. Inledningen ska ha en beskrivning av arbetet som ska göras:
a. Inkluderar en beskrivning av projektet och målet.
b. User Stories (user stories är en beskrivning av vad användaren ska kunna göra i
applikationen. Titta i “specs” slide)
c. Teknologierna som ska användas. (Python [, -moduler- ])
3. Inkludera klassdiagram av följande klasser;
a. Bank, Customer, Account
4. Milestones och Tasks ska dokumenteras, inkluderar:
a. Beskrivning av milestones.
b. Tasks för varje milestone.
