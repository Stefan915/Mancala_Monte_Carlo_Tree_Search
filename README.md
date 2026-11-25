### Scop:

Implementarea jocului Mancala cu posibilitatea de a juca impotriva calculatorului, algoritmul folosit pentru adversar fiind unul bazat pe cautarea pe arbori Monte Carlo. Jocul ales este unul potrivit datorita complexitatii sale ridicate din punct de vedere al strategiei alese (este foarte influentat de numarul de niveluri parcurse) si simplitatii mutarilor (la un moment dat, un jucator are de ales doar dintre 6 mutari), fapt care poate demonstra in mod foarte usor cresterea capacitatii de joc al adversarului cu un cost computational mai mic. Desi are un numar de mutari posibile la un moment dat foarte mic, complexitatea creste exponential datorita multitudinii de factori la care jucatorul trebuie sa fie atent, avand aproximativ 6^20 stari posibile.

### Limbaje:
- Python:
  - Jocul principal + AI
- Matlab (poate)
  - Studiu de caz
  - Simulare
  - Grafice interesante formule/progres joc
----------------------------------------------------------------------------------------------
### Membri:
- 1:
  - Simularea Monte Carlo de baza
- 2:
  - Functii de fitness diferite, dificultati diferite, etc
  - Core-ul jocului (simulare backend)
- 3:
  - Vizualizare prin arbore Monte Carlo, tuning parametri + grafice si statistice AI
  - Interfata grafica cu utilizatorul
