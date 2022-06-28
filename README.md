# Recetas
A recipe website.

#STEPS TO START THIS PROJECT.

step.1: npm init
        -package name: #your project name.
          {leave blank}
        -author: #your name.
        -click YES.
 #generated in package.json which is automattically created
 {
  "name": "recetas",
  "version": "1.0.0",
  "description": "Recipe application",
  "default": "index.html",
  "scripts": {
    "start": "parcel index.html",
    "build": "parcel build index.html"
  },
  "author": "Ankit",
  "license": "ISC",
  "devDependencies": {
    "@parcel/transformer-sass": "^2.6.2",
    "parcel": "^2.6.2"
  },

step.2: npm i parcel@next -D {if not updated  run $npm i parcel@2 -D (for upgraded version of parcel)}.

step.3: npm start
      {if FAILED change "main":"index.html" to "default":"index.html"}.

step.4: npm install

step.5: npm install sass@1.26.10 {for css}.

step.6: npm start.

step.7: copy http://localhost:1234 in your fav. browser.
 and boom u good to go❤.
