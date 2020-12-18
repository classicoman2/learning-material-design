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
> https://material.io/develop/web/docs/getting-started, apartat "Using MDC Web with Sass and ES2015
"

### Errors

Mentre seguim el tutorial anterior, ens podem trobar amb un error que s'arregla canviant `webpack-dev-server` per `webpack serve` a `package.json` segons se mostra en [la resposta més votada de stackoverflow](https://stackoverflow.com/questions/59611597/error-cannot-find-module-webpack-cli-bin-config-yargs).