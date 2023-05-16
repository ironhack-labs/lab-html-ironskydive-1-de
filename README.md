![logo_ironhack_blue 7](https://user-images.githubusercontent.com/23629340/40541063-a07a0a8a-601a-11e8-91b5-2f13e4e6b441.png)

# Geleitete Übung - IronSkydive 💪 - Block- und Inline-Level-Elemente

<br>

## Einführung

In diesem Modul wirst du mit HTML & CSS vertraut gemacht. Beide Technologien bieten dir alle Werkzeuge, die du benötigst, um eine Website zu erstellen. HTML ohne CSS ist hässlich und CSS ohne HTML ist... nun ja, nichts!

Deshalb wirst du während dieses Moduls mehrmals an dieser Übung arbeiten. Unser Ziel ist es, eine grundlegende HTML & CSS-Website zu erstellen, auf der du die verschiedenen Konzepte üben kannst, während du sie lernst.

<br>

## IronSkydive | Die Firmen-Website

Ironhack liebt das Coden, aber wir üben auch gerne Extremsportarten aus. In einer neuen Produktpalette haben wir ein neues Unternehmen namens IronSkydive gegründet. Wir bieten ein komplettes Skydiving-Erlebnis an.

Wir hoffen, dass du uns helfen kannst, unsere Website zu erstellen, da wir damit beschäftigt sind, das Unternehmen zu gründen und sicherzustellen, dass alle unsere Papiere mit den Regeln übereinstimmen. :see_no_evil:

Wie wir bereits erwähnt haben, wirst du während der nächsten paar Lektionen an dieser Übung arbeiten, aber dein Ziel am Ende ist:

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_1f30ebb21258466ca36702d7cdaa0cad.png)

<br>

Du wirst an einem neuen Pen arbeiten, also gehe zu [CodePen](https://codepen.io/) und erstelle jetzt einen neuen Pen. Bist du bereit für den Sprung?

<br>

![](https://media.giphy.com/media/xT5LMrGIfLuDtRSAMg/giphy.gif)

<br>

### Teil 1 - Block-Elemente

In diesem Teil der Übung wirst du mit den Block-Elementen arbeiten, die du gelernt hast. Du hast gesehen, wie uns semantische Block-Elemente dabei helfen, die Komposition unserer Website besser zu verstehen. Beginnen wir damit, die grundlegende HTML-Struktur zu erstellen, die folgendermaßen aussehen wird:

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_8f778c8cd703db596d5bb22dae089716.jpg)

<br>

Später in der Übung werden wir die verschiedenen Abschnitte unterscheiden, die wir haben. Jetzt fügen wir ein paar weitere Block-Elemente innerhalb jedes Elements hinzu.

### Nav

Innerhalb von `<nav>`, erstelle ein `<ul>` -Tag mit drei Elementen:

- Day Structure
- Team
- Schedule

Diese werden unsere Menüoptionen sein.

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_ace26745798b17492d307e0d0c817ea4.png)

<br>

### Header

Hier musst du zwei verschiedene Dinge erstellen:

- Erstelle zuerst ein `<h1>`-Tag mit dem Text "IronSkydive"
- Unter diesem Tag erstelle ein `<h2>`-Tag mit dem Text "Let the trip begin" und schließlich
- Unter diesen Tags erstelle ein `<aside>`-Tag, das ein Zitat enthält.

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_3c0c7f97d3804c728475f52c89f0ec85.png)

<br>

### Sektion 1

Dieser Abschnitt hat einen dunklen Hintergrund, der die gesamte Breite der Website bedeckt. Später wirst du die Farbe für den Hintergrund hinzufügen, also brauchst du dir jetzt keine Sorgen darüber zu machen.

<!-- Um diesen Effekt zu erzielen, werden wir später einen Container innerhalb des Abschnitts erstellen. Dieser Wrapper wird nützlich sein, um eine bestimmte Breite festzulegen und später im CSS alle Inhalte auf dem Bildschirm zu zentrieren. -->

Er wird drei `<article>`-Tags enthalten, um die Informationen unter dem Header hinzuzufügen.

Füge innerhalb jedes `<article>`-Tags ein `<h3>`-Tag für die verschiedenen Titel und einen Absatz für den weißen Text hinzu. Das Ergebnis wird etwa so aussehen:

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_f004e36a2b2bb0dfc02ac008e5d5c97e.png)

<br>

### Sektion 2

Dieser Abschnitt ist dem vorherigen sehr ähnlich. In diesem Fall wird der Abschnitt einen `<h3>`-Titel mit dem Text "How do we structure the day?" und dann ein `<div>` mit vier verschiedenen `<article>`-Tags enthalten.

Innerhalb jedes article-Tags haben wir vorerst ein `<h4>`-Tag mit dem Artikeltitel und ein `<p>`-Tag mit dem Artikelinhalt.

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_c810d2f904e4c4e72ad8b9ed055e4b37.png)

