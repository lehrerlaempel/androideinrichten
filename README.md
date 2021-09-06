# Tutorial: Wie man Android sicher einrichtet (Eine Anleitung)
v 4.2 | Stand: September 2021 | Lizenz: [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/deed.de)

Weitere Anleitungen von uns findet man [hier](https://lehrerlaempel.github.io/anleitungen/)!

# Vorwort
Diese Anleitung soll dabei helfen, Android-Smartphones sicher einzurichten. Mit *sicher* ist dabei einerseits ein so datenschutzfreundliches und schwer anzugreifendes Gerät wie möglich gemeint. Andererseits soll sich diese Anleitung aber auf Maßnahmen beschränken, die durchschnittliche Anwender:innen nicht überfordern und die alltägliche Benutzung des Handys möglichst wenig beeinflussen. Es geht hier also explizit nicht um ein möglichst gehärtetes System für maximalen Schutz, sondern um so viel Sicherheit, wie ohne größere Einschränkungen eben möglich ist.

Es wird übrigens dringend empfohlen, die Anleitung in der hier beschriebenen Reihenfolge zu durchlaufen. Sofern Sie aber bereits vor einem installierten Handy sitzen und nicht alles neu aufsetzen können oder wollen, können Sie sich aber auch selbstverständlich einzelne Kapitel herauspicken. Lieber nur einzelne Maßnahmen dieser Anleitung umsetzen, als keine!

Bevor es losgeht: Diese Anleitung beinhaltet lediglich allgemeine Empfehlungen. Es kann durchaus sein, dass diese Anleitung Fehler enthält oder aufgrund anderer Soft-/Hardware einige Punkte auf Ihrem System anders heißen. Haben Sie Mut, Ihr System selbst einzurichten. Wir möchten Sie mit dieser Anleitung dabei unterstützen. Aber zögern Sie bei Fragen bitte nie, sich im Internet oder bei fachkundigen Personen aus Ihrem Umfeld Hilfe zu holen.

# 1 Welches Gerät kaufen?
Das Angebot an Android-Geräten ist gefühlt fast unendlich groß. Es gibt zahlreiche Hersteller, die meist mehrmals im Jahr neue Geräte vorstellen. Für welches Gerät Sie sich entscheiden, sollten Sie dabei aber nicht nur von persönlichem Geschmack oder Sympathie zu einer bestimmen Marke abhängig machen. 

Sobald der Hersteller eines Smartphones aufhört, dieses mit Updates zu versorgen, wird es quasi unmöglich, einen sicheren Betrieb des Gerätes zu gewährleisten. Ein Gerät ohne die neusten Sicherheitsupdates sollten halbwegs sicherheitsbewusste Nutzer:innen nicht nutzen! Man könnte sagen: Die sicherste Konfiguration bringt nichts, wenn das Betriebssystem als Basis offen steht wie ein Scheunentor. Und genau das tut es: Zu alter Software gibt es diverse offen bekannte Sicherheitslücken. Anders als bei einem Computer ist es bei einem Smartphone aber ein relativ komplexer und fehleranfälliger Prozess, ein alternatives Betriebssystem aufzuspielen. Updates gibt es also für die meisten Nutzer:innen faktisch nur, solange der Hersteller Sie mit solchen versorgt. Danach sind die Geräte quasi unbrauchbar.

Aber woher bekommt man ein Handy, das lange mit Updates versorgt wird? Der einfachste Weg: Kaufen Sie ein Gerät aus dem [Android One Programm](https://www.android.com/one/). Verschiedene Hersteller bieten Ihnen unter diesem Label Geräte unterschiedlichster Preisklassen an, bei denen Sie ab Marktstart des jeweiligen Handys garantiert zwei Jahre Upgrades auf neue Android-Versionen sowie drei Jahre regelmäßig Sicherheitsupdates erhalten. Zudem ist auf den Geräten meist wenig [Bloatware](https://de.wikipedia.org/wiki/Bloatware) installiert, die bei vielen Android-Handys sonst erst wieder umständlich entfernt werden muss.

Sollten Sie sich für ein anders Gerät entscheiden, stellen Sie unbedingt vor dem Kauf in einer Recherche sicher, dass der Hersteller alte Geräte in der von Ihnen angepeilten Preisklasse so lange mit Updates und Upgrades versorgt hat, wie Sie das Gerät nutzen möchten.

# 2 Vorbereitung der Hardware
Vor dem ersten Gerätestart sollten die **Kameras** (mindestens die Frontkamera) mit einer Abdeckung oder einem blickdichtem Aufkleber verdeckt werden. Diese sollten nur bei Bedarf entfernt und danach wieder angebracht werden.

Es empfiehlt sich zum Schutz vor Lauschangriffen durch Sprachassistenten oder Schadsoftware auch, das **Mikrofon** zu deaktivieren, wann immer dieses nicht benötigt wird. Anders als z.B. bei einem Laptop gestaltet sich das bei für durchschnittliche Anwender:innen bei einem Smartphone jedoch relativ schwierig. Ein günstiger und einfacher aber interessanter Ausweg sind kleine Stecker wie z.B. der *CAMeleon Mikrofon Blocker* oder der *Privise Mikrofon Blocker*, die für das Smartphone ein Headset simulieren und dadurch einen guten Grundschutz vor unerwünschtem Horchen bieten. Leider gibt das Gerät dann auch erstmal keinen Ton mehr aus, solange der Stecker im Gerät ist.

Wenn die Stecker für Sie keine Lösung sind, werden Sie wohl erstmal damit leben müssen, ein aktiviertes Mikrofon durch die Gegen zu tragen. Wichtig ist dann vor allem, dass Sie sich dessen bewusst sind und das Gerät vielleicht nicht ausgerechnet mit ins Schlafzimmer oder die nächste Besprechung nehmen. Auch wenn man sich das heute kaum noch vorstellen kann: Ein Smpartphone muss seiner Besitzerin nicht überall hin auf Schritt und Tritt folgen. ;-)

# 3 Android Neugerät Ersteinrichtung
Da viele Smartphone-Hersteller für ihre Geräte eigene Benutzeroberflächen/ Menüstrukturen entwickeln, heißen die folgenden Punkte oft anders und auch die Reihenfolge kann variieren. Im Wesentlichen müssten die Schritte beim ersten Start aber wie folgt heißen:

*(Bitte versuchen Sie wie beschrieben, wenn überhaupt auch tatsächlich erst in Kapitel 6 ein Google-Konto anzulegen bzw. mit dem Gerät zu verknüpfen!)*

- Gerät ohne eingelegte SIM-Karte einschalten und Aufforderung zum Herstellen einer Mobilfunkverbindung überspringen
- Verbindung mit einem WLAN überspringen (Sofern irgendwie möglich, sollten Sie Ihre Geräte immer offline einrichten!)
- Sprache und ggf. Land auswählen
- Zeitzone, Datum und Uhrzeit einstellen

Im Folgenden will Ihr System Ihnen dann noch diverse Features unterjubeln, die primär auf zusätzliche Datenerhebung hinauslaufen. Wir lehnen also möglichst viel ab.

- Deaktivieren von folgenden Google Diensten:
  - Standort verwenden
  - WLAN-Suche zulassen
  - Nutzungs- und Diagnosedaten senden
- Entsperrung mit Gesichtserkennung überspringen (Bietet keine ausreichende Sicherheit, weil es sich teilweise mit wenig Aufwand überlisten lässt oder aber z.B. in Grenzkontrollen oder bei Hausdurchsuchungen in Anwesenheit der Nutzer:innen durch Beamte entsperrt werden kann)
- Displaysperre einrichten, die mindestens aus einem 8-stelligem PIN, besser aus einem Passwort besteht (erst dadurch wird die Geräteverschlüsselung aktiviert)
- Im nächsten Schritt die Teilnahme am Nutzererfahrungsprogramm ablehnen

Wenn das Telefon dann den Startbildschirm anzeigt, sollten als erstes alle nicht benötigten Netzwerkverbindungen und Schnittstellen wie z.B.: Bluetooth, GPS, NFC, deaktiviert werden. Anschließend das Gerät auschalten.
  
*Wird später der PIN oder Passwort vergessen, kann das Handy über Android Recovery (beim Gerätestart wird dazu eine herstellerabhängige Tastenkombination gedrückt) zurückgesetzt werden. Dabei werden jedoch alle Daten auf dem internen Gerätespeicher gelöscht. Achtung: Dies funktioniert oft nicht mehr, sobald ein Google-Konto auf dem Gerät registriert ist, dann werden nach dem Zurücksetzen die Zugangsdaten des alten Google-Kontos abgefragt, bevor das Gerät wieder neu eingerichtet werden kann. Sollten diese LogIn-Daten nicht vorliegen, kann das Handy ohne großen Aufwand nicht weiter benutzt werden! Sie sollten also die PIN sowie die Zugangsdaten für Ihr Google-Konto stets an einem sicheren Ort notieren, so dass Sie diese bei Bedarf nachschlagen können!*

# 4 Der erste Start
Da jeder Smartphone-Hersteller für seine Geräte eigene Benutzeroberflächen/ Menüstrukturen entwickelt, ist es nicht immer einfach die u.a. Einstellungen/ Menüpunkte zu finden. Android bietet jedoch in den Einstellungen eine Textsuche an (Lupen-Symbol). Gibt man hier zum Beispiel das Wort „Standort“ ein, werden alle Menüeinträge die den Suchbegriff „Standort“ enthalten angezeigt und es kann per Klick direkt in das entsprechende Suchergebnis/ Untermenü gesprungen werden.

## 4.1 Updates
Setzen Sie ggf. Ihre SIM-Karte in das Smartphone ein und starten Sie dieses. Stellen Sie dann bei Bedarf eine Verbindung mit einem WLAN Netzwerk her, um Ihre mobilen Daten zu schonen.

Zunächst prüfen wir, ob Systemupdates verfügbar sind. Falls ja, installieren wir diese umgehen (*Einstellungen -> System -> Erweitert -> Systemaktualisierung*).

Anschließend müssen wir die vorinstallierten Apps updaten (*Google-Play-Store öffnen ohne sich bei Google einzuloggen, drei Punkte oben rechts anklicken, Updates auswählen*).

## 4.2 Nicht benötigte Software deinstallieren
Sind alle Updates installiert, können wir damit beginnen, nicht benötigte Apps zu entfernen. Bedenken Sie: Jede App, die nicht auf Ihrem Gerät ist, kann weder Daten über Sie sammeln noch als Einfallstor für Schadsoftware dienen.

Öffenen Sie also *Einstellungen -> Apps & Benachrichtigungen -> Alle Apps anzeigen* und löschen Sie alle Programme, die Sie nicht benötigen. Sollte eine Deinstallation nicht möglich sein, deaktivieren Sie die Apps. Haben Sie Mut zum Löschen. Zur Not kann man fehlende Programme wieder nachinstallieren.

Die folgenden Apps können ohne Probleme deinstalliert bzw. deaktiviert werden: Facebook, Netflix, Gmail, YouTube, Fotos, One Drive, Assistant, Digital Wellbeing, Google, Google News, Files by Google, Kalender, Provider-Apps, Gerätehersteller-Apps, Wetter, Werbung, Office, etc.

Im Endeffekt können Sie alles löschen außer einem Webbrowser, einer Tastatur (z.B. GBoard) den Google Play-Diensten, den Google Playstore, die Playservices und der Einstellungen-App.

Keine Sorge: Im nächsten Kapitel besorgen wir uns datensparsame Alternativen zu den eben gelöschen Apps!

## 4.3 Einstellungen prüfen
Im Endeffekt können Sie jetzt einfach in Ruhe einmal durch alle Einstellungen Ihres Smartphones gehen. Nehmen Sie sich bitte Zeit und klicken Sie sich wirklich durch jedes Menü und Untermenü. Deaktivieren Sie dabei alles, was Sie nicht wirklich benötigen.

Falls es jemand präziser möchte, hier ein paar Vorschläge von uns, was man einstellen könnte:

- In den Standorteinstellungen (Einstellungen -> Standort) folgende Funktionen deaktivieren:
   - Google Standortgenauigkeit verbessern (standortbasierte Funktionen und Dienste)
   - WLAN-Suche und Bluetooth-Suche (standortbasierte Funktionen und Dienste)
- Berechtigung auf App-Ebene überprüfen und nur die tatsächlich notwendigen Berechtigungen gewähren (Einstellungen -> Datenschutz -> Berechtigungsmanager). Lassen Sie sich hier von der Meldung, dass dann ggf. grundlegende Funktionen nicht mehr ordnungsgemäß funktionieren, nicht abschrecken. Zur Not können Sie ja jederzeit einzelne Berechtigungen wieder aktivieren.
- Unter Einstellungen -> Datenschutz -> Werbung die Funktion *Personalisierte Werbung deaktivieren* auswählen
- Hintergrundaktualisierung für alles außer Messenger und Playstores über einen der zwei folgenden Wege deaktivieren:
  - Über *Einstellungen -> Apps & Benachrichtigungen -> Alle Apps anzeigen* für jede einzelne App unter *Erweitert -> Akku -> Hintergrundnutzung einschränken
  - Unter *Einstellungen -> Netzwerk&Internet -> Datensparmodus* den Datensparmodus aktivieren. Dann unter *Uneingeschränkten Zugriff* den Carrier Service, sämtliche verwendeten AppStores sowie die verwendeten Messenger freigeben.
- Unter *Einstellungen -> System -> Sprachen und Eingaben -> Bildschirmtastatur -> Gboard* die Spracheingabe deaktivieren und unter *Erweitert* folgende Optionen deaktivieren: *Nutzungsstatistik, Personalisierung, Spracheingabe für alle verbessern*.
- Um Strom zu sparen bzw. die Akkulaufzeit zu verlängern können dann bei Bedarf unter *Einstellungen -> Display* noch die folgenden drei Einstellungen vorgenommen werden:
  - Dunkles Design aktivieren
  - Die Helligkeit auf das notwendige Minimum reduzieren
  - Unter *Hintergrund* einfarbig schwarz auswählen

## 4.4 SD-Karten
Setzen Sie nun eine ggf. vorhandene Micro-SD Karte in das Gerät ein. das Gerät fragt dann, wie der Speicher eingebunden werden soll (interner Gerätespeicher oder als externer Speicher). Als **interner Gerätespeicher** wird die Micro-SD Karte verschlüsselt, mit dem Nachteil, dass diese nur noch im Smartphone gelesen und beschrieben werden kann. Plug and Play in einem neuen Telefon oder Ihrem Computer funktioniert dann nicht mehr! Als **externer Speicher** eingebunden bleibt die Karte unverschlüsselt und Daten lassen sich auch außerhalb des Smartphones lesen, schreiben und sichern... natürlich auch von Unbefugten, wenn das verschlüsselte Smartphone verloren wird. Entscheiden Sie also sorgfältig, welche Option Ihrem Bedarf am ehesten entspricht.

# 5 Alternative App-Stores
Man kann mit einem Android-Smartphone erstaunlich weit kommen, ohne ein Google-Konto einzurichten. Vermutlich wird in den meisten Fällen sogar kein Google-Konto benötigt. Hier nun zunächst ein Vorschlag, wie man ohne Google-Konto Apps installieren und updaten kann. Mehr zum Google-Play-Store bzw. einem Google-Konto dann im 6. Kapitel.

Auf der Suche nach passenden Apps können Sie sich vor der Installation bei [Exodus Privacy](https://exodus-privacy.eu.org/en/) die Berechtigungen und Tracker von vielen Apps anzeigen lassen. Das Portal [MobilSicher.de](https://mobilsicher.de/themenpakete/appreview) bietet zahlreiche Empfehlungen für datenschutzfreundliche Apps.

In diesem Kapitel finden Sie also zunächst eine Erklärung, wie Sie die zwei von uns empfohlenen AppStores installieren. Unser Tip: Überspringen Sie danach Kapitel 6 zum Google-Konto. Sie finden in Kapitel 7 dann ausreichend App-Emfpehlungen, die eigentlich jeden Bedarf abdecken und die Sie mit Hilfe von F-Droid und Aurora problemlos ohen Google-Konto installieren und nutzen können.

## 5.1 F-Droid
F-Droid ist ein App-Store, der freie bzw. Open-Source-Software anbietet. F-Droid gibt es nicht im Playstore und muss daher [von der offiziellen Webseite](https://f-droid.org) heruntergeladen werden. Mit einem Klick im Downloadmanager oder im Downloads-Ordner auf die heruntergeladene apk-Datei kann man die Installation starten. (Sie müssen dazu die Installation von Apps aus der verwendeten Quelle - z.B. Chrome - zustimmen bzw. nach Aufforderung den Haken bei *Dieser Quelle Vertrauen* setzen.)

Mehr Informationen zu F-Droid und zahlreiche App-Empfehlungen findet man zum Beispiel [im Blog von Mike Kuketz](https://www.kuketz-blog.de/f-droid-und-app-alternativen-android-unter-kontrolle-teil3/) oder auch direkt [auf der Seite des Projektes](https://f-droid.org/de/).

Für die Installation neuer Apps empfiehlt sich F-Droid immer als erste Anlaufstelle.

*Wichtig: Nach der Installation von F-Droid sollten Sie unbedingt Ihrem Browser wieder das Recht entziehen, Apps installieren zu dürfen!*

## 5.2 Aurora Store
Sie wollen eine App aus dem Google-Play-Store installieren, die Sie bei F-Droid nicht finden konnten? Kein Problem!

Installieren Sie sich zunächst über F-Droid den App-Store den [Aurora Store](https://f-droid.org/de/packages/com.aurora.store/). Über diesen kann man ohne Anmeldung (beim Start der App *anonymes Konto* auswählen, alle anderen Einstellunge unverändert lassen) alle kostenlosen Apps aus dem Google-Play-Store herunterladen, installieren und aktualisieren.

*Bitte beachten Sie, dass der Aurora Store über das Tor-Netz nicht genutzt werden kann. Sie erreichen diesen nur über eine "offene" Internetverbindung.*

*Manchmal endet der Versuch, über Aurora eine kostenfreie App herunterzuladen in der Fehlermedlung, dass die App noch nicht bezahlt sei. Erfahrungsgemäß hilft es hier, die Aurora App zu schließen und es noch einmal zu versuchen.*
        
# 6 Das Google-Konto
Meistens benötigt man kein GoogleKonto. Zwar kann man über Aurora keine kostenpflichtigen Apps herunterladen, diese bekommt man aber häufig auch direkt über den Hersteller, so zum Beispiel den beliebten Messernger [Threema](https://shop.threema.ch/).

Wenn man aber zwingend kostenpflichtige Apps aus dem GooglePlaystore benötigt, die sonst nirgendwo angeboten werden, kommt man dann aber nicht mehr um die Einrichtung eines Google-Kontos herum, daher hier auch dazu ein paar Hinweise:

## 6.1 Anlegen
Das einrichten eines Google-Accounts bzw. die Nutzung des Google-Playstores ist meist auch ohne Angabe einer Handynummer möglich. Gehen Sie dazu am besten wie folgt vor:
- Legen Sie sich bei einem Mailanbieter Ihrer Wahl ein Postfach an.
- Öffnen Sie dann [diese Website](https://accounts.google.com/signUpWithoutGmail?hl=de) und tragen Sie hier fiktive Daten sowie eine E-Mail Adresse ein und vergeben Sie ein Passwort.
- Bestätigen Sie den per Mail erhaltenen Code.
- Anschließend muss man ein Geburtsdatum und ein Geschlecht auswählen. Das Feld für eine Mobilfunknummer kann einfach leer gelassen werden.
- Dann die Bedingungen für den Datenschutz prüfen:
  - hier unter weitere Optionen alles abwählen ( Web&App Aktivitäten, Personalisierte Werbung, YouTube Verlauf)
  - Den Nutzungsbedingungen und die Verarbeitung der persönlichen Daten muss für die Erstellung eines Google Kontos zwingend zugestimmt werden
  
## 6.2 Erste Anmeldung im Google-Playstore
Nun öffnen wir den Google-Play-Store auf unserem Handy, klicken auf  und machen dann folgendes:
- E-Mail des Google Konto und dazugehöriges Passwort eingeben.
- Es folgt die Frage nach einer Telefonnummer. Unter weitere Optionen *Nein, meine Telefonnummer nicht hinzufügen* wählen.
- Den Nutzungsbedingungen zustimmen.
- Jetzt die Sicherung in Google Drive deaktivieren.
- Zusätzliche Suchdienste und Browser werden im nächsten Schritt zur Installation angeboten. Das kann übersprungen werden. Zusätzliche Apps kann man sich besser im F-Droid Store laden.

## 6.3 Einstellungen anpassen
Über einen Browser [im Google-Konto anmelden](https://myaccount.google.com/) oder aber auf dem Smartphone unter *Einstellungen -> Konten -> Google -> Google-Konto* die Einstellungen des Google-Kontos öffnen, um die Sammelwut zu bremsen, sofern das eben möglich ist.

Nutzen Sie Ihren gesunden Menschenverstand und klicken Sie sich in Ruhe durch die unterschiedlichen Kategorien. Schränken Sie ein und deaktivieren Sie so viel, wie eben möglich ist. Wichtig ist vor allem, dass am Ende die *Web- & App-Aktivitäten*, der *Standortverlauf* und sämtliche Synchronisierungen deaktiviert sind.
  
## 6.4 Guthaben aufladen
Sofern möglich, sollte auf das Hinterlegen von Zahlungsinformationen wie einer Kreditkarte oder einem PayPal-Konto verzichtet werden, um den Rückschluss auf die Nutzer:in nicht einfacher als nötig zu gestalten. Am besten kauft man sich einfach in einem Supermarkt oder einer Drogerie gegen Barzahlung GooglePlay-Guthaben und lädt dieses im Playstore durch Eingabe des Codes auf sein Konto. Das reicht aus, um Apps kaufen zu können.

# 7 App-Empfehlungen
## 7.1 Weg von Google
Für die meisten meisten Googe-Apps gibt es offene und datenschutzfreundliche Alternativen. Durch die Verwendung dieser Apps kann Tracking, Werbung und sonstige Datensammelwut verhindern, mindestens aber deutlich einschränken und erschweren. Anbei ein paar Empfehlungen:

| Google App | Alternative |
| :------- | -------: |
| Kontakte | [Schlichte Kontakte](https://f-droid.org/de/packages/com.simplemobiletools.contacts.pro/) |
| Kalender | [Schlichter Kalender](https://f-droid.org/de/packages/com.simplemobiletools.calendar.pro/) oder [Etar](https://f-droid.org/de/packages/ws.xsoh.etar/)|
| GoogleMaps | [OsmAnd](https://f-droid.org/de/packages/net.osmand.plus/) |
| Kamera | [OpenCamera](https://f-droid.org/de/packages/net.sourceforge.opencamera) |
| Foto | [Schlichte Gallerie](https://f-droid.org/de/packages/com.simplemobiletools.gallery.pro/)   |
| Google Chrome | [Fennec](https://f-droid.org/de/packages/org.mozilla.fennec_fdroid/) oder [TorBrowser](https://play.google.com/store/apps/details?id=org.torproject.torbrowser)|
| GMail | [K-9 Mail](https://f-droid.org/de/packages/com.fsck.k9/) oder [FairEmail](https://f-droid.org/de/packages/eu.faircode.email)|
| Youtube | [NewPipe](https://f-droid.org/de/packages/org.schabi.newpipe/) |

Außerdem empfehlenswert ist der [LibreOffice und OpenOffice Dokumentenbetrachter](https://f-droid.org/de/packages/at.tomtasche.reader/), der neben gängigen Office-Formaten auch viele Bild- und Videoformate abspielen kann.

Weitere Empfehlungen und freie Alternativen zu kommerziellen Apps finden Sie in der [Empfehlungecke von Mike Kuketz](https://www.kuketz-blog.de/empfehlungsecke/#google-alternativen).

***Nach der Installation einer Alternative nicht vergessen, die ersetzte GoogleApp zu deinstallieren bzw. zu deaktivieren.***

## 7.2 Messenger
Messenger gibt es wie Sand am Meer und jeden Tag kommen drei neue dazu. Einen guten Überblick über die bekanntesten inkl. Bewertung bietet zum Beispiel die [Messenger-Matrix von Mike Kuketz](https://www.messenger-matrix.de/).

Wir wollen uns hier darauf beschränken, Ihnen drei kostenlose, seriöse und Ende-zu-Ende-verschlüsselte Messenger für unterschiedliche Zwecke zu empfehlen:

**Signal** kann [hier](https://signal.org/android/apk/) direkt von der Homepage des Herstellers geladen werden. Sofern Sie über eine Handynummer verfügen und bereit sind, diese mit Ihren Kontakten zu teilen, ist das vermutlich der bequemste und technisch beste moderne sichere Messenger. Signal unterstützt z.B. auch Gruppenchats, Telefonie, Sprachnachrichten und Videochats - und das alles verschlüsselt, ohne dass Sie sich damit befassen müssen.

**Element** können Sie [https://f-droid.org/de/packages/im.vector.app/] direkt über F-Droid installieren. Sie benötigen lediglich ein Konto, dass Sie mit einer Mailadresse [hier](https://app.element.io/#/register) erstellen können. Element ist zwar nicht ganz so komfortabel wie Signal, verfügt aber über ähnliche Funktionen und ist inzwischen an einem Punkt angekommen, wo es auch durchschnittlichen Anwender:innen durchaus zugemutet werden kann. Klarer Vorteil: Sie müssen Ihre Handynummer nicht mit Ihren Kontakten teilen. Selbstverständlich ist auch hier alles Ende-zu-Ende-verschlüsselt.

**Briar** routet sämtlichen Datenverkehr über das Tor-Netz und kommt ganz ohne Nutzerkonten oder persönliche Identifiyer wie z.B. Handynummern, Mailadressen etc. aus. Briar kann man ebenfalls [hier](https://f-droid.org/de/packages/org.briarproject.briar.android/) bequem über F-Droid installieren. Briar kann nur Textnachrichten verschicken, bietet dafür aber das höchstmögliche Maß an Anonymität und Sicherheit und kann zum Beispiel auch offline via Bluethooth von Gerät zu Gerät kommunizieren.

## 7.3 Weitere Empfehlungen 
- [Öffi](https://f-droid.org/de/packages/de.schildbach.oeffi/): Sehr gute App für die Navigation mit öffentlichen Verkehrsmitteln (Verbindungsabfragen, Echtzeitabfahrten, nahegelegene Haltestellen, interaktive Netzpläne usw.)
- [AntennaPod](https://f-droid.org/de/packages/de.danoeh.antennapod/): Podcasts suchen, abonieren, hören, managen usw.
- [NewPipe](https://f-droid.org/de/packages/org.schabi.newpipe/): YouTube-Videos ohne Werbung schauen. Kann Videos auch zum Offline-Gebrauch herunterladen.
- [FOSS Weather](https://f-droid.org/de/packages/de.baumann.weather/): Umfangreiche Wetterangaben u.a. von DWD
- [KeePassDX](https://f-droid.org/de/packages/com.kunzisoft.keepass.libre/): Ein guter Passwortmanager.
- [MuPDF](https://f-droid.org/de/packages/com.artifex.mupdf.mini.app/): Zeigt PDFs an
- [SecScanQR](https://f-droid.org/de/packages/de.t_dankworth.secscanqr/): QR-Code Scanner
- [Odyssey](https://f-droid.org/de/packages/org.gateshipone.odyssey/): Musikplayer
- [Open Camera](https://f-droid.org/de/packages/net.sourceforge.opencamera/): Kamera mit vielen Einstellungsmöglichkeiten
- [AnutoTD](https://f-droid.org/de/packages/ch.logixisland.anuto): Ein lustiges TowerDefense-Spiel (Achtung: Suchgefahr!)

# 8 Unerwünschten Datenverkehr unterdrücken
Als letzter Schritt sollte eine der folgenden Apps installiert werden, die unerwünschten Datenverkehr von Apps und dem Betriebssystem selbst verhindert. Diese simulieren dem Gerät eine VPN-Verbindung und unterdrücken dann unerwünschte Anfragen. 

*(Die folgenden Apps funktionieren also nicht, wenn man einen kommerziellen VPN-Dienst nutzen möchte! Wir empfehlen daher den Verzicht auf ein VPN. Nutzen Sie stattdessen lieber eine der folgenden Apps und verschleiern Sie beim Surfen dann Ihre Herkunft durch das Nutzen des [TorBrowsers](https://play.google.com/store/apps/details?id=org.torproject.torbrowser).)*

- [Blokada](https://f-droid.org/de/packages/org.blokada.fem.fdroid/): Tolle App um Werbung und Tracking zu unterbinden. DIe App ermöglicht es auch sehr einfach, ein alternatives DNS festzulegen. Die Bedienung ist relativ einfach und auch für Einsteiger:innen machbar.
- [NetGuard](https://f-droid.org/de/packages/eu.faircode.netguard/): Die vielleicht beste Firewall für Android, die auch Werbe- und Trackingdomains filtern kann. Kuketz schreibt zur App: *"Die Kombination aus Firewall + Filterlisten ist äußerst mächtig, erfordert allerdings auch ein hohes Maß an Disziplin und Einarbeitungszeit."* Aber die Mühe lohnt sich! Eine Anleitung zur Einrichtung findet man z.B. [hier](https://www.kuketz-blog.de/netguard-firewall-android-unter-kontrolle-teil4/).

 - - -

***Herzlichen Glückwunsch, Sie haben es geschafft!***

***Sofern Sie tatsächlich alle oben beschriebenen Schritte durchgeführt haben, profitieren Sie zukünftig von einem soliden Grundschutz gegen die digitalen Bedrohungen im 21. Jahrhundert und die Misslichkeiten des digitalen Alltags.***

***Ein gut konfiguriertes Gerät ist jedoch kein Allheilmittel! Sie sollten stets umsichtig mit Ihrem Smartphone umgehen und vor allem bei der Installation von Software, dem Einstecken von Wechselmedien und dem Download von Daten auf vertrauenswürdige Quellen achten!***

- - - -

# 9 Langfristige Routinen und Empfehlungen
## 9.1 Software
Bitte beachten Sie, dass diese Grundkonfiguration für einen sicheren Betrieb nicht ausreicht, da Ihr System z.B. durch Betriebssystemupdates immer wieder verändert wird. Auch Sie selbst als Nutzer:in ändern meist im Laufe der Zeit z.B. durch Installationen immer wieder Ihr Gerät.

Sie sollten also alle paar Monate die folgenden Schritte durchführen, um sicherzustellen, dass Ihr System nach wie vor ordentlich konfiguriert ist:
- Berechtigung auf App-Ebene überprüfen und nur die tatsächlich notwendigen Berechtigungen gewähren (Einstellungen -> Datenschutz -> Berechtigungsmanager).
- Apps mit Hilfe der verwendeten App-Stores aktualisieren.
- System updaten (Einstellungen -> System -> Erweitert -> Systemaktualisierung).
- Gespeicherte W-LAN-Netze und Bluetooth Geräte löschen, sofern diese nicht mehr verwendet werden.
- Prüfen, ob nach wie vor nur benötigte Software auf dem Gerät installiert ist.
- Auf dem Smartphone unter *Einstellungen -> Konten -> Google -> Google-Konto* die Einstellungen des Google-Kontos kritisch prüfen.

## 9.2 Laden
Häufig werden Ihnen unterwegs USB-Buchsen zum Laden angeboten - sei es im Mietwagen, in Hotelzimmern, im ÖPNV oder z.B. im Einkaufszentrum. Um in solchen Situationen zu verhindern, dass mehr als nur Strom durch die Leitung geht, sollten Sie entweder nur mit dem eigenen Netzteil via Steckdosen Ihr Gerät aufladen, oder aber durch die überall erhältlichen *USB Data Blocker* sicherstellen, dass zum Laden nur Strom durchs Kabel kann. 

Wichtig: Nutzen Sie auch immer nur Ihre eigenen Ladekabel, da es inzwischen [Keylogger gibt, die in ein Kabel passen](https://www.vice.com/en/article/k789me/omg-cables-keylogger-usbc-lightning).

## 9.3 Regelmäßige Neustarts
Regelmäßige Neustarts Ihres Smartphones (am besten täglich) tragen nicht nur zu einem flüssigen Betrieb des Gerätes bei, sondern machen auch potentiellen Angreifer:innen das Leben sehr schwer. Beim Neustart laden moderne Betriebssysteme nämlich in der Regel nur signierten Softwarecode - eine Hürde, die viel Schadsoftware nicht überwinden kann.

## 9.4 Handy ausschalten
Bevor Sie Ihr Gerät aus den Händen geben (einschließen in einem Schließfach, ablegen in einem Büro, ohne Handy das Haus verlassen, etc.), sollten Sie dieses stets herunterfahren. Alternativ können Sie dieses auch Neustarten, so dass es direkt einsatzfähig ist, wenn Sie es wieder in die Hände nehmen. 

Egal welchen Weg Sie wählen: Wichtig ist, dass Ihr Handy seit dem letzten Hochfahren noch nicht entsperrt wurde, wenn es ein Angreifer in die Hände bekommt. Im laufenden Betrieb nach dem ersten Entsperren des Gerätes sind Smartphones (Android wie iOS) nämlich deutlich leichter anzugreifen.

# 10 Wenn das Smartphone den Besitzer wechseln soll
Sofern es sich vermeiden lässt, sollten verwendete Datenspeicher (In Laptops, Smartphones, etc.) nicht an Dritte weitergegeben werden. Sofern Sie dennoch gezwungen sind, Ihr Smartphone in fremde Hände zu geben, machen Sie vorher am besten Folgendes:
- SIM- und Micro SD-Karte entfernen
- ggf. wichtige Daten (Kontakte, Bilder, Kalenderdaten, E-Mail usw.) auf PC sichern
- ggf. vorhandenes Google-Konto auf dem Gerät löschen
- anschließend das Gerät „Auf Werkseinstellungen“ zurücksetzen (inkl. persönliche Daten löschen)
- danach das Gerät ohne Google-Konto wie oben beschrieben neu einrichten (inkl. neuem und anderem PIN bzw. PW für die Displaysperre)
- Gerätespeicher mit beliebigen Daten (z.B. Videos aus YouTube über NewPipe) füllen
- wird das Gerät jetzt noch einmal „Auf Werkseinstellungen“ zurückgesetzt, sollten alte Kryptoschlüssel gelöscht/ überschrieben worden und somit ein Wiederherstellen der Daten mit „normalen Mitteln“ kaum noch möglich sein

# 11 Nachwort
Für sicherheitsempfindliche Einsatzszenarien sollte ein Google-freies System wie zum Beispiel [LineageOS](https://lineageos.org/) oder besser [GrapheneOS](https://grapheneos.org/) auf dem Smartphone installiert werden. Mehr dazu z.B. [hier](https://www.kuketz-blog.de/grapheneos-das-android-fuer-sicherheits-und-datenschutzfreaks/) und [hier](https://www.kuketz-blog.de/android-ohne-google-take-back-control-teil1/). 

Für alle, die selbst kein Betriebssystem auf einem Smartphone installieren wollen: Es gibt auch Handys, die bereits mit einem Android ohne GoogleDienste verkauft werden, z.B. [hier](https://esolutions.shop/) oder [hier](https://volla.online/de/shop/). Alternativ kann für sensible Einsatzzwecke auch ein speziell vom Hersteller für sicherheitsempfindliche Szenarien entwickeltes Geräte verwendet werden, wie z.B. ein [NitroPhone](https://www.nitrokey.com/de/news/2021/nitrophone-das-sicherste-android-des-planeten), das bereits sicher konfiguriert beim Kunden ankommt. 

Es gibt inzwischen neben iOS und Android auch noch eine dritte Sparte Smartphones, die ganz ohne Technologie von Apple und Google auskommt: Linux-Smartphones. Die Geräte wie z.B. das [PinePhone](https://www.pine64.org/pinephone/) sind nach unserer Einschätzung zwar sehr faszinierend, aber derzeit noch weit davon entfernt, eine verlässliche Alternative für durchschnittliche Anwender:innen zu bieten.

Bleibt noch iOS. Ist ein iPhone nicht sicherer als ein Android? Kurzfassung: Nein. Es hat vermutlich primär historische Gründe, dass diese Fehlannahme so weit verbreitet ist. Fakt ist: Ein iPhone ist keine Lösung für alle, die auf der Suche nach einem möglichst sicheren und datensparsamen Gerät sind. iOS ist nicht sicherer oder schwerer anzugreifen als Andorid. Im Gegenteil: iOS lässt dem Nutzer kaum Möglichkeiten, das System nennenswert zu härten oder auf das Wesentliche zurechtzustutzen. Daher gibt es von uns auch keine Anleitung zu dem Thema.

Dies alles ist jedoch explizit nicht Thema dieses Tutorials. Wir gehen für diese Anleitung davon aus, dass Sie prinzipiell kein Problem mit GoogleDiensten auf Ihrem Smartphone haben und das gekaufte gewöhnliche Smartphone mit dem vorinstallierte Betriebssystem nutzen möchten. Alles weitere dann hoffentlich bald in einer separaten Anleitung zur Installation alternativer Android-Betriebssysteme.

# 12 Das Kleingedruckte
## 12.1 Fehlerteufel
Diese Anleitung wurde von [lehrerlaempel](https://github.com/lehrerlaempel) nach bestem Wissen und Gewissen erstellt. Wir haben die feste Absicht, diese im Laufe der Zeit an Änderungen der erwähnten Software anzupassen und um weitere Aspekte zu ergänzen.

Ihnen sind Fehler aufgefallen? Sie haben Verbesserungs- oder Änderungswünsche? Dann nehmen Sie gerne [Kontakt](https://lehrerlaempel.github.io/anleitungen/) mit uns auf. Wir sind tatsächlich sehr an Ihrer Rückmeldung interessiert!

Wir übernehmen explizit keinerlei Haftung für die hier getroffenen Aussagen oder möglicherweise daraus entstandene Datenverluste oder Schäden am Gerät. Wir haben diese Texte nach bestem Wissen und Gewissen verfasst, sind aber wie alle Menschen fehlbar.

## 12.2 Lizenz
Dieser Text steht unter einer CC-Lizenz, ist also quasi schöpferisches Gemeingut.

Sie dürfen:
- **Teilen** das Material in jedwedem Format oder Medium vervielfältigen und weiterverbreiten
- **Bearbeiten** das Material remixen, verändern und darauf aufbauen

Der Lizenzgeber kann diese Freiheiten nicht widerrufen solange Sie sich an die Lizenzbedingungen halten.

Unter folgenden Bedingungen:
- **Namensnennung** Sie müssen angemessene Urheber- und Rechteangaben machen, einen Link zur Lizenz beifügen und angeben, ob Änderungen vorgenommen wurden. Diese Angaben dürfen in jeder angemessenen Art und Weise gemacht werden, allerdings nicht so, dass der Eindruck entsteht, der Lizenzgeber unterstütze gerade Sie oder Ihre Nutzung besonders.
- **Weitergabe unter gleichen Bedingungen** Wenn Sie das Material remixen, verändern oder anderweitig direkt darauf aufbauen, dürfen Sie Ihre Beiträge nur unter derselben Lizenz wie das Original verbreiten. 
- **Keine weiteren Einschränkungen** Sie dürfen keine zusätzlichen Klauseln oder technische Verfahren einsetzen, die anderen rechtlich irgendetwas untersagen, was die Lizenz erlaubt. 

Hinweise:
- Sie müssen sich nicht an diese Lizenz halten hinsichtlich solcher Teile des Materials, die gemeinfrei sind, oder soweit Ihre Nutzungshandlungen durch Ausnahmen und Schranken des Urheberrechts gedeckt sind.
- Es werden keine Garantien gegeben und auch keine Gewähr geleistet. Die Lizenz verschafft Ihnen möglicherweise nicht alle Erlaubnisse, die Sie für die jeweilige Nutzung brauchen. Es können beispielsweise andere Rechte wie Persönlichkeits- und Datenschutzrechte zu beachten sein, die Ihre Nutzung des Materials entsprechend beschränken.

*Dies war eine allgemeinverständliche Zusammenfassung der [Lizenz](https://creativecommons.org/licenses/by-sa/4.0/legalcode.de), die diese nicht ersetzt.*

## 12.3 Externe Links
Bitte erlauben Sie uns auch noch ein paar Wörter zu den auf dieser Seite gesetzten Links, wie sie von [eRecht24](https://www.e-recht24.de/muster-disclaimer.html) empfohlen werden:

Unser Angebot enthält Links zu externen Websites Dritter, auf deren Inhalte wir keinen Einfluss haben. Deshalb können wir für diese fremden Inhalte auch keine Gewähr übernehmen. Für die Inhalte der verlinkten Seiten ist stets der jeweilige Anbieter oder Betreiber der Seiten verantwortlich. Die verlinkten Seiten wurden zum Zeitpunkt der Verlinkung auf mögliche Rechtsverstöße überprüft. Rechtswidrige Inhalte waren zum Zeitpunkt der Verlinkung nicht erkennbar. Eine permanente inhaltliche Kontrolle der verlinkten Seiten ist jedoch ohne konkrete Anhaltspunkte einer Rechtsverletzung nicht zumutbar. Bei Bekanntwerden von Rechtsverletzungen werden wir derartige Links umgehend entfernen.

# 13 Ausblick/ToDo
Die folgenden Punkte sollen zukünftig noch in dieser Anleitung ergänzt werden:
- BackUp-Möglichkeiten ergänzen
- Kurzfassung voranstellen
- Benötigte Zeit für die einzelnen Schritte ergänzen
