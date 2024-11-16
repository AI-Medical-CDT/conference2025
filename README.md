Website for the UKRI AI-Medical CDT Conference 2025

## Tools

- [Quarto](https://quarto.org/)
    - Extensions: [fontawesome](https://github.com/quarto-ext/fontawesome)
- [R](https://www.r-project.org/)
    - Packages: [leaflet](https://cran.r-project.org/web/packages/leaflet/index.html), [leaflet.extras](https://cran.r-project.org/web/packages/leaflet.extras/index.html), [dplyr](https://cran.r-project.org/web/packages/dplyr/index.html) and [htmltools](https://cran.r-project.org/web/packages/htmltools/index.html)

## Repo Organisation

```
📦conference2025
 ┣ 📂.quarto
 ┣ 📂assets
 ┃ ┣ 📂imgs  --> Images Used
 ┃ ┗ 📂styles  --> CSS & SCSS for styling & EJS for layout
 ┣ 📂listings  --> YML for Quarto listings
 ┣ 📂docs  --> Folder for rendered site
 ┣ 📂_extensions
 ┣ 📂_site
 ┣ 📜.gitattributes
 ┣ 📜.gitignore
 ┣ 📜index.qmd  --> Quarto markdown file for main page
 ┣ 📜README.md
 ┣ 📜share-button.js
 ┗ 📜_quarto.yml  --> Quarto config file
```

## Acknowledgements

| Asset  | Source  | License  | Modified  |
|:-|:-|:-|:-:|
| Icons on header, footer and buttons  |  [Font-Awesome](https://github.com/FortAwesome/Font-Awesome) | [Font Awesome Free License](https://fontawesome.com/license/free)  | No  |
| Navbar animation code  | [Ella Kaye's blog](https://github.com/EllaKaye/ellakaye.co.uk)  | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)  | Yes  |
| Header image  | [Wikimedia](https://commons.m.wikimedia.org/wiki/File:Histopathology_of_ulcer_in_acute_cholecystitis.jpg)  | [CC0 1.0 Universal](https://creativecommons.org/publicdomain/zero/1.0/deed.en)  | Yes (cropped)  |
| EJS files for grids  | [level-up-shiny](https://github.com/posit-conf-2024/level-up-shiny)  | [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)  | Yes  |
| Agenda Icons  | [Canva](https://www.canva.com/)  | [Free Content License](https://www.canva.com/policies/content-license-agreement/)  | No  |
| share-button.js  |  [share-button](https://github.com/daviddarnes/share-button) | [MIT License](https://github.com/daviddarnes/share-button?tab=MIT-1-ov-file#readme)  | No  |
| EJS files for agenda  |  [Andrew Heiss' Blog](https://github.com/andrewheiss/ath-quarto) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)  | Yes  |