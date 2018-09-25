# Oppgaver i HTML, CSS og Javascript

1. Ta utgangspunkt i <a href="oppgave 1 - startkode.html">oppgave 1 - startkode.htm</a>. Endre slik at om man trykker på den første teksten, så vises teksten "Feil!"
rett etter knappen. (Det vil si i b-taggen med 	id="feedback1"). 
<br/><br/>_Løsningsforslag_ oppgave 1: <a href="oppgave 1 - løsning del 1.html">oppgave 1 - løsning del 1.html</a>

1. Gjør tilsvarende endring også for de to andre knappene, men med teksten "Riktig!" for den
som er riktig.	
<br/><br/>_Løsningsforslag_ oppgave 2: <a href="oppgave 1 - løsning komplett.html">oppgave 2 - løsning.html</a>

1. Endre så det vises en knapp med teksten "Neste spørsmål" umiddelbart etter
teksten "Riktig!" når denne legges til. Knappen trenger ikke gjøre noe ennå.
 
1. Endre html-en for spørsmålet og svarene til dette:
    ```html
    <div id="spm">Hvor høy er Galdhøpiggen?</div>
    <div id="svar">
        <button onclick="alternativ1()">2484m</button> <b id="feedback1"></b><br />
        <button onclick="alternativ2()">2448m</button> <b id="feedback2"></b><br />
        <button onclick="alternativ3()">2469m</button> <b id="feedback3"></b><br />
    </div>
    ```
    1. Når man trykker på knappen "Neste spørsmål", skal det vises et nytt
    spørsmål.
    1. Det skal vises nye svaralternativer til det nye spørsmålet. 
    1. Så skal man få riktige tilbakemeldinger når man trykker på disse...