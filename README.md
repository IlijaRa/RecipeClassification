# Zahtev zadatka

Dat je skup podataka koji sadrži podatke o prisustvu/odsustvu 150 određenih sastojaka za pojedine recepte koji potiču iz različitih zemalja. Primeniti 2 različita tipa klasifikatora koji će na osnovu informacije o prisustvu/odsustvu određenih sastojaka odrediti zemlju porekla za dati recept. Ukupno ima 10566 prikupljenih recepta iz 9 zemalja i za svaki je naznačeno prisustvo (1) ili odustvo (0) svakog od 150 sastojaka. <br>
* A. Za svaku klasu analizirati u nekoj formi (po izboru) pojavljivanja određenih sastojaka. Iskomentarisati i uporediti ih za različite klase. Podatke podeliti na trening i test set.<br>
* B. Broj svog indeksa podeliti po modulu 5 - dobijeni broj označava klasifikator koji treba da se koristi:
  * Logistička regresija 
  * kNN
  * Neuralna mreža
  * SVM
  * Stablo odluke (RF) <br>
Uz označeni klasifikator, odabrati jedan drugi tip klasifikatora po izboru (Naivni Bayes, 
Logističku regresiju, kNN, Neuralnu mrežu, SVM, RF).
* C. Za svaki od klasifikatora uraditi analizu u pogledu evaluacije/procene parametara:
  * Koristeći metodu unakrsne validacije nad trening setom odrediti optimalne parametre 
oslanjajući se na željenu meru uspešnosti. Obratiti pažnju da u svakom od podskupova 
za unakrsnu validaciju bude dovoljan broj uzoraka svake klase.
  * Za konačno odabrane parametre prikazati i analizirati matricu konfuzije dobijenu 
akumulacijom matrica iz svake od iteracija unakrsne validacije. Odabrati adekvatnu 
meru uspešnosti i potom na osnovu matrice konfuzije izračunati prosečnu vrednost 
za klasifikator, kao i vrednost te mere za svaku klasu.
  * Klasifikator sa konačno odabranim parametrima obučiti i testirati. Analizirati rezultate 
u poređenju sa rezultatima unakrsne validacije.
* D. Uporediti konačna dva klasifikatora po osetljivosti, specifičnosti i preciznosti, za svaku klasu 
posebno, kao i prosečnu tačnost klasifikatora, mikro i makro preciznost, osetljivost i F-meru. 
Iskomentarisati prednosti i mane svakog od klasifikatora.
* E. Rezultate prikazati i diskutovati u izveštaju (2-4 strane).
