#  Analiza și prezentarea rezultatelor testării A/B 

### Ce vei învăța pe parcurs:

- Formularea de ipoteze pentru test.
- Selectarea audienței și a parametrilor pentru evaluarea testului.
- Calcularea dimensiunii eșantionului necesar.
- Crearea un plan al următoarelor etape în funcție de rezultatele testului.

În aplicația noastră mobilă, după ce se conectează, utilizatorului i se oferă un abonament săptămânal de 4,99 $, care oferă acces la caracteristici premium. În prezent, **17%** dintre utilizatorii care primesc oferta cumpără un abonament de pe acest ecran.

Am decis să testăm un design alternativ pentru ecranul de abonament, în care oferim de asemenea un abonament de 4,99 dolari, dar îi spunem utilizatorului că are o reducere de 50%.

În fiecare zi, aproximativ **2.000** de utilizatori instalează aplicația, iar **34%** dintre ei ajung la ecranul de abonament.

## **Sarcini (pas cu pas):**
1. Expune ipoteza pe care o vom încerca în acest test.
2. Descrie ce utilizatori ar trebui să includem în acest test.
3. Selectează metricele țintă și auxiliare și justifică-ți alegerea.
4. Calculează dimensiunea eșantionului de care avem nevoie pentru a testa ipoteza și numărul de zile în care ar trebui să se desfășoare testul.



### În aplicația noastră mobilă, după ce se conectează, utilizatorului i se oferă un abonament săptămânal de 4,99 $, care oferă acces la caracteristici premium.
### În prezent, 17% dintre utilizatorii care primesc oferta cumpără un abonament de pe acest ecran.
### Am decis să testăm un design alternativ pentru ecranul de abonament, în care oferim de asemenea un abonament de 4,99 dolari, dar îi spunem utilizatorului că are o reducere de 50%.
### În fiecare zi, aproximativ 2.000 de utilizatori instalează aplicația, iar 34% dintre ei ajung la ecranul de abonament.

Expune ipoteza pe care o vom încerca în acest test
- **Ipoteza alternativă (H1):** Mai mulți utilizatori vor decide să se aboneze la aplicația noastră la prețul de 4,99 $ dacă primesc ecranul cu mențiunea că au o reducere de 50%
- **Ipoteza nulă (H0):** Nu se va observa nicio diferență semnificativă statistic între grupa A (care vede ecranul original la prețul de 4,99 )și grupa B(cei cărora li se oferă aplicația tot la 4,99 $, dar se presupune că este o reducere de 50%)

Descrie ce utilizatori ar trebui să includem în acest test
- În cadrul testului nostru, vom include utilizatorii care instalează aplicația pentru prima dată, aproximativ 2000 (două mii) pe zi, pe o perioadă determinată, în funcție de mărimea eșantionului necesar.

Selectează metricele țintă și auxiliare și justifică-ți alegerea 
- **Metrică țintă:** Rată de conversie (procentajul de utilizatori care cumpără abonamentul)
- **De ce Radă de conversie?** - Deoarece dorim să vedem care este eficeinta Design-ului alternariv al ecranului de abonament cu reducerea de 50% (grupa B).
Îmbunătățirea semnificativă statistic a ratei de conversie este motivul principal pentru introducerea ecranului alternativ, iar acest test ne va ajută să evaluăm dacă acest ecran și-a atins scopul.
În cazul nostru, ne interesează conversia directă a utilizatorilor din grupa B față de grupa A, conform ipotezei H1.

- **Țintă auxiliară:** Revenue (Venit) - acesta reprezintă venitul obținut din vânzarea aplicației utilizatorilor și de principiu se dorește să mărim această suma.
O altă țintă auxiliară ar fi ROMI (Return on Marketing Investment) - acest metric auxiliar măsoară eficiența investițiilor în marketing (în cazul nostru, crearea ecranului alternativ pentru atragerea clienților plătitori)


Calculează dimensiunea eșantionului de care avem nevoie pentru a testa ipoteza și numărul de zile în care ar trebui să se desfășoare testul.
- Având în vedere faptul că în fiecare zi avem 2000 de utilizatori noi care descarcă aplicația utilizând formulă de mai jos ajungem la concluzia cane trebuie cel puțin 1.6 zile de testare și un minimi absolul de 1344 utilizatori per grup. 
![image](https://github.com/user-attachments/assets/d738f5e1-acd9-4c2a-9475-782aea25f412)

Site folosit pentru redactarea calculelor: https://www.evanmiller.org/ab-testing/sample-size.html
