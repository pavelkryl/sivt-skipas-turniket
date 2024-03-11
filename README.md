## Zadání

- mám evidenci skipasů
- mám hlídače, který si pamatuje který skipas kdy projel
- lyžaři se skipasy jezdí na sjezdovce

- skipas identifikujte pomocí UUID (generujte)
- skipas má expiraci/platnost

- při průjezdu budu hlídat, že skipas neprochází turniketem příliš brzy po skenu a kontrolujte i platnost (ne jen existenci a časový limit)

## Hlavní metoda

- chování hlavní metody: vrací False/True pokud se turniket ne/má otevřít
- co nechci řešit:
  - otevírání, zavírání, sken
