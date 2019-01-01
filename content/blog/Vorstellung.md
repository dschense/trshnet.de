---
title: "Vorstellung"
date: 2019-01-01
tags: ["Allgemein", "Neuigkeiten", "Trshnet", "Vorstellung"]
draft: false
---

# Vorstellung

Hallo und Willkommen auf dem kleinen aber feinen Blog von Trshnet.

Mein Name is dschense, ich bin 30 Jahre alt und interessiere mich vor allem für den Bereich **Linux**, **Server** und **Open Source**.

Ich beschäftige mich schon seit langer Zeit mit dieser Materie und versuche mir immer mehr Wissen in diesem Bereich anzueigenen.
Angefangen habe ich damit, wie vermutlich viel andere auch, mit dem **Aufsetzen von Linux Maschinen** im eigenen lokalen Netzwerk. Die ersten Schritte habe ich mit **Desktop-Umgebungen**
wie Ubuntu, Fedora, Debian & Co gemacht.<br>
Dabei bin ich immer weiter in die Materie eingestiegen. Anfänglich waren es nur rein optische Anpassungen des Desktops, dann habe ich **#bash** für mich entdeckt und damit experimentiert.<br>
Es entstanden kleine **Scripte** für das Eine oder Andere. Daraus entwickelten sich komplexere Gebilde wie zum Beispiel **automatische Backuproutinen** mit **borg**, **rsync**, **rclone**.

Als mir das alles dann nicht mehr reichte, setzte ich meine ersten eigenen **Webserver** auf.
Über den bekannten **Apache** bin ich recht schnell bei **Nginx** gelandet.
Die ersten Systeme hatte ich abgeschottet in meinem localen Netzwerk am laufen.<br>

Das Tor in die weiten des **WWW's** habe mich mit kleinen Insancen der verschiedensten Anbieter geöffnet.
Mit **netcup.de**, **contabo.de** und **servercow.de** habe ich dann etliche kleine, große, kurzweilige und längere Projekte realisiert.

Da ich ein Freund der "kontrollierten Datengewalt" bin, habe ich mir dann irgendwann Gedanken über **Datensicherheit** gemacht.
Angefangen hat es zuerst mit der **verschlüsselten Ablage von Daten in der Cloud**.<br>
Der nächste Schritt war das betreiben der **eigenen Cloud** im heimischen Netzwerk.<br>
Es folgten dann einige Veränderungen der eigenen Netzwerkstruktur. Die bislang eingesetzte **Fritzbox** wurde als reines Modem dekradiert und eine eigens angeschaffte **PfSense-Firewall** übernahm die neue Aufgabe.

Anfangs wurde die PfSense Firewall tatsächlich als reine Firewall eingesetzt, doch mit der Zeit wurde ich dann neugieriger und testete die mitgelieferten Packete aus, die Pfsense an Board hatte.

So entwickelte sich ein komplexes Netzwerk mit verschiedenen, voneinander abgeschotteten Subnetzen.<br>

Zu diesem Zeitpunkt began ich die Überlegung anzustellen, meine Dienste von zu Hause aus zu betreiben.
So schaffte ich mir einen kleinen **Homeserver** an, der zu einem **Host für virtuelle Maschienen** ausgebaut wurde. Nach diversen Testversuchen bin ich dafür bei **Proxmox** gelandet, das bislang erfolgreich eingesetzt wird.  

So fand ich den Weg in die **Virtualisierung**.

PfSense war mir in diesem Fall wieder einmal eine große Hilfe, denn es blieb dann natürlich nicht bei einem virtuellen Server. Da es mehrere sein sollten, stand ich vor dem Problem der **Bereitstellung**. In diesem Fall entdeckte ich nach anfänglichen Versuchen Nginx als **ReverseProxy** einzusetzten, dass PfSense von Haus aus **HAproxy** packetiert.<br>
Auch **Letsencrypt** in Form eines **ACME Packets** stellte PfSense zur verfügung.

So kam es dazu, dass meine PfSense Firewall durch HAproxy und ACME die Verwaltung und Weiterleitung meiner Dienste übernahm.

In meinem knappen Umriss klingt die Entwicklung vermutlich sehr rassant, allerdings muss ich gestehen, dass der Werdegang sich über viele Jahre hinzog.<br>
Viele Tage und Nächte habe ich getüftel, probiert, getestet.. Viele Fehlschläge, kleine Erfolge.. Unzählige Tutorials, Dokumente, Anleitungen, Videos..<br>

Doch ich bin es noch lange nicht leid. Nur wer probiert und scheitert, kann Fehler finden und es besser machen.

# Projekte

 Ich habe Vieles vor...

## Trshnet.de

### Blog

Der Blog auf Trshnet.de soll für mich als Gedankenstütze, Sprachrohr in die Weiten des WWW's, und evtl. auch als Hilfe für Andere dienen.<br>
Ich werde hier Beiträge über Themen veröffentlichen, die mich selbst interessieren und bewegen.
Es wird keinen regelmäßigen Zeitplan dafür geben. Wenn ich die Zeit und die Lust finde wird Inhalt produziert.

### Status

Die Statusseite status.trshnet.de soll einen Überblick über die von Trshnet angebotenen Dienste geben.<br>
Hier befinde ich mich noch in der Findungsphase. Ich habe mich noch nicht vollends für eine Lösung entschieden, weswegen sich dieser Part natürlich weiterhin dynamisch verändern wird.
