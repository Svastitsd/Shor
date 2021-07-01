# Shor
A jupyter notebookok tartalma röviden:

Mindegyik nootebook segédfüggvényekkel kezdődik, melyek a Shor-algoritmus elő- és utófeldolgozásához szükségesek.
Ezek mind hatékonyan (a probléma méretében polinomiálisan) skálázódnak.

A notebookok tartalma röviden:
1. Shor.ipynb :
  - A Shor-algoritmushoz szükséges kvantum kapuk implementációja (ezek nagy része a "modular exponentiation" részhez kell)
  - A Shor-algoritmsus elő- és utófeldolgozásához szükséges klasszikus algoritmusok megvalósítása
  - Minden olyan részfeladathoz tartozó kód, amihez az algoritmus kvantumos részének meghívása szükséges:
    - konkrét kvantumáramkörökben lévő kapuk számának, mélységének meghatározása
    - a mért bitstringek eloszlása
    - szükséges futtatások száma


2. a_N.ipybn :
  - mely (a, N) párok esetén van szükség kvantumáramkörre, és melyek vezetnek sikerre
  - Adott (a, N) pár esetén mekkora valószínűséggel kapjuk meg a periódust a kvantumáramkör egyszeri futtatásából

3. bitsztring_eloszl.ipybn : 
  - fizikai hibák nélkül mi a kvantumáramkör méréséből kapott bitstringek eloszlása
  - erre az eloszlásra a 'readout error' hatásának szemléltetése

4. erőforrás.ipynb :
  - A kvantum kapuk számának, áramkör mélységének n=[log_2(N)] szerinti skálázódása
  - A kvantumáramkör sikerhez szükséges futtatásainak számának várható értéke, és fizikai hibák hatása erre
  - A sikerhez szükséges idő várható értéke és hibák hatása erre

5. futtatások_száma.ipynb :
  - A szükséges futtatások számának várható értéke (ez az erőforrás.ipybn fileban is szerepel)
  - A szükséges futtatások számának eloszlása
