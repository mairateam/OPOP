# OPOP: hledanost kotlů podle zemí a kategorií

Klientský report hledanosti (Google Ads Keyword Planner) pro OPOP.

- Stránka: https://mairateam.github.io/OPOP/
- Záložky nahoře = země (Česko, Slovensko, Polsko), pod nimi 4 kategorie kotlů
  (tuhá paliva, pevná paliva, dřevo, pelety) + pohled „Všechny 4 kategorie“.
  Kategorie se nikdy nesčítají dohromady.
- Vybraný pohled je v adrese (např. `#cz/pelety`, `#sk/drevo`, `#pl/all`),
  odkaz jde sdílet.
- Data: měsíční hledanost z Keyword Planneru, čísla jsou zaokrouhlená Googlem.
  Období a datum poslední aktualizace jsou uvedené přímo ve stránce.

Soubor `index.html` je generovaný (data jsou vložená uvnitř), ručně se neupravuje.
Složka `history/` je archiv měsíčních dat od 2023-01 (záloha, stránka ho nečte).
Aktualizace = nové stažení dat z Keyword Planneru, přegenerování stránky a push
do tohoto repa; GitHub Pages ji zveřejní během minuty.