<br>

### Sektion 3

Dieser Fall ist dasselbe wie **Sektion 1** - er hat einen dunklen Hintergrund, und wie in den vorherigen Abschnitten musst du einen `<h3>`-Titel und einen <p> mit einer kurzen Beschreibung hinzufügen.

Dann erstellst du ein `<div>`-Tag und fügst drei leere `<article>`-Tags hinzu, die die Informationen jedes Teammitglieds enthalten werden. Es reicht aus, einen Text anzugeben, der die verschiedenen Artikel anzeigt:

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_4bf21e881db9707b671a812c022db35f.png)

<br>

### Sektion 4

In diesem Abschnitt haben wir eine Tabelle, die den Zeitplan enthält.

Beginnen wir damit, zwei verschiedene `<h3>`-Überschriften mit dem Text hinzuzufügen:

- Schedule
- Schedule a Time Slot

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_cdeeac1a34e5b4f5785ec6f203632b7c.png)

<br>

Füge jetzt eine Tabelle unter dem ersten `<h3>`-Tag hinzu, die den Text "Schedule" enthält. Diese Tabelle wird den IronSkydive-Zeitplan für die Woche enthalten. Das Format der Tabelle ist wie folgt:

| Time          | Monday | Tuesday | Wednesday | Thursday | Friday | Saturday |
| ------------- | ------ | ------- | --------- | -------- | ------ | -------- |
| 9:00 - 11:00  |        |         | X         |          | X      | X        |
| 12:00 - 14:00 |        |         |           |          | X      | X        |
| 15:00 - 17:00 |        |         | X         | X        | X      | X        |

Erstelle die Tabelle und füge den erforderlichen Inhalt hinzu, um dieses Ergebnis zu erzielen:

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_5c089d05a9df991db3784ba81a880835.png)

<br>

Erinnere dich daran, dass du neben dem `<table>`-Tag `<thead>` mit sechs `<th>`-Tags für die Kopfzeilen (sechs Tage, an denen IronSkydive betrieben wird) verwenden solltest. Dann musst du innerhalb des _Tabellenkörpers_ (`<tbody>`) Zeilen mit `<tr>`-Tags definieren. Schließlich solltest du `<td>`-Tags für den Inhalt innerhalb der Zeilen verwenden.

### Footer

Zu guter Letzt muss der Fußbereich nur ein `<section>`Tag enthalten. Innerhalb der `<section>`, musst du mehrere Dinge hinzufügen (in der richtigen Reihenfolge beschrieben):

- `<h5>` mit dem Titel "Contact Information".
- [`<address>`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/address)-Element mit den korrekten Informationen:
  _IronSkydive 33 Rue la Fayette, 75009 Paris, France +33 (0) 619 193 088_
- `<h5>` mit dem Titel "Follow Us".
- `<ul>`-Liste mit drei Elementen:
  - Twitter.
  - Facebook.
  - Instagram.

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_661b4572e673afb0ce5a419ae78b9ce8.png)

<br>

### Teil 2 - Inline Elemente

In der zweiten Iteration unseres Übungsprojekts wirst du mit den Inline-Elementen arbeiten, die du kennengelernt hast. Du hast gesehen, dass wir verschiedene Tags mit verschiedenen Zielen verwenden. Hier ist unsere aktuelle Projektstruktur:

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_8f778c8cd703db596d5bb22dae089716.jpg)

<br>

Du wirst verschiedenen Inline-Elemente zu allen Abschnitten hinzufügen, die wir bereits haben.

### Nav

Das `<nav>`-Tag wird verwendet, um Links auf unserer Website zu umfassen. Im Moment haben wir nur eine Liste von Elementen. Lass uns das ändern, indem wir _Links_ in jedem Listenelement hinzufügen.

Du musst drei verschiedene Links erstellen, die jeweils auf `#structure`, `#team`, und `#schedule` verweisen:

:bulb: Spoiler: _Links_ sind _Anker_-Tags und werden mit dem `<a>`-Tag dargestellt und benötigen das `href`-Attribut. :wink:

```html
<a href="#structure">Day Structure</a>
```

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_53837d5c2b9d5e3c537a87079080151e.png)

<br>

### Header

Der Header des Projekts ist unvollständig. Zunächst musst du ein Logo zum Header hinzufügen. Füge außerdem ein Testimonial-Zitat ein, wo du derzeit einen Fülltext hast.

**Zuerst das Logo.** Füge ein Bild innerhalb des `<h1>` ein, das das folgende Bild lädt:

`https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/ironhack-skydive-logo.png`.

Denke daran, einen beschreibenden Alternativtext hinzuzufügen, nur für den Fall, dass das Bild nicht geladen wird. Eine gute Option wäre "IronSkydive Logo".

