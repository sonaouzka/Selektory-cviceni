# Cvičení na CSS selektory

## Fork úkolu

1. Přihlas se do Githubu.
2. Udělej si **fork** tohoto repozitáře (vpravo nahoře). Tím se ti úkol zkopíruje to tvého Github účtu.  
   ![fork](git/fork.png)
3. Tento repozitář si ze svého Githubu potom naklonuj k sobě na disk.

![clone](git/clone.png)

Zkopíruj si odkaz se záložky **clone** a potom v terminálu ve vybrané složce spusť příkaz `git clone ODKAZ`. Například `git clone https://github.com/marketaanezka/Selektory-cviceni.git`.

![git clone](git/gitclone.png) 4. Tady už můžeš přidávat, commitovat a pushovat změny a uvidíš je na svém Githubu.  
! Pokud by sis naklonovala rovnou tento repozitář, nemohla bys do něj ukládat změny! \
Na to, jak udělat fork repozitáře se můžes podívat v [krátkém videu](https://youtu.be/K7rE3jRCjD4).

## Zadání

Prohlédni si soubor index.html a spusť si ho v Live Serveru. Uvidíš _seznam kontaktů_.
![Selektory zadani](selektory_zadani.jpg)

Prohlédni si strukturu html souboru.

### V první části používej pro stylování pouze selektory typu element (nepoužívej třídy)

1. Každé druhé sekci přidej bílé pozadí
2. Fotografii přidej 3px silný rámeček barvy lightblue. Dej pozor, aby se rámeček nepřidal i ikonám.

### Pro tento úkol použij třídy

- Nastyluj ikony pro volání a zprávu, tak aby se při najetí myši:

1.  ikonka zvětšila. Použij pro to vlasnost a hodnotu `transform: scale(1.3);`
2.  kurzor změnil na pointer/ručičku (vlasnost `cursor`)

#### Bonus

- Pro plynulé zvětšení si najdi použití vlastnosti `transition` a uplatni ho na ikonky.

## Výsledek

![Selektory_vysledek](selektory_result.gif)

### Ulož si změny do Githubu

V terminálu se přesuň do správné složky. Pro přesunutí do složky použij , pro přesun o složku výš použij `cd ..`

![git clone](git/folder.png)

Ve složce postupně spusť tyto příkazy:

1. `git add .`
2. `git commit -m "Moje zprava"`
3. `git push`
