# Úkol: Piškvorky 1/5

Toto je první ze série pěti úkolů, ve kterých si postupně naprogramuješ hru piškvorky.

## Zadání

1. Pokud nemáš na [github.com](https://github.com/) účet, založ si jej.

1. Ve svém účtu vytvoř nový veřejný repozitář pojmenovaný `piskvorky`, do kterého budeš průběžně nahrávat tvoji práci.

1. U sebe na počítači si přichystej novou složku, taky pojmenovanou `piskvorky`, a v ní vytvoř soubor `index.html`.

1. Do `index.html` přidej základní strukturu `html` a mezi značky `<body></body>` vlož nadpis úrovně `h1` s textem `Piškvorky`. Výsledek by měl vypadat takto: ![základ](zadani/zaklad.png)

1. Pomocí příkazu `git init` v terminálu připrav složku v počítači pro práci s gitem.

1. Příkazem `git add .` vyber nově vytvořený html soubor a s `git commit -m "Základní html"` založ první commit.

1. Nahraj první commit na github.

   1. Zavolej `git remote add origin https://github.com/{DOPLN_TVUJ_UCET}/piskvorky.git`

   1. `git branch -M main`

   1. `git push -u origin main`

1. Zkontroluj, že na adrese `https://github.com/{DOPLN_TVUJ_UCET}/piskvorky` je nahraný `index.html`.

1. V nastavení povol GitHub Pages.

   ![nastavení](zadani/nastaveni.png)

   ![GitHub Pages](zadani/github-pages.png)

1. Odkaz na stránku přidej do popisku repozitáře v sekci Website.

   ![website](zadani/website.png)

1. Vedle souboru `index.html` vytvoř i `styly.css` a napoj je do stránky pomocí tagu `<link … />`.

1. Do stejné složky si stáhni obrázek @TODO.

1. Postupnou úpravou html a css uprav stránku do této podoby:

   ![vizuál](zadani/vizual.png)

1. Pro spodní dvě tlačítka použij tag `<a>`. Oběma zatím nastav atribut `href="index.html"`, ať odkazují na úvodní stránku, protože pravidla a hru budeme dělat až v dalších úkolech.

1. Tlačíka by se po najetí myši měly ztmavit.

   ![interakce](zadani/interakce.gif)
