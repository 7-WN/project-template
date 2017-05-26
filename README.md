# Website template

**Project template voor websites (HTML/CSS/JavaScript) in [Webontwikkeling en Netwerkbeheer aan het Scheppersinstituut Deurne & Antwerpen](http://7wn.be/)**

Je kan deze template gebruiken als startpunt voor al je 'platte' websites die geen back-end nodig hebben. Zo voldoe je moeiteloos aan een aantal belangrijke 'Best Practices' en wordt je text editor geconfigureerd volgens onze afspraken.

## De template installeren

### Vereisten

-   Voor een aantal paketten heb je [nodejs](https://nodejs.org/) nodig. Volg de link en installeer het juiste pakket voor je systeem.
-   Je hebt [JavaScript Standard Style](https://standardjs.com/index.html#install) nodig en [Stylelint](https://stylelint.io/) nodig. Voer het volgende commando in je nodejs command line in:

```sh
npm install -g standard stylelint stylefmt
```

-   Om de standaard configuraties te kunnen gebruiken, voer je dit commando in je nodejs command line in:

```sh
npm install stylelint-order stylelint-config-standard stylelint-config-idiomatic-order
```

-   Je moet een degelijke, moderne text editor gebruiken. Wij gebruiken [Atom](https://atom.io/) met minimaal de volgende plugins of packages geïnstalleerd:
    -   [atom-beautify](https://atom.io/packages/atom-beautify) met `Beautify on Save` geactiveerd voor HTML, JSON en Markdown. Voor  Markdown selecteer je `Remark` als Default Beautifier. Voor JavaScript selecteer je `Disable Beautifying Language`.
    -   [atom-standard-formatter](https://atom.io/packages/standard-formatter) en activeer `Format On Save` in de package settings.
    -   [stylefmt](https://atom.io/packages/stylefmt) en activeer `Format on Save` in de package settings.
    -   [editorconfig](https://atom.io/packages/editorconfig)
    -   [linter](https://atom.io/packages/linter)
    -   [linter-htmlhint](https://atom.io/packages/linter-htmlhint)
    -   [linter-stylelint](https://atom.io/packages/linter-stylelint) vink `Disable when no config file is found` uit en selecteer `Use standard`.
    -   [linter-js-standard](https://atom.io/packages/linter-js-standard)
    -   [standardjs-snippets](https://atom.io/packages/standardjs-snippets)
-   Als je je code onder versiecontrole wil plaatsen, heb je git nodig de makkelijkste manier om git te gebruiken op je systeem is met [Github Desktop.](https://desktop.github.com/)
-   De eenvoudigste manier om je website gratis te publiceren is ook via [Github](http://github.com).

### De template folder installeren op je computer

De eenvoudigste manier om deze code te gebruiken is het zip-bestand downloaden en uitpakken:

1.  Download [het zip-bestand met de laatste versie.](https://github.com/7-WN/website-template/archive/master.zip)
2.  Pak het zip-bestand uit naar je werkmap en geef de uitgepakte map een duidelijke naam.
3.  [TODO: gebruik een npm install script om README om te vormen]
4.  Verwijder het bestand README.md en hernoem README.md.template naar README.md.
5.  Vul je nieuwe README.md bestand aan met de gegevens voor je project.

## De template gebruiken

[TODO]

## Je code onder versiecontrole plaatsen (met git en Github)

[TODO]

## Checklist voor publicatie

[TODO]

## Je website publiceren (via Github)

[TODO]

## Referenties

-   [EditorConfig](http://editorconfig.org/) gebruiken we om de standaard afspraken over indents, character sets, newlines … te forceren.
-   [JS Beautify](https://github.com/beautify-web/js-beautify) gebruiken we voor HTML en inline CSS/JavaScript.
-   [JavaScript Standard Style](https://standardjs.com/) is de moderne manier om JavaScript te schrijven.

## Meewerken aan de template

[TODO]

## Versies

We gebruiken [SemVer](http://semver.org/) voor versienummers. Bekijk de [tags in deze repository](https://github.com/7-WN/website-template/tags) voor de beschikbare versies.

## Changelog

[TODO]

## Auteurs

-   **Lars De Richter** - _[Webontwikkeling & Netwerkbeheer aan het Scheppersinstituut Antwerpen](http://7wn.be/)_

## Licentie

Dit project is beschikbaar onder de MIT licentie - [zie het LICENSE bestand.](LICENSE)

## Dank

[TODO]
