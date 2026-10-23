# Pauls Mini-Adventure

Ein textbasiertes Pixel-Rollenspiel und Spielleiter-Werkzeug in der Welt **Pauluso-Tanien**. Es läuft komplett im Browser – nichts installieren.

**▶ Spielen:** https://paulriegraf-dev.github.io/RPG/

## Gemeinsam spielen (1 Spielleiter + 1–4 Spieler)

**Spielleiter**
1. Die Seite öffnen, „Neues Spiel“ (Gruppe wählen) oder „Spielstand laden“.
2. Rechts im Spielleiter-Bereich unter **Gemeinsam spielen** auf **Raum öffnen** klicken.
3. **Link kopieren** und an die Mitspieler schicken (oder nur den 5-stelligen Code nennen).
4. Unter „Gemeinsam spielen“ siehst du, wer da ist, und kannst jedem einen Helden geben oder ihn entfernen.

**Spieler**
1. Den Link öffnen (oder die Seite öffnen → **Mitspielen (Raum-Code)**).
2. Namen eingeben → **Beitreten** → eigenen Helden wählen.
3. Unten in der Leiste steht, wer dran ist. Du klickst, wenn dein Held dran ist:
   im Kampf nach der Reihenfolge, beim Erkunden über **Ich bin dran** oder dein Bild in der Gruppe.
4. **Mein Held** zeigt Leben, Geist, Techniken und Gepäck. Das Feld unten schickt Nachrichten an alle.
   Freitext unter dem Log geht ans Spiel, wenn du dran bist – sonst als Nachricht an alle.
5. Würfeln: den Würfel anklicken (oder Leertaste).

**Gut zu wissen**
- Das Spiel läuft im Browser des Spielleiters. Sein Fenster muss offen bleiben. Spielstände speichert nur er.
- Lädt der Spielleiter die Seite neu: Spielstand laden – der Raum öffnet sich mit demselben Code wieder, die Spieler verbinden sich von selbst neu.
- Die Browser verbinden sich direkt miteinander (WebRTC). Zum Finden dient der kostenlose Vermittlungsdienst von PeerJS (0.peerjs.com); blockiert ein Netz direkte Verbindungen, laufen die Daten verschlüsselt über dessen Weiterleitung.
- Zum Ausprobieren an einem Rechner: die Seite zweimal öffnen und hinten `?lokal=1` anhängen (z. B. `…/index.html?lokal=1`).
- Am gemeinsamen Bildschirm geht es wie immer ohne Raum.

## Auf eine Webseite legen

Den ganzen Ordner (index.html, musik/, CREDITS.md) auf einen Webspace mit **https** legen – oder als GitHub-Repository mit eingeschaltetem GitHub Pages (Settings → Pages → Branch `main`, Ordner `/`).

## Credits

Siehe [CREDITS.md](CREDITS.md). Privates, nicht-kommerzielles Projekt.
