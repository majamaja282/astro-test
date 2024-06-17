# Astro test for Github codespaces

## Vytvoření repozitáře
1. Klikněte na tlačítko "Fork" na GitHubu
2. Vytvořte repozitář na GitHubu SE STEJNÝM JMÉNEM
3. Klikněte na tlačítko _Code_ a _Codespace_
4. Vytvořte codespace
5. Nainstalování všech extensionů atd.

## Proč se vlastně učíme Astro?

_Názorná ukázka z find and replace_

## Co jsou to komponenty?

Možnost jak využít části HTML a CSS víckrát. Představte si to jako že vytváříme vlastní HTML tagy.

## Vytvoř vlastní komponentu

1. Ve složce `src/components` otevři soubor [`Footer.astro`](./src/components/Footer.astro)
2. Vytoř `<footer>` tag
3. _Ukázka referencování dynamické proměnné_
4. _Ukázka vytvoření prop na vlastní jméno_
5. Jdi na [icones](https://icones.js.org/) a vyber si ikonku pro vlastní sociální síť a zkopíruj jako SVG
6. Ve footeru vytvoř tag do kterého vložíme ikonku (`.social-links>a*2`)
7. Přidej odkaz s ikonkou

## Pojďme stránku udělat naší

1. Otevři si [`globals.css`](./src/globals.css)
2. Uprav barvy dle své libosti
3. Otevři si [`const.ts`](./src/consts.ts) a uprav hodnoty podle sebe
4. Otevři si [`Intro.astro`](./src/pages/Intro.astro) a uprav komponent podle sebe


## Napiš svůj vlastní příspevěk
_ukázka toho jak funguje markdown atd_

## Dostaneme naší stránku ven!

V [`astro.config.mjs`](./astro.config.mjs) změníme:
```diff
- site: 'https://tomaskebrle.github.io',
+ site: 'https://<vase_jmeno_na_githubu>.github.io/',
```

Všechny naše změny uložíme a _pushneme_ na github.