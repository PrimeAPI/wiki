---
description: >-
  Das Einrichten des Discord Bots kann einem schwierig vorkommen. Mit der
  richtigen Anleitung ist es jedoch Kinderleicht
---

# Discord Bot

## Vorbereitung

### Discord Applikation

#### Schritt 1: Erstellen

Begib dich auf und erstelle eine Applikation

![Erstellen einer neuen Applikation](<../.gitbook/assets/r2ikovq (2) (2) (2).png>)

#### Schritt 2: Name vergeben

![Vergabe eines Namens für die Applikation](../.gitbook/assets/theeqnq.png)

#### Schritt 3: Bot erstellen

![Der Applikation einen Bot hinzufügen](<../.gitbook/assets/vs8orlo (1) (1).png>)

#### Schritt 4: Bot-Token kopieren

![](../.gitbook/assets/UYvmAhY.png)

{% hint style="danger" %}
Speichere dir diesen Token ab! Wir brauchen diesen token Später
{% endhint %}

#### Schritt 5: Bot auf deinen Server einladen

![](../.gitbook/assets/3kyftVu.png)

Unter OAuth2 musst du nun bei `SCOPES` `bot` auswählen und unter `BOT PERMISSIONS` musst du `Administartor` auswählen. Nun kopierst du den Link, und öffnest ihn in einem neuen Tab

![](../.gitbook/assets/mvGrFAs.png)

In diesem Fenster nun deinen Server auswählen, auf Weiter klicken und im nächsten Fenster Autorisieren auswählen.

![](../.gitbook/assets/oH2eeHj.png)

Nun kannst du den Bot auf deinem Server betrachten

### Developer Modus

Damit du die Config richtig einstellen kannst, musst du bei deinem Discord den Developer Modus aktivieren.\
In deinen Einstellungen kannst du unter Erweitert den Entwickler-Modus aktivieren.

![](../.gitbook/assets/hE5S7hO.png)

## Einrichtung der Config

### Connection

Unter connection findest du verschiedene Einstellmölichkeiten. \
**key** -  Hier gibst du den Key den du dir vorher kopiert hast an\
**status** - Hier gibst du den OnlineStatus des Bots an. (grüner, gelber oder roter Kreis) (Liste aller möglichen Status: [_JDA Wiki_](https://ci.dv8tion.net/job/JDA/javadoc/net/dv8tion/jda/api/OnlineStatus.html) __ )\
**activity.type** - Hier gibst du die Art der Acitify an. (Spielt..., Guckt.., etc...) (Liste aller möglichen Typs: [_JDA Wiki_](https://ci.dv8tion.net/job/JDA5/javadoc/net/dv8tion/jda/api/entities/Activity.ActivityType.html) )\
**activity.value** - Die aktivität die angezeigt wird nach dem Typ. Bspw. \[Spiel] verifizieren\
**guild** - Guild steht hier für deinen Discord-Server. Hier musst du die ID deiner Guilde angeben. Diese erhälst du indem du Rechtsklick auf dein Server-Icon machst, und dort die ID kopierst

![](<../.gitbook/assets/cbnttim (1) (1).png>)

### Verifikation


**Command**

{% hint style="info" %} Dadurch das die Verarbeitung von SlashCommands nicht dirket ist, kann dies einige Minuten dauern bis er angezeigt wird {% endhint %}

  1 Command ➟ Hier gibts du den Namen des Befehls an, der zur Verifikation genutzt wird.<br>
  2 Info ➟ Die Information zum Verify-Command im Discord<br>
  3 Code ➟ Hier gibts du den Namen an, welchen das Argument für den Verifycode im Discord haben soll<br>
  4 Description ➟ Die Information was man beim 'Code' angegeben werden muss<br>
  5 Groups-Verify-Apply ➟ Soll man bei der Verifikation die 'Verify' Gruppe im Discord erhalten<br>
  6 Groups-Roles-Apply ➟ Soll man Team oder andere Rollen erhalten<br>
  <br>
  Wie muss ich die Gruppen angeben?<br>
  <br>
  `permssion:Rollen-ID`.&#x20;<br>
  <br>
  permission ➟ Bei welcher Ingame Permission soll die Gruppe vergeben werden<br>
  Rollen-ID ➟ Welche Rolle soll dieser Spieler im Discord bekommen.<br><br>
  
  Wie bekomme ich die Rollen-ID herraus?
  
![](../.gitbook/assets/48Ue2db.png)

### Notify & Report

Wenn du Notify antiwierst erhälst du in deinem Discord immer wenn jemand einen **Spieler bannt** eine Nachricht in einen angegebenen Channel.

Wenn du Report aktivierst, wehälst du in deinem Discord immer wenn jemand einen **Spieler reported** einen Nachricht in einen angegebenen Channel.

Du musst bei beidem den Channel als ID angeben. Die ID gibst du genauso wie bei dem Channel von der [Verifikation](discord-bot.md#verifikation) an.