Es ist üblich, Zitate in _kursiv_ an verschiedenen Stellen zu finden, deshalb werden wir das tun. Füge das Zitat in kursiv (mit Hilfe von Inline-Elementen) innerhalb des `<aside>`-Elements mit dem Text "Die beste Erfahrung unseres Lebens" hinzu. 
In einer neuen Zeile, diesmal mit einem Block-Element (`<p>`), füge die Namen der Autoren hinzu. Die Namen lauten "Ariel Quiónes & Gonzalo Manrique, Ironhack Founders".

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_0f0563ef2d64bd9a7bdf5d401bca9c16.png)

<br>

### Sektion 1

In der ersten Sektion haben wir drei verschiedene Artikel. Jeder von ihnen hat ein `<h3>`- und ein `<p>`-Tag. Lass uns unter jedem Absatz einen Link hinzufügen. Der Link muss nicht irgendwohin verweisen.

<br>

:::info
Wir können einen Link ohne eine spezifische URL erstellen, indem wir einen Hash im `href`-Attribut angeben:
<br>

```html
<a href="#">Link text</a>
```
:::

<br>

Füge drei Links hinzu, einen in jeder Sektion, in folgender Reihenfolge:

- Learn More
- Watch Video
- Register

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_016b92205b14c5a93d86d324547cf86e.png)

<br>

### Sektion 2

In diesem Abschnitt haben wir vier verschiedene Artikel, die Informationen darüber enthalten, wie ein typischer Tag bei IronSkydive strukturiert ist. Lassen Sie uns jedem Abschnitt einige beschreibende Symbole hinzufügen.

Die verschiedenen Symbole in der richtigen Reihenfolge sind:

- `https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/ironskydive-training.png`
- `https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/ironskydive-get-ready.png`
- `https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/ironskydive-fly.png`
- `https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/ironskydive-jump.png`

Erinnere dich daran, eine alternative beschreibende Text in dem `alt` Attribut hinzuzufügen. Jeder der Abschnitte wird dieses Format mit unterschiedlichen Bildern haben:

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_3aa54eab8bec42f35381b704d5c7b06e.png)

<br>

### Sektion 3

Lass uns die Teaminformationen im Abschnitt hinzufügen. Du solltest drei verschiedene Artikel ohne Informationen haben. In jedem Artikel fügst du den Namen des Teammitglieds in **fettem** Text hinzu (aber das ist etwas, worüber du dir Sorgen machen wirst, wenn wir zur Gestaltung kommen). Du kannst den _Block_ -Level-Tag `<h4>` verwenden, um jeden Namen zu umschließen. Unter dem Namen musst du das Foto des Teammitglieds hinzufügen. Du findest die Bilder hier:

- **Harold Rothstein**, `https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_c18b1c463b80090894237a262dfdfbad.jpg`
- **Susan Phillips**, `https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_a18d6123a7c8e75f7e70a4e59b941093.jpg`
- **Taylor Roberts**, `https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_7104a331530d1b0611da55093b7dc421.jpg`

Vergiss nicht, einen alternativen Text hinzuzufügen, falls das Bild nicht geladen wird. Diese Bilder sind ziemlich groß, aber wir werden uns später in CSS darum kümmern.

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_845dbf46e21d7bb275bdb5b23ff17aa6.gif)

<br>

Um diese Sektion abzuschließen, fügen wir zwischen dem Absatz und den Teammitgliedern eine `<hr>`-Markierung hinzu.

### Sektion 4

_Nichts hinzuzufügen!_!

### Footer

Zuerst wollen wir die Adresse formatieren. Derzeit ist alle Information in einer Zeile. Lass uns `<br>` Tags verwenden, um die verschiedenen Abschnitte der Adresse zu trennen

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_cf1a7806a1a921e018aa46c428d67a17.png)

<br>

Schließlich füge Links zu allen sozialen Netzwerken hinzu, auf denen die Benutzer IronSkydive folgen können. Du kannst leere Links erstellen (mit der Raute im `href`-Attribut) oder Links zu den sozialen Netzwerken hinzufügen. In beiden Fällen muss ein neues Fenster geöffnet werden, wenn die Benutzer auf die Links klicken.

<br>

:::info
:bulb: Verwende das Attribut [`target`](https://html.com/attributes/a-target/)  des Ankers, um einen Link in einem neuen Tab zu öffnen. (das Wort _target_ ist anklickbar, also fühle dich frei, ein wenig zu erkunden - denke daran, dass du nicht alles auswendig lernen musst, sondern wissen musst, wo du die Antworten findest, die du brauchst.)
:::

<br>

![](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_27057afe7732d2b6f26ce69eb00a63ec.png)

<br><br>

:heart: **Viel Spaß beim Coden!**
