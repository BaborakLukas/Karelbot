# Robot Karel

**Robot Karel** je interaktivní simulace, která umožňuje ovládat robota na mřížce pomocí jednoduchých příkazů. Projekt využívá Three.js pro vizualizaci robota a mřížky, která je podobná šachovnici.

## Funkce
- **Pohyb**: Robot se může pohybovat po mřížce po jednotlivých krocích.
- **Rotace**: Robot se může otáčet doleva nebo doprava.
- **Pokládání položek**: Robot může na mřížku pokládat položky.
- **Vstup příkazů**: Můžeš zadat seznam příkazů, které robot vykoná.
- **Reset**: Lze resetovat pozici robota a odstranit položené položky.

## Příkazy
Robot můžeš ovládat následujícími příkazy:

- `KROK <N>`: Robot se posune o `N` kroků (např. `KROK 3` znamená, že se robot posune o 3 kroky).
- `VLEVOBOK <N>`: Robot se otočí doleva `N`krát (např. `VLEVOBOK 1` znamená otočení doleva jednou).
- `VPRAVOBOK <N>`: Robot se otočí doprava `N`krát (např. `VPRAVOBOK 2` znamená otočení doprava dvakrát).
- `POLOZ <barva>`: Robot položí položku dané barvy (např. `POLOZ red` položí červenou položku).

## Jak spustit

Stačí otevřít soubor `index.html` v libovolném moderním prohlížeči. Tento projekt je čistě na straně klienta, takže není potřeba žádné serverové nastavení. Vše běží v prohlížeči pomocí Three.js pro 3D zobrazení.

## Jak používat

1. **Zadání příkazů**: Do textového pole zadej své příkazy (jeden na každý řádek).
2. **Provedení příkazů**: Klikni na tlačítko "Proveď" a robot bude postupně vykonávat zadané příkazy.
3. **Reset**: Kliknutím na tlačítko "Reset" se robot vrátí na výchozí pozici a všechny položky budou odstraněny.

## Použité technologie
- **HTML5**: Pro strukturu a rozvržení.
- **CSS**: Pro styling.
- **Three.js**: Pro 3D vykreslování robota a mřížky.
- **JavaScript**: Pro logiku a interakci.

## Screenshoty

![image](https://github.com/user-attachments/assets/a72da734-21f5-48c6-958e-1eb8dfc6e018)
![image](https://github.com/user-attachments/assets/2d13a0f1-3754-43ac-9af4-d77a097dd797)


