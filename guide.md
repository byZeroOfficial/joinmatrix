
---

title: Wie trete ich der Matrix bei?

ntitle: Die Anleitung

layout: page-two-col

nav: true

parent: guide

permalink: guide/

description: Ein einsteigerfreundlicher Leitfaden für Matrix, die föderierte Chat-Plattform, die dich wirklich respektiert.

---

  

## Wie trete ich der Matrix bei?: Die Grundlagen

  


Willkommen! Diese Website soll ein einsteigerfreundlicher Leitfaden zu Matrix (manchmal [fälschlicherweise](#is-it-matrix-or-element) als Element bezeichnet) sein. Matrix ist ein offenes, föderiertes Kommunikationsprotokoll, das eine Alternative zu verschiedenen zentralisierten, proprietären Plattformen sein will. Aber das sind sehr große Worte, die leider manchmal verwirren. Deshalb soll dieser Leitfaden dir den Chat-Aspekt in etwas einfacheren Worten näher bringen. Wir beginnen mit dem "Warum" und dann mit dem "Wie". Dieser Teil richtet sich an Leute, die Matrix noch nie benutzt haben. Wenn du also auf der Suche nach weiterführenden Informationen bist, sieh dir die Seitenleiste an.

  

## Warum die Matrix?

  

Matrix ist der lang erwartete Mittelweg zwischen One-to-One-Messaging-Plattformen (Facebook Messenger, WhatsApp, iMessages, SMS...) und sozialen/kollaborativen Messaging-Plattformen (Discord, Slack, Telegram...): Es bietet ein angemessenes Maß an Privatsphäre und ermöglicht es dir, mit anderen zu kommunizieren/zusammenzuarbeiten. Die Vorzüge, die Matrix von anderen unterscheidet, lassen sich im Wesentlichen auf zwei Kategorien zusammenfassen:

  

* **Freiheit.** Du kannst selbst entscheiden, wie du die Plattform nutzen willst und wie deine Daten behandelt werden.

* Gespräche können Ende-zu-Ende verschlüsselt werden[^1]. Dies ist standardmäßig für Direkt- und Gruppennachrichten aktiviert[^2].

* Das automatische Sammeln von Daten ist auf ein Minimum reduziert: kein Adressbuchabgleich[^3], keine "Bist du ein Mensch?"-Prüfung nach der Registrierung, Telefonnummern sind optional, sogar E-Mail-Adressen sind optional (auf ausgewählten Homeservern)!

* Du kannst deinen eigenen Server hosten oder dich einem bestehenden öffentlichen Homeserver anschließen, der dir gefällt. In beiden Fällen ist dein Zugang zum Matrix-Netzwerk derselbe[^4]!

* [Bridges](./features/#all-about-bridges) ermöglichen es dir, mit Nutzern auf anderen Plattformen zu chatten, wodurch die sozialen Kosten für den Wechsel zu Matrix minimiert werden!

* Da Matrix ein offenes Protokoll ist, ist es erweiterbar und kann für andere Zwecke als nur zum Chatten verwendet werden. Zum Beispiel: [Helpdesk](https://www.safesupport.chat/), [Social Media](https://minestrix.henri2h.fr/), Zusammenarbeit in Echtzeit...

* **Vertrauen.** Du kannst der Software, die du benutzt, wirklich vertrauen.

* Matrix ist ein offenes Protokoll, und die meisten[^5] seiner [Apps](#what-app-should-i-use) und Server[^6] sind beide Open Source, zu denen du beitragen kannst!

* Matrix ist föderal aufgebaut, genau wie E-Mail: Im Gegensatz zu konventionellen Plattformen, die [zentralisiert](./matrix-vs-al/#centralized-platforms) sind, kann kein einzelnes Unternehmen den gesamten Matrix-Verbund kontrollieren, bei dem die unabhängig voneinander betriebenen Homeserver über ein vereinbartes Protokoll miteinander kommunizieren.

* Außerdem können zwar einzelne Homeserver ausfallen, aber der gesamte Verbund kann nicht offline gehen.

* Du bist herzlich eingeladen, Matrix zu verbessern, indem du neue Apps dafür entwickelst oder (https://spec.matrix.org/unstable/proposals/) Vorschläge einreichst. Du kannst deine Plattform in eine bessere Richtung lenken!

* Matrix wird vom öffentlichen Sektor unterstützt, vor allem von den / der Deutschen ([Gesundheitswesen](https://matrix.org/blog/2021/07/21/germanys-national-healthcare-system-adopts-matrix), [Armee](https://element.io/case-studies/bundeswehr), [Universitäten](https://doc.matrix.tu-dresden.de/en/why/)) sowie von [den Franzosen](https://element.io/case-studies/tchap).

  


Und natürlich hat Matrix alles, was eine moderne Messaging-Plattform bietet: plattformübergreifend, in Echtzeit, Nützlichkeit, etc. Aber das ist nicht der Punkt. Matrix zeigt, dass es **möglich** ist, eine anständige Chat-Plattform zu haben, die dich tatsächlich **respektiert**.

  

Wenn dich diese Gründe nicht überzeugt haben, wie wäre es, Matrix [mit anderen Plattformen](./matrix-vs-al) wie [Discord](./matrix-vs-discord) und [Telegram](./matrix-vs-telegram) zu vergleichen?

  

<div  class="flash">

Die Matrix ist nicht makellos, aber sie wird ständig verbessert! Du kannst auch dem <a href="https://matrix.org/blog/posts">Blog von Matrix.org</a> folgen, um alle Neuigkeiten rund um Matrix zu erfahren!

</div>

  

## Los geht's

  

Bist du bereit, Matrix auszuprobieren? Los geht's:

  

### Heißt es Matrix oder Element?

  


* Matrix ist das Protokoll, das von der in Großbritannien eingetragenen gemeinnützigen Organisation [The Matrix.org Foundation C.I.C.](https://matrix.org/foundation/) entwickelt wurde. Es kann sich auch auf den gesamten Matrix-Verbund beziehen, der alle Nutzer/innen und Räume umfasst.

* Element (früher bekannt als Riot.im) ist das Flaggschiff von Matrix und wurde von der in Großbritannien eingetragenen gemeinnützigen [New Vector Ltd](https://element.io/about) entwickelt. Der Begriff kann sich auch auf kommerzielle Dienstleistungen beziehen, die das Unternehmen anbietet, wie z. B. [Element Matrix Services](https://element.io/matrix-services).

  

[Wie später noch erläutert wird](#welche-app-soll-ich-verwenden), ist Element nur eine der Apps, die auf Matrix zugreifen. Daher ist es korrekt, die Plattform einfach "Matrix" zu nennen. Allerdings hindert dich niemand daran, sie *[The Matrix](https://en.wikipedia.org/wiki/The_Matrix)* zu nennen.

  

### Einen eigenen Homeserver einrichten oder einem bestehenden Homeserver beitreten?

  


Wenn du über die Infrastruktur und die technischen Fähigkeiten verfügst, die erforderlich sind, um ein internetfähiges Programm zu hosten, dann kannst du versuchen, deinen eigenen Homeserver[^6] einzurichten. Die gängigste Homeserver-Implementierung ist [Synapse](https://github.com/matrix-org/synapse/). Wie das geht, steht in der [Installationsanleitung](https://matrix.org/docs/guides/installing-synapse). Es kann möglich sein, einen Homeserver kostenlos zu betreiben [mit Oracle Cloud](https://matrix.org/docs/guides/free-small-matrix-server).

  

Allerdings ist Hosting für viele immer noch unerwünscht. In diesem Fall kannst du...

  

* einem bestehenden Homeserver beitreten, indem du einen aus [unserer öffentlichen Homeserver-Liste](../servers) auswählst, oder

* einen Freund ansprechen, der einen Homeserver hostet, oder

* ein [verwaltetes Homeserver-Hosting](https://matrix.org/hosting/) kaufen.

  

<div  class="flash">

Der "standardmäßige" Matrix homeserver ist <code>matrix.org</code>, welcher von 35% aller Matrix-Benutzer benutzt wird <a  href="https://matrix.org/blog/2020/01/02/on-privacy-versus-freedom">(Schätzungen zufolge im Jahr 2020)</a>. Auch wenn es okay ist, ihn zu verwenden (weil du beispielsweise schnell damit die Matrix austesten kannst), wird dringend empfohlen, einen anderen Homeserver zu wählen (einschließlich der Führung eines eigenen Matrix-Homeservers) für eine langfristige Nutzung, da es dem Geist der Dezentralisierung dient, den das Matrix-Protokoll fördert, und auch, weil <code>matrix.org</code> gelegentlich überlastet ist (obwohl sich die Leistung in letzter Zeit verbessert hat) und hinter Cloudflare liegt (was ein Sicherheitsrisiko darstellt).

</div>

  

### Einen Account erstellen

  

<div  class="flash">

Dieser Teil bezieht sich nicht auf Fälle, in denen ein Homeserver seine eigenen Authentifizierungswerkzeuge verwendet. In solchen Fällen konsultiere bitte die Anweisungen deines Homeservers.

</div>

  


Der Einfachheit halber ist die Anleitung so aufgebaut, dass die Registrierung über einen PC-Browser empfohlen wird, auch wenn viele Server dies über native PC-/Mobile-Apps ermöglichen. Sobald du registriert bist, kannst du dein Konto überall nutzen!

  

1. Wenn du unsere Homeserver-Liste verwendest, die dir einen Link zum internen Element-Client des Homeservers zur Verfügung gestellt hat, kannst du diesen verwenden. Andernfalls kannst du dich über den offiziellen [Element Web Client] (https://app.element.io) anmelden.

2. Klicke auf "Konto erstellen".

3. Überprüfe oben im Registrierungsdialog, ob du dich auf dem richtigen Server registrierst. Wenn nötig, klicke auf "Bearbeiten" und gib die richtige Domain ein (sieh in den Anweisungen deines öffentlichen/privaten/verwalteten Homeservers nach oder in der Spalte "Registrierungsmethode" der [Homeserverliste](../servers)). Sobald du verifiziert bist, **notierst du dir die Domain. ** Du brauchst sie zum Einloggen[^7].

4. Fülle die erforderlichen Informationen aus.

5. Wenn du keine E-Mail-Adresse angegeben hast, bist du schon drin. Andernfalls verifiziere deine E-Mail-Adresse, woraufhin du aufgefordert wirst, dich [einzuloggen](#log-into-an-existing-account).

  

Benutzer werden durch ihre MXID eindeutig identifiziert. Deine MXID ist dein Benutzername plus dein Servername (nicht unbedingt die Domain). Zum Beispiel ist `@byzero:yatrix.org` meine MXID, wobei `byzero` mein Benutzername und `yatrix.org` der Name des Servers ist, auf dem ich mich befinde. **Dies kannst du später nicht mehr ändern**, denn wenn du einen neuen Benutzernamen oder einen anderen Homeserver verwendest, musst du einen neuen Account registrieren (du kannst aber [Daten migrieren](https://ems.element.io/tools/matrix-migration)). Wenn du den Account deaktivierst, kann außerdem niemand anderes mehr diese MXID haben! Du kannst jedoch den Anzeigenamen und deinen Avatar ändern.
  

Denke daran, ein [Schlüssel-Backup einzurichten](#set-up-key-backup)!

  

### Anmeldung bei einem bestehenden Konto

  


Für die meisten Apps:

  

1. Gehe in den Anmeldedialog, wenn nötig.

2. Vergewissere dich, dass du dich beim richtigen Server anmeldest. Dieser wird normalerweise oben im Dialogfeld angezeigt. Wenn nötig, klicke auf "Bearbeiten" und gib die richtige Domain ein (siehe Schritt 3 der Anmeldung).

3. Gib deine Anmeldedaten ein.

  

### Set up key backup

  

Wenn du dich bei einem neuen Gerät anmeldest, wirst du aufgefordert, es mit deinem bestehenden Gerät zu verifizieren (durch Scannen eines QR-Codes oder durch Vergleich von Emojis). Dein neues Gerät ruft dann die Raumschlüssel von deinem bestehenden Gerät ab und kann so deine verschlüsselten Nachrichten lesen. Dies verhindert, dass andere Personen - einschließlich des Betreibers deines Homeservers - verschlüsselte Inhalte lesen können[^1].

  


Für den Zugriff auf verschlüsselte Nachrichten ist jedoch ein Sicherheitsschlüssel erforderlich, wenn:

  

* Du dich vor dieser Anmeldung von *allen* Sitzungen abgemeldet hast, oder

* du nicht in der Lage bist, dich interaktiv von einer anderen Sitzung aus zu verifizieren.

  

Du kannst einen Sicherheitsschlüssel mit den folgenden Schritten einrichten:

  

1. Bei deiner ersten Anmeldung wirst du in einer Sprechblase oben links aufgefordert, "ein sicheres Backup einzurichten". Klicke auf "Weiter". Wenn das nicht der Fall ist, klicke auf deinen Avatar, dann auf "Einstellungen" -> "Sicherheit & Datenschutz" -> "Sicheres Backup" -> klicke auf "Einrichten".

2. "Einen Sicherheitsschlüssel generieren" reicht.

3. Speichere den generierten Sicherheitsschlüssel an einem sicheren Ort (z. B. in einem Passwortmanager).

  

<div  class="flash flash-warn">

Es wird <b>stark empfohlen</b>, diesen Schritt auszuführen, um zu verhindern, dass du versehentlich alle deine verschlüsselten Nachrichten verlierst.

</div>

  

## Sich vertraut machen

  

### Welche App sollte ich verwenden?

  

Es gibt [viele verschiedene Apps](https://matrix.org/clients/), die auf Matrix zugreifen können. Da Matrix ein offenes Protokoll ist, kannst du Matrix sogar in deine eigene App implementieren, wenn du die nötigen Fähigkeiten hast. Aber für die meisten Leute gibt es hier einige Empfehlungen:

  


#### Browser

  

* [Element](https://app.element.io): Das Flaggschiff der App.

* [Element Entwicklungsversion](https://develop.element.io): Element mit aktivierten Lab-Funktionen, aber potenziell instabil.

* [SchildiChat](https://app.schildi.chat/): Element mit aktivierten Lab-Funktionen und einem optionalen Sprechblasen-Layout.

* [Cinny](https://cinny.in/): Matrix im Slack-Stil.

* [Hydrogen](https://hydrogen.element.io/): Schnell und anpassungsfähig an mobile Browser, allerdings um den Preis, dass einige optionale Funktionen fehlen.

  

#### PC und Handy

  

* [Element](https://element.io): Das Flaggschiff der App.

* [SchildiChat](https://schildi.chat/): Element mit aktivierten Lab-Funktionen und einem optionalen Sprechblasen-Layout. Es wird empfohlen, die App auf dem PC zu benutzen, um den vollen Funktionsumfang zu nutzen.

* [FluffyChat](https://fluffychat.im/): "Niedliche" Matrix. Empfohlen für die Nutzung auf dem Handy, um die Leistung zu verbessern.

  

Für diejenigen, die am Rande der Gesellschaft leben: [Commune](https://commune.chat/), [Nheko](https://github.com/Nheko-Reborn/nheko), [Spectral](https://spectral.im), und [Syphon](https://syphon.org/).
  

<div  class="flash">

Für alle PC-Nutzer, die eine bessere Erfahrung mit Element oder SchildiChat machen möchten, kopiere <a  href="../assets/config.json">diese Konfigurationsdatei</a> in dein <a  href="https://github.com/vector-im/element-desktop#user-specified-configjson">Konfigurations-Ordner</a>, wo <code>$NAME</code> entweder "Element" oder "SchildiChat" ist. Die Konfigurationsdatei ermöglicht den Zugriff auf den "Labs" tab in den Einstellungen, ermöglicht benutzerdefinierte Aussehenseinstellungen, <a  href="https://github.com/aaronraimist/element-themes">ein paar benutzerdefinierte Motive</a>, nutzt <a  href="https://dimension.t2bot.io/">Dimension</a> anstatt von Scalar als Integrationsmanager, und lädt bereits einige Homeserver bei der Suche nach Räumen vor.

</div>

  

### Welchen Räumen kann ich beitreten?

  


Jeder Matrix-Homeserver verfügt über ein öffentliches Raumverzeichnis, auf das die Benutzer dieses Homeservers oder, wenn aktiviert, auch die Benutzer anderer Homeserver zugreifen können.

  

* Auf dem PC klickst du für Element und SchildiChat auf die Schaltfläche "Räume erkunden" oben links unter deinem Benutzernamen.

* Für FluffyChat und für Element und SchildiChat auf dem Telefon klickst du auf die Schaltfläche "Suchen".

  

In jedem der oben genannten Fälle kannst du die Raumadresse eingeben, um einem Raum direkt beizutreten, oder du kannst Schlüsselwörter eingeben, um nach Räumen zu suchen[^8]. Das Verzeichnis kann jedoch unintuitiv sein, da es die Räume nach der Anzahl der Mitglieder ordnet[^9]. Der Autor der offiziellen Version des Leitfadens empfiehlt, [diesem Raum](https://matrix.to/#/#offtopic-space:envs.net) (`#offtopic-space:envs.net`) beizutreten, der eine Liste aktiver Off-Topic- oder No-Topic-Diskussionsräume enthält.

  

#### Moment mal, was ist ein/e Space?

  


Discord-Benutzer sind vielleicht mit diesem Format vertraut, aber Spaces sind nicht genau dasselbe wie ein Discord-"Server". Ein Space[^10] ist eine Liste, die andere Räume und Spaces enthalten kann. Er kann verwendet werden, um deine eigenen Räume zu organisieren, oder um alle Räume einer Gemeinschaft zu organisieren. Wenn du einem Space beitrittst, heißt das nicht, dass du auch allen anderen Räumen beitrittst (Räume können jedoch festlegen, dass die Benutzer/innen erst einem Space beitreten müssen), und wenn du einen Space verlässt, heißt das auch nicht, dass du alle Räume verlässt (Standardeinstellung).

  

Auf Element und SchildiChat werden die Räume links in der Raumliste angezeigt. Wenn du einen auswählst, wird deine Raumliste auf DMs mit Mitgliedern des Raums und auf Räume, die dem Raum beigetreten sind, gefiltert. Um Räume zu sehen, denen du noch nicht beigetreten bist, klicke auf die Schaltfläche Erkunden (siehe oben).

  

## Mehr Informationen

  

<div  class="flash flash-warn">

Die Namen deiner Sitzungen sind öffentlich, so dass andere wissen können, welches Betriebssystem du verwendest (früher war es gerätegenau, aber das ist nicht mehr der Fall). Du kannst sie jedoch umbenennen (solange du weißt, wer welcher ist):

<ul>

<li>In Element/SchildiChat, musst du in die Einstellungen gehen, und dann unter "Sicherheit & Datenschutz" die Sitzungen so benennen, wie du möchtest.</li>

<li>In FluffyChat, musst du in die Einstellungen gehen, dann "Geräte". Klicke auf die Sitzungen um sie zu bearbeiten.</li>

</ul>

</div>

  


Wenn du Element oder SchildiChat verwendest, solltest du die [Element-Bedienungsanleitung](https://element.io/user-guide) griffbereit haben, um dich schnell mit der Benutzeroberfläche vertraut zu machen!

  

* [Weitere Funktionen von Matrix](./features): Eine Einführung in weitere Funktionen von Matrix!

* [Öffentliche Homeserver-Liste](../servers)

* [Fragen & Antworten](./qna)

  

## Footnotes

  

[^1]: Nur Textinhalte und Dateianhänge von Nachrichten werden mit dem Signal-Protokoll verschlüsselt. Derzeit verhindert Matrix die Weitergabe von Metadaten nicht, was vor allem an seinem föderalen Charakter liegt. Das wird sich jedoch ändern, wenn Matrix [Pinecone] (https://archive.fosdem.org/2021/schedule/event/matrix_pinecones/) einführt, das p2p-Verbindungen ermöglicht. Wenn alle Teilnehmer/innen einer E2EE-Konversation ihren eigenen Homeserver betreiben (um Dritte auszuschließen), kann das Problem derzeit *abgemildert* werden.

  

[^2]: Ausnahme: Einige Bots unterstützen keine Ende-zu-Ende-verschlüsselte Nachrichtenübermittlung. Wenn du einen leeren privaten Raum erstellst, wirst du außerdem aufgefordert (aber nicht standardmäßig), die Verschlüsselung zu aktivieren.

  

[^3]: Element bietet dir die Möglichkeit, einen "Identitätsserver" zu verwenden (ab Ende 2021 nicht mehr standardmäßig aktiviert) - stell dir das wie ein großes Online-Adressbuch vor. Damit können Nutzer/innen ihre E-Mail-Adressen und ihren Benutzernamen teilen, die von anderen Nutzer/innen manuell nachgeschlagen werden können. Allerdings bedeutet "Adressbuch" hier, dass Matrix die Daten nicht lokal auf deinem Telefon speichert; Homeserver *können* sehen, mit wem du sprichst, da diese Informationen nicht verschlüsselt sind. Es gibt [einen Vorschlag] (https://github.com/matrix-org/matrix-doc/pull/3414), der dies regelt. Siehe auch Fußnote 1.

  

[^4]: Beachte, dass öffentliche Räume bestimmte Server blockieren können - genau wie das Verbot einzelner Nutzer/innen - aufgrund der Verbreitung von inakzeptablen Inhalten (Spam, Hassreden usw.). Wenn du keinen eigenen Homeserver betreibst, solltest du dich nicht auf Homeservern anmelden, die dafür bekannt sind, dass sie solche Inhalte enthalten. Das gilt nicht für Homeserver, die auf [unserer öffentlichen Liste](../servers) aufgeführt sind, da sie auf einen schlechten Ruf hin überprüft werden. Benehmt euch in jedem Fall und denkt an den Menschen.

  

[^5]: Dazu gehören alle Clients und Server, die ein durchschnittlicher Nutzer verwendet.

  

[^6]: [Synapse](https://github.com/matrix-org/synapse/) ist derzeit die einzige stabile Homeserver-Implementierung. Wenn du auf der Kippe stehst, kannst du [Dendrite](https://github.com/matrix-org/dendrite/) und [Conduit](https://conduit.rs/) ausprobieren, die beide irgendwann p2p unterstützen sollen (siehe Fußnote 1).

  

[^7]: In den meisten Fällen entspricht dies dem Serverteil deiner MXID. Die Ausnahmen sind, wenn Homeserver die automatische Erkennung von `.well-known` nicht richtig eingerichtet haben...

  

[^8]: Titel und Beschreibung.

  

[^9]: Das ist kein vernünftiges Maß für die Aktivität. Erstens können Konten inaktiv sein. Zweitens: Wenn ein Raum [Brücken](./features/#all-about-bridges) verwendet, werden diese Konten ebenfalls gezählt, auch wenn ihre Aktivität größtenteils nicht von Matrix ausgeht (du kannst aber trotzdem mit ihnen interagieren).

  

[^10]: Das ist, um genau zu sein, eine spezielle Art von Räumen. Abgesehen davon, dass du Räume (und Spaces) auflisten kannst, anstatt Nachrichten zu senden, gibt es keine Unterschiede zwischen einem Space und einem Raum.
