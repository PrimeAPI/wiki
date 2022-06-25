---
description: Hier erfährst du wie du deinen Core richtig einrichtest
---

# Loslegen

## Installieren

Zunächst musst du die CoreAPI runterladen. Die CoreAPI für BungeeCord und Spigot kann im [Dashboard](https://dash.primeapi.de/downloads) runtergeladen werden. \
Danach muss die .jar-Datei in den plugins ordner verschoben/hochgeladen werden. Nach einem Server-Restart sollten sich die Konfigurations-Datein erstellen haben.

## MySQL-Zugangsdaten

Damit die Plugins ihre Daten speichern können, musst du deine **MySQL Daten** angeben. Wenn du den das Plugin in den plugins Order gezogen hast, und den Server einmal restartet hast, hat sich ein Order  **`plugins/primeplugins`** Order erstellt. Dort findest du eine **`config.yml`**, welche so aussieht:

```
mysql:
  host: localhost:3306
  database: primeplugin
  username: root
  password: password
```

Hier musst du jetzt deine MySQL Daten angeben.

{% hint style="danger" %}
**Wichtig**\
Achte darauf, dass du einen Port hinter dem Host angibst!\
Der standart Port ist `:3306`
{% endhint %}

## Neustarten

Jetzt musst du deinen Server einmal **neustraten**, damit dieser deine Änderungen übernehmen kann. Jetzt bist du good-to-go!

{% hint style="warning" %}
Solltest du ein Cloud-System verwenden, dank daran dein Template zu speichern!
{% endhint %}
