## get the localised format `YYYY-mm-dd H:i:s`
this is suitable for psql and mysql.
shows the current time exactly as you see it on you system.
```js
let date = new Date();
date.toLocaleString('sv-SE');
```
