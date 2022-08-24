  ## Tema proiectului
  
  În mediul Matlab a fost proiectat un regulator fuzzy pentru controlul unui proces descris de funcția de transfer:
  
  $$ Gp(s) = {0.8 \over (81s + 1)(10s + 1)} $$
  
  Performanțele impuse:
  - e = 3 (eroarea staționară)
  - Mv = 3 (suprareglajul)
  - ts = 80 (timpul de stabilire)

  În acest proiect s-a realizat implementarea regulatorului proiectat, în limbajul C++, care mai apoi a fost testat pentru diverse valori ale mărimilor de intrare ale sistemului de inferență prin comparație cu funcționarea aceluiași sistem de inferențe realizat în Matlab.  
