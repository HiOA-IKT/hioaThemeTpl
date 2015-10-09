#Template med HiOA profil

Dette er en template med HiOA profil. Alt av google analytics ol. er blitt fjernet.
CSS, js og bilder er disponert for å fungere ved å laste ned pakken.
All javascript, inkludert rammeverker, kommer i en fil. For å bruke f.eks en annen versjon av jQuery,
fjern den eksisterende fra js/all.js og legg til ønsket versjon.

Alle lenkene fra header og footer er riktige, de lenkene som er i elementene i body er tømme.
Elementene i body er frivillige og kan fjernes.
For å editere elementene eller legge til nye se på kode i:

[www.hioa.no](http://www.hioa.no/)



##COMPONENTER

```
|-- css
|   |-- all.css
|   |-- browsers
|   |   |-- ie5.css
|   |   `-- ie7lte.css
|   |-- ie8.css
|   |-- print.css
|   `-- upgrade_rearrange_fixes.css
|-- img
|   |-- examples
|   |   `-- examplebilde.jpg
|   |-- favicon.ico
|   |-- footermenu_foransatte.png
|   |-- Hioa-Logo-s_h-orig.png
|   |-- HiOA-logo-stor-versjon.png
|   |-- hioa-logo-web_697\303\227120_no.png
|   |-- hioa-meny-knapp_off.png
|   |-- hioa-search-icon.png
|   |-- hioa-sok-knapp_off.png
|   |-- logo_HiOA.png
|   `-- some
|       |-- google-plus-16x16.png
|       |-- icon-facebook-16x16.png
|       |-- icon-flickr-16x16.png
|       |-- icon-instagram-16x16.png
|       |-- icon-linkedin-16x16.png
|       `-- icon-twitter-16x16.png
|-- index.html
|-- js
|   `-- all.js
`-- README.md
```


##INSTALL

Last ned alt og kjør index.html i en nettleser.


##INSTALL MED NPM

Kjør 

```javascript
npm i hioathemetpl --save
```

Da får du node_modules/hioathemetpl/ med alle de nødvendige filer.
