Faglig refleksion af opgaven ”Implementering af figma design”
Denne refleksion beskriver min proces med at løse opgaven "Implementering af Figma-design". Formålet var at blive fortrolig med nye teknikker og at beskrive, hvordan jeg løste opgaven, hvilke udfordringer jeg stødte på, og hvad jeg lærte.
Eksempel 1- GSAP og ScrollTrigger
En af de teknikker vi lærte i dette tema var GSAP. Dette gav mig et helt ny blik på at kunne lave animationer. Jeg benyttet ScrollTrigger i min opgave til at lave en animation, der skulle følge når brugeren scroller ne på siden. Så brugeren selv kan ”styre” animationen. 

![readme1](https://github.com/user-attachments/assets/5f0704ad-271e-49a4-95c4-d31c64c7c0f2)


Når jeg til opgaven har benyttet Astro, så skulle jeg først installere GSAP, og derefter så importere ScrollTrigger for at kunne benytte det. I det overstående eksempel har jeg benytte min selektor .parent1 til at udløse min funktion når den har nået 65% ned fra toppen af viewporten og slutte igen ved 55% ned fra toppen af viewporten. For at brugeren selv kan ”styre” animationen, benyttede jeg scrub:true;. Dette gør at animationen følger med når brugeren scroller på siden.  Derudover har jeg lavet en variabel med procent, da denne animation var ringe der skulle vise et antal procent. Dette gjorde koden nemmere at vedligeholde, skulle der ske ændringer. 
Eksempel 2- Details og Summary
I dette tema lærte vi også om <details> og <summary>. Dette fangede min interesse meget, da man nu kunne lave ”pop-ind” ”pop-ud”, som jeg i denne situation benyttede til en FAQ-komponent. Dette gjorde jeg helt uden JS, kunne lave en simpel opsætning med kode, og derefter style det efter designet der var givet. Dette gjorde min proces meget mere enkel, og jeg sparet en hovedpine fra at lege med JS. 


![readme2](https://github.com/user-attachments/assets/04f7fa74-8518-4430-899e-ab66bbdb5358)

Jeg stødte på flest problemer med opsætningen af grid, subgrid og flex. Ved at gennemgå gamle opgaver fandt jeg løsninger, som jeg kunne bruge i denne opgave. Jeg har lært at opsætte variabler til både styling af elementer og generelle stilarter, hvilket sparede tid og gjorde vedligeholdelsen lettere. Jeg blev også stor fan af nesting, da det gjorde min proces nemmere og gav mig en bedre forståelse af teknikken.
