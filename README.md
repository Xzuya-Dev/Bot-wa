### NOTE 

sc ini hanyalah hasil recode dari sc Naze
Xzuya hanya menghilangkat bug, memperbagus & menyeting banyak hal
agar tidak terjadi error

## HOW TO CONNECT TO MONGODB WHEN RUN IN HEROKU

* Create account and database in mongodb atlas [`watch here`](https://youtu.be/w1iMJS0ib-w)
* when you already have a database, you just need to take mongourl
* Put mongourl in Procfile `web: node . --db 'mongourl'`
* Example `web: node . -- db 'Your Mongo URI'`

### installation in termux
``` bash
pkg update && pkg upgrade -y
pkg install node
pkg install git
cd Xzuya-Dev/Bot-Wa
$node .
```

## ❗ Warning
Bot WhatsApp masih dalam tahap pengembangan, jadi ada beberapa bug
Koneksi WhatsApp (BETA, tidak berfungsi dengan sempurna)


Editing Number Owner in [`config.js`](https://github.com/nazedev/Bot-Wa/blob/main/config.js)

### THANKS TO ###
• Naze ( Penyedia Base )
