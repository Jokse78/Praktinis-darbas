# Praktinis-darbas

Projekto su Django pavyzdys
Repozitorija, skirta Django pavyzdžiams dėstant
Sistema daržininkams-mėgėjams
Trumpas aprašymas
Web puslapis daržininkų užrašams Naudotojai gali žymėti ką sodins ir kiek, kokios rūšies daržoves ir kokios veislės. Kada sodins sodinukus, kada persodins į lysves. Kada reikia tręsti, laistyti, purkšti nuo kenkėjų. Kiek derliaus surinkta. 

## Duomenys
    - Vartotojas
        - Vardas
        - Pavardė
        - telefonas
        - el. paštas
        - vietovė
    - daržas
        - plotas metrais
        - užsodinta veislė
        - pasodinimo data (pasėjimo)
        - sodinimas iš sėklų
        - sodinukų pikiavimas
        - sodinukų perkėlimas į lysves
        - kada tręšti
        - kada laistyti (jei nelyja)
        - kada purkšti nuo kenkėjų
        - kada imti derlių
        - pastabos
          
    - veislė
        - daržovių rūšies veislė (pavadinimas)
        - veislės aprašymas
        - reikalinga veislei vieta
        - reikalinga žemė daržovių auginimui
        - reikalingi įrankiai, įranga daržovėms auginti
        - auginama šiltnamyje ir/ar tik lauke
          
## Procesai
    - Veislės pasirinkimas
        - Naudotojas pasirenka veislę "Išsirinkite augalo veislę"
        - Naudotojui pasirinkus veislę rodomas veislės aprašymas
        - Naudotojas paspaudžia mygtuką "Išsirinkite augalo veislę" ir veislė išsisaugo.
        - Naudotojas gali paspausti mygtuką "Peržiūrėti veislę ir jos aprašymą"
    - Savo įkeltų veislių peržiūra
        - Naudotojas paspaudžia mygtuką "mano augalų veislės"
        - Naudotojui parodomos visos jo įkeltos veislės
    - Reikiamo sėklų kiekio apskaičiavimas:
        - Aukščiau aprašytam augalų veislių sąraše prie kiekvienos veislės  yra mygtukas "įvesti norimą apsodinti plotą, metrais:“
        - Paspaudus mygtuką "redaguoti", atsidaro langas, identiškas įvedimo langui, bet jau su esamais duomenimis
        - Duomenis galima pakeisti
        - Paspaudus mygtuką "saugoti", duomenys išsaugomi.
    - Reikiamos žemės įvertinimas pagal rekomendacijas veislei
    - Įrankių paieška ir pasirinkimas:
        - Pagrindiniame puslapyje rodomas įrankių sąrašas
        - Sąrašą galima filtruoti pagal įvairius kriterijus: kategorija, jėgos šaltinis, kaina, pristatymas ir kita.
        - Taip pat galima paieška pagal raktinius žodžius
    - Sodinukų pikiavimas
        - Naudotojui išsiunčiamas el.paštu priminimas, kad laikas pikiuoti.
    - Sodinukų perkėlimas į lysves
        - Pasirenka datą ir laiką (rodomos galimos datos, tos datos, kuriomis palanku sodinti, tikrinamos orų prognozės)
    - Sodinukų trešimas
        - Pagal trąšų gamintojų rekomendacijas, išsiunčiamas priminimas, kad laikas tręšti augalus
    - Sodinikų laistymas
        - Jei remiantis orų prognozėmis ilgai nelis, tai Naudotojui siunčiamas priminimas, kad reikia laistyti augalus
    - Sodinukų purškimas nuo kenkėjų
        - Pagal insekcisidų tiekėjų rekomendacijas siunčiamas priminimas, kad reikia purkšti sodinukus nuo kenkėjų
    - Derliaus nuėmimas
        - Pagal sėklų gamintojų rekomendacijas derliaus nuėmimas, siunčiamas el.paštu priminimas
    - Pastabos
    
## Naudotojai ir rolės
    1. Naudotojai. Gali matyti ir redaguoti savo paskyros duomenis. Gali rinktis veisles. Apskaičiuoti sėklų poreikį, stebėti sodinukų augimo procesą, žymėti augalų priežiūros darbus.
    2. Sistemos administratorius. Gali matyti visų vartotojų duomenis. Neleidžia taisyti teksto.  Gali panaikinti naudotojų paskyras.
## Dizainas
Dizainas minimalus, funkcionalus
