# e-klase Palīgs — Tavs personīgais mācību supervaronis

Mājaslapa skolēniem Latvijā  
Ievadi savus e-klase.lv datus vienreiz — un saņem īstus mājasdarbus, motivāciju latviešu valodā, gudrus mājienus (nekad gatavus risinājumus!) un īstu spēles līmeņu sistēmu.

| «Mācies. Uzvari. Lepojies.» — ar spēļošanu kā dzinuli |

## Ko viņš prot
1. Droši pieslēdzas tavam e-klase.lv kontam (parole redzama tikai tev)  
2. Ar vienu klikšķi parāda šodienas un tuvāko dienu mājasdarbus  
3. Dod spēcīgu motivāciju latviski — komanda „motivācija”  
4. Ja prasīsi „kā risināt?” — saņemsi tikai gudrus pretjautājumus un mājienus  
5. Katru reizi, kad uzraksti „izdevās”, „paldies”, „gatavs” — +10 punkti  
6. Automātiski paaugstina līmeni ar uguņošanu un trofejām

## Kāpēc tas ir forši

| Problēma                            | Risinājums (šī mājaslapa)                             |
|-------------------------------------|--------------------------------------------------------|
| Pārāk daudz uzdevumu, nav motivācijas| Ikdienas pārskats + latviskas motivācijas frāzes       |
| Gribas nokopēt atbildes             | Lieku domāt pašam — tikai mājieni un jautājumi         |
| Mācīties garlaicīgi                 | Pārvērš mācības īstā spēlē ar līmeņiem un punktiem     |
| Vecāki/baidās no krāpšanās   | 100 % godīgi — tu tiešām iemācīsies                    |

## Kā palaist (5 minūtēs)

### 1. Uzstādi Python
https://www.python.org/downloads/ → lejupielādē un uzstādi  
Atzīmē Add Python to PATH

### 2. Lejupielādē projektu
```bash
git clone https://github.com/tavs-lietotājvārds/eklase-paligs-web.git
cd eklase-paligs-web

3. Uzstādi bibliotēkas

pip install flask requests beautifulsoup4

4. Palaid serveri

python app.py

5. Atver pārlūkā
http://localhost:5000
Ievadi savus e-klase datus → baudi!

Komandas / funkcijas lietošanā
•  Ieraksti jebko ar vārdu motivācija → saņem iedvesmu
•  Ieraksti palīdzi / kā risināt / grūti → saņem gudru mājienu
•  Kad pabeidz uzdevumu → raksti izdevās / paldies / gatavs → +10 punkti un iespējams līmenis augšup!

Nākotnes plāni (Roadmap)
Funkcija
Apraksts {
Ikdienas 17:00
atgādinajumi
Automätiska zina ar
nepadaritajiem darbiem
Draugu lideru
tops
Kuram šonedēl augstākais limenis?
Foto uzdevuma
nolasišana
Nosüti bildi → paligs izlasa un
palidz
Streak &
nozimites
7 dienas pēc kārtas = uguns
nozimite
Vecăku nedēlas
kopsavilkums
Anonims pārskats par
progresu
