# learning-material-design
Tests with material design w/ npm

>https://material.io/develop/web/docs/getting-started

## 1. Emprar localment Material Design, només css (Igual que Bootstrap)

Instal·lar, 

    npm i material-components-web

I a continuació linkar els fitxers
> Exemple:  `index-local.html`


## Theming amb SASS i MDC

>https://material.io/develop/web/docs/theming


Configurar SASS i Material Design amb `Webpack`, aconseguit seguint el tutorial:
> https://material.io/develop/web/docs/getting-started --> Using MDC Web with Sass and ES2015


### Errors

Mentre seguim el tutorial anterior, ens podem trobar amb un error que s'arregla canviant `webpack-dev-server` per `webpack serve` a `package.json` segons se mostra en [la resposta més votada de stackoverflow](https://stackoverflow.com/questions/59611597/error-cannot-find-module-webpack-cli-bin-config-yargs).

## Incloure components MDC

Ex: Botons. 

1- Instal·lar com a dependència amb:

    npm install @material/button

2- Incloure en el fitxer `app.scss` a la part superior. Per exemple, els botons, 

    @use '@material/button/mdc-button';
    @use '@material/button';

LLavors puc triar el botó que vulgui des de:

- Disseny: https://material.io/components/buttons/
- Implementació: https://material.io/components/buttons/web#text-button

## To-do

- [x] Afegits [Material Icons](https://google.github.io/material-design-icons/) a secció head del html