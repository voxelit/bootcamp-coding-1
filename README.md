# www.voxel.it

Durante il primo incontro di coding abbiamo messo in piedi un progetto Nuxt.

Per farlo abbiamo installato:
- **Visual Studio Code**: un editor per scrivere codice che ha un terminale integrato
- **NodeJS**: ci serve per far funzionare il progetto, ma noi non lo useremo direttamente
> Per verificare che node sia installato abbiamo eseguito nel terminale il comando `node -v`

Abbiamo installato `yarn`, eseguendo nel terminale `npm install -g yarn`. Yarn è uno strumento per installare librerie e dipendenze esterne che ci serviranno nel progetto.

Abbiamo creato la Nuxt app, eseguendo nel terminale il comando: `yarn create nuxt-app www.voxel.it` e abbiamo avviato il progetto con il comando `yarn dev`

Infine abbiamo aggiunto Bulma, una cassetta degli attrezzi che mette a disposizione degli strumenti per costruire una pagina web, fornendo degli stili CSS carini, già pronti per essere utilizzati 😊

## Link per approfondire

- Documentazione di NuxtJS: https://nuxtjs.org
- Sito di Bulma: https://bulma.io
- Nuxt Awesome: https://github.com/nuxt-community/awesome-nuxt
- Corso online su NuxtJS: https://www.udemy.com/course/nuxtjs-vuejs-on-steroids/

## Comandi

``` bash
# per installare dipendenze
$ yarn install

# per avviare progetto sul proprio computer, visibile su localhost:3000
$ yarn dev

# build for production and launch server
$ yarn build
$ yarn start

# generate static project
$ yarn generate
```
