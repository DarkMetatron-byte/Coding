# UNGEBRANNT — Game Design Document

> **Status:** Designphase abgeschlossen bis zur Entscheidungsvorlage. Noch kein Prototyp.
> **Genre:** Top-down Action-Adventure mit systemischen Rätseln
> **Arbeitstitel:** *Ungebrannt*

---

## 1. Die Idee in drei Sätzen

Du spielst **Rill**, eine Figur aus ungebranntem Ton, in einer Welt, die noch nicht fertig geformt ist. Rill baut den eigenen Körper aus dem, was die Welt hergibt: Arme aus Stein, Beine aus Holz, ein Kopf aus Glas. Jedes Material verleiht Fähigkeiten, ist zugleich Lebensenergie und fehlt der Welt, sobald Rill es genommen hat.

Der Gegenspieler ist die **Glasur**, eine lebende Keramikschicht, die alles überzieht und für immer erstarren lässt. Rill muss die Glasur aufbrechen. Dafür braucht Rill Material, und wer zu gierig nimmt, macht die Welt für die Glasur anfällig.

---

## 2. Designsäulen

Jede spätere Entscheidung wird an diesen drei Säulen gemessen. Ein Feature, das keine davon stärkt, fliegt raus.

| # | Säule | Bedeutung für das Spiel |
|---|-------|-------------------------|
| 1 | **Du bist, was du nimmst** | Körper, Lebensenergie, Ausrüstung und Fähigkeiten sind *ein einziges System*. Es gibt kein separates Inventar, keine Lebensleiste und keine Erfahrungspunkte. |
| 2 | **Weich gegen hart** | Rill bewegt sich ständig zwischen *formbar, aber schwach* (nass) und *stark, aber spröde* (trocken). Beide Zustände haben Vor- und Nachteile, keiner ist „richtig“. |
| 3 | **Die Welt merkt es sich** | Was Rill nimmt, fehlt sichtbar. Was Rill zurückgibt, wächst nach. Die Landschaft dient als Spielstand. |

**Warum diese Säulen?** Viele Action-Adventures stapeln voneinander getrennte Systeme: HP, Ausdauer, Inventar, Skilltree und Moral-Score. Spielerinnen und Spieler müssen sie einzeln lernen, und sie beeinflussen sich kaum. *Ungebrannt* bündelt sie in **zwei verzahnten Größen** (Material und Feuchte) und **einer Weltgröße** (Gefüge). So entsteht Tiefe aus Wechselwirkung statt aus Menge.

---

## 3. Die Welt: das Lettenland

### 3.1 Prämisse

Das **Lettenland** (von *Letten*, altes Wort für Lehm/Ton) wurde von einer uralten Kraft geformt, die man nur „die Hände“ nennt. Die Hände haben ihr Werk **nie vollendet**. Flüsse verlagern sich nach jedem Regen, Hügel sacken ab, und Lebewesen wachsen, zerfallen und formen sich neu. Veränderung ist hier Naturgesetz.

Nicht alle ertrugen das. Ein Teil der Bewohner ließ sich **brennen**: Sie wurden hart, dauerhaft und unveränderlich. Diese **Gebrannten** leben in Städten aus Kachel und Ziegel. Sie zerfallen nicht mehr, können aber auch nicht mehr heilen. Ein Sprung bleibt für immer.

Der Porzellangelehrte **Kantor Vell** ging einen Schritt weiter. Er erschuf die **Glasur**, einen lebenden, glänzenden Überzug, der sich selbst ausbreitet und alles, was er berührt, versiegelt. Unter der Glasur stirbt nichts mehr, aber es lebt auch nichts mehr. Regen perlt ab, die Böden trocknen aus, und die Flüsse versiegen.

### 3.2 Regionen

Jede Region führt **genau ein neues Material** und **eine neue Form** ein (siehe Abschnitt 5). Das ist bewusstes Pacing gegen Überforderung.

| Region | Charakter | Neues Material | Neue Form | Glasur-Bedrohung |
|---|---|---|---|---|
| **Die Schwemme** | Überflutete Auen, Treibholz, Schlammbänke | Holz | *Kugel* | Glasurmilben besiedeln die Weiden |
| **Moosgrund** | Dunkler Wurzelwald, ständig feucht | Moos | *Platte* | Ein glasierter Wurzelstock schnürt den Wald ab |
| **Die Salzpfanne** | Ausgetrockneter See, gleißende Sonne | Salz | *Schale* | Glasurdünen wandern über die Ebene |
| **Kachelhof** | Stadt der Gebrannten, Ziegel und Mörtel | Stein | — (Siegel statt Form) | Politischer Konflikt, Glasur als „Schutz“ verkauft |
| **Der Ofen** | Vulkanberg, Vells Werkstatt | Glas | — | Quelle der Glasur, Endgebiet |

Lehm hat Rill von Anfang an.

**Warum diese Reihenfolge?** Holz (Schwimmen, Reichweite) und Moos (Klettern, Heilung) sind *verzeihende* Materialien, mit denen man das System lernt. Salz bringt die erste echte Wechselwirkung mit der Feuchte. Stein und Glas sind die extremsten Materialien (schwer, zerbrechlich) und kommen erst, wenn das Grundverständnis sitzt. Thematisch rückt Rill zugleich immer näher an das Harte, Gebrannte heran, also an Vells Welt.

---

## 4. Figuren

### Rill: die Hauptfigur
Eine kleine Figur aus dem letzten weichen Ton des Flussbetts, heimlich geformt von Schlick. Rill ist **unfertig**: ohne feste Gestalt, ohne festes Material und ohne feste Rolle. Rill spricht kaum und drückt sich über Körpersprache aus. Weil sich der Körper ständig verändert, *sieht* man den Spielfortschritt direkt an der Figur.

> **Designgrund:** Eine Hauptfigur ohne feste Form macht die Kernmechanik zur Identität der Figur. Das Thema („Unfertig sein ist keine Schwäche“) wird nicht erzählt, sondern gespielt.

### Scherbling: der Begleiter
Eine sprechende Scherbe eines uralten Kruges, die auf Rills Schulter sitzt. Scherbling ist geschwätzig, ängstlich (noch kaputter zu werden ist ein Albtraum) und erinnert sich bruchstückhaft an die Vergangenheit, im wahrsten Sinne des Wortes.
**Funktion im Spiel:** Tutorial-Stimme, Hinweissystem (nur auf Nachfrage), Erklärung von Materialien und Lore-Vermittler.
**Bogen:** Scherbling will wieder ganz sein. Am Ende steht die Wahl, sich als Teil von Rills Kopf einbauen zu lassen und damit selbst „unfertig“ zu werden.

### Schlick: die Mentorin
Ein Flussgeist, dem das Wasser ausgeht. Schlick erscheint als rissiges, halb ausgetrocknetes Gesicht im Flussbett. Mit jeder befreiten Region kehrt etwas Wasser zurück, und Schlick wird lebendiger, sichtbarer und gesprächiger.
**Funktion:** Questgeberin. Ihr Zustand macht den Weltfortschritt sichtbar.

### Kantor Vell: der Antagonist
Ein Gelehrter aus feinstem Porzellan. Einst war er selbst aus Ton. Sein Kind, ebenfalls eine Tonfigur, löste sich in einer Flut auf. Seitdem verfolgt ihn ein einziger Gedanke: **Nichts soll je wieder verloren gehen.** Die Glasur ist für ihn kein Werkzeug der Zerstörung, sondern eines der *Bewahrung*.
**Warum dieser Antagonist?** Vells Motiv ist nachvollziehbar und spiegelt die Spielmechanik: Der Feuchte-Zustand *spröde* macht Rill stärker, aber zerbrechlicher. Spielerinnen und Spieler erleben Vells Versuchung also im eigenen Kampfsystem.

### Ziegelvogt Harth: die Grauzone
Oberhaupt von Kachelhof. Pragmatisch, misstrauisch und gebrannt. Die Gebrannten fürchten Frost und Regen, weil sie Risse bekommen und nicht heilen können. Vell verspricht ihnen, dass die Glasur sie schützt. Harth lässt sich überzeugen, wenn Rill zeigt, dass Heilung möglich ist (Reparatur von Gebrannten mit Material, siehe 5.5).

### Tiefgang: der Fährmann
Eine Steinfigur, die auf dem Grund des großen Flusses lebt, weil Stein eben sinkt. Tiefgang ist ruhig, langsam und weise und lehrt Rill, dass Schwere kein Makel ist. Als Nebenfigur bereitet er auf die Stein-Mechanik vor.

---

## 5. Kernmechaniken

### 5.1 Der Materialkörper (Säule 1)

Rills Körper besteht aus **vier Segmenten**:

- **Kopf**: Wahrnehmung, Sondersinn
- **Arme**: Angriff und Interaktion
- **Rumpf**: Schutz, passive Eigenschaft, **Gefäß**
- **Beine**: Bewegung

Jedes Segment ist aus einem Material. Rill nimmt Material auf, indem Rill eine Quelle in der Welt berührt und hält (Baumstamm, Felsen, Moospolster …). Das Material ersetzt dann ein gewähltes Segment. Das alte Material fällt zu Boden und kann zurückgegeben werden (siehe 5.4).

#### Materialtabelle

| Material | Kopf | Arme | Rumpf | Beine | Schwäche |
|---|---|---|---|---|---|
| **Lehm** (Start) | — | Lehmklumpen werfen (Fernkampf, *kostet eigene Masse*) | Langsame Selbstheilung, wenn feucht | Durch enge Spalten quetschen (wenn nass) | Unspezifisch, weich |
| **Holz** | *Jahresringe*: zeigt Spuren und Fährten der Vergangenheit | Lange Reichweite, schnell; anzündbar für Feuerschaden | Auftrieb; Wind trägt weiter | Schwimmen, höhere Sprünge | Brennt |
| **Moos** | *Tarnung*: Gegner bemerken Rill später | Ranken: Gegenstände und Gegner heranziehen | Wächst nach: heilt beschädigte Segmente | An Wänden haften (Klettern) | Verdorrt bei Trockenheit |
| **Salz** | Zeigt Feuchte-Stufe von Gegnern und Oberflächen | Treffer entziehen Gegnern Feuchte | Zieht Feuchte aus der Luft | Hinterlässt Salzspur, die Wasserwesen meiden | Löst sich in Wasser auf |
| **Stein** | Rammstoß | Langsame, schwere Schläge, Erschütterung, Blocken | Hohe Rüstung, kein Rückstoß | Sinkt (Fluss- und Seegrund begehbar), drückt Platten, Stampfen | Schwer, langsam, sinkt |
| **Glas** | Sieht Lichtwege und Glasurkerne (Schwachstellen) | Schnitte, höchster Schaden | Leitet und speichert Licht (Lichträtsel) | Hitzefest: über Glut laufen | Zerspringt beim Blocken und unter Schlägen |

**Warum vier Segmente und sechs Materialien?** 6⁴ = 1.296 mögliche Kombinationen, aber jedes Segment hat eine *klar abgegrenzte Aufgabe*. Spielerinnen und Spieler müssen also nicht 1.296 Builds verstehen, sondern pro Situation nur die Frage beantworten: „Was brauche ich gerade? Bewegung, Angriff, Schutz oder Wahrnehmung?“ Jedes Material hat eine *Umweltschwäche* statt eines Zahlenmalus. Das macht Fehler nachvollziehbar („Ich bin mit Salzbeinen in den Fluss gelaufen“) statt frustrierend.

### 5.2 Material ist Leben (keine Lebensleiste)

Treffer schlagen **Material ab**. Jedes Segment hat drei Zustände:

```
  heil  ──Treffer──▶  angeschlagen  ──Treffer──▶  abgefallen
```

- **Angeschlagen**: sichtbare Risse, Funktion bleibt erhalten.
- **Abgefallen**: Das Segment liegt als Brocken neben Rill. **Die Funktion fehlt**, bis es wieder aufgehoben oder ersetzt wird.
  - Keine Beine: Rill kriecht langsam.
  - Keine Arme: Nur noch Körperstöße sind möglich.
  - Kein Kopf: Das Sichtfeld schrumpft, Scherbling verstummt.
- **Rumpf abgefallen**: Rill zerfällt zu einem Lehmhaufen und erwacht an der letzten **Quelle** (Checkpoint). Die Materialien bleiben am Ort des Zerfalls liegen.

**Fernkampf kostet Körper:** Lehmklumpen werfen nimmt Masse von den Armen. Geworfene Klumpen bleiben liegen und können wieder eingesammelt werden. Fernkampf ist also immer eine Investition.

**Notform:** Fehlt ein Segment und ist kein Material in der Nähe, kann Rill es an einer Quelle aus Grundlehm neu formen. Mitten im Kampf geht das gegen einen hohen Feuchte-Preis.

**Warum keine Lebensleiste?**
1. **Lesbarkeit:** Den eigenen Zustand sieht man direkt an der Figur, nicht in einer Ecke des Bildschirms.
2. **Schaden verändert das Spiel und nicht nur eine Zahl.** Wer die Beine verliert, muss anders spielen. Das erzeugt Geschichten („Ich habe den Boss ohne Arme mit Rammstößen besiegt“).
3. **Risiko und Belohnung im Kampf:** Abgefallene Segmente liegen in der Arena. Holt man sie sich zurück, mitten zwischen den Gegnern?

**Risiko: Todesspirale.** Weniger Körper heißt schwächer, und schwächer heißt noch weniger Körper. *Gegenmaßnahmen:* Abgefallene Teile landen immer in Reichweite. Das Aufheben ist schnell und unterbricht Angriffe. Gegner priorisieren Rill nicht stärker, wenn Rill geschwächt ist. Notform als letzte Rettung.

### 5.3 Das Feuchte-Spektrum (Säule 2)

Statt einer Ausdauerleiste hat Rill eine **Feuchte-Stufe**. Die Begriffe stammen aus der echten Töpferei:

| Stufe | Bewegung | Angriff | Schaden erhalten | Formen möglich? | Besonderheit |
|---|---|---|---|---|---|
| **Schlamm** | sehr langsam | sehr schwach | Treffer *verformen* statt abzuschlagen (kaum Materialverlust) | ja, kostenlos | Durch Spalten quetschen |
| **Feucht** | langsam | schwach | reduziert | ja | — |
| **Lederhart** | normal | normal | normal | ja (kostet Feuchte) | Ausgewogener Zustand |
| **Trocken** | schnell | stark | erhöht | **nein** | — |
| **Spröde** | sehr schnell | sehr stark, Treffer erschüttern | **doppelt**, Segmente brechen sofort ab | **nein** | Glasbruch-Gefahr |

**Was die Feuchte senkt:** Ausweichen, Sprinten, schwere Angriffe, Sonne, Feuer, Glut.
**Was die Feuchte erhöht:** Wasser, Regen, Pfützen, Moos-Rumpf, Salz-Rumpf (langsam aus der Luft).

**Warum ein Spektrum statt einer Ausdauerleiste?**
- Eine Ausdauerleiste hat nur *eine* gute Richtung (voll). Das Feuchte-Spektrum hat **zwei Pole mit eigenen Stärken**. Aggressive Spielweise trocknet Rill aus und macht Rill tödlicher, aber zerbrechlicher. Defensive Spielweise hält Rill nass, sicher und formbar, aber schwach.
- **Die Umgebung wird taktisch.** Ein Kampf neben einem Fluss spielt sich anders als einer in der Salzpfanne. Positionierung bekommt eine Bedeutung jenseits von „Deckung“.
- **„Trocken kann nicht geformt werden“** ist echte Tonlogik und verbindet Kampf und Rätsel. Wer eine Form braucht, muss erst feucht werden.
- **Thematische Spiegelung:** *Spröde* ist ein Vorgeschmack auf das Gebranntsein, also Vells Versprechen von Stärke um den Preis der Starrheit.

### 5.4 Das Gefäß

Rills Rumpf ist hohl, schließlich ist Rill ein Tongefäß. Er kann **eine Füllung** tragen:

- **Wasser**: ausgießen (Fläche nässen, Feuer löschen, Gegner abschrecken) oder selbst trinken (Feuchte +2 Stufen)
- **Glut**: ausschütten (Fläche entzünden, Gegner erhitzen) oder selbst aufnehmen (Feuchte −2 Stufen, sofort kampfbereit)
- **Licht** (nur mit Glas-Rumpf): speichern und an anderer Stelle abgeben (Rätsel)

**Warum?** Das Gefäß gibt Spielerinnen und Spielern einen **aktiven Hebel auf die eigene Feuchte**. Ohne ihn wäre die Feuchte reine Umweltverwaltung. Gleichzeitig ist es das Werkzeug für die wichtigste Kampfkombination (siehe 6.2).

### 5.5 Formen

Ab der ersten Region lernt Rill Körperformen. Formwechsel geht nur bei Feuchte *lederhart* oder nasser.

| Form | Wirkung | Typische Nutzung |
|---|---|---|
| **Kugel** | Rollen: schnell, Rampen hinauf, Schwung | Strecken überwinden, Gegner umstoßen |
| **Platte** | Flach: unter Spalten hindurch, mit Holz-Rumpf über Wasser gleiten | Durchgänge, Schleichen |
| **Schale** | Große Öffnung: Regen sammeln, Glut auffangen, doppelte Gefäß-Menge | Ressourcen transportieren, Feuchte gezielt steuern |

Formen sind **Werkzeuge, keine Kampfstile**. Sie werden für Durchquerung und Rätsel eingesetzt. Im Kampf dienen sie eher als Fluchtoption.

### 5.6 Reparieren

Rill kann **Gebrannte reparieren**, indem Rill Material aus dem eigenen Körper in ihre Risse drückt. Das kostet ein Segment. Diese Handlung trägt die Geschichte in Kachelhof (Harth überzeugen) und erzählt das Thema: Etwas von sich selbst geben, damit andere heilen.

---

## 6. Kampf

### 6.1 Grundsteuerung

| Aktion | Wirkung |
|---|---|
| Leichter Angriff | Abhängig vom Arm-Material |
| Schwerer Angriff | Abhängig vom Arm-Material, kostet Feuchte |
| Ausweichen | Kurzer Sprung, kostet Feuchte |
| Werfen | Lehmklumpen (kostet Masse), Fernkampf |
| Aufnehmen (halten) | Material aus der Welt oder vom Boden aufnehmen |
| Gefäß | Füllung ausgießen / selbst nutzen |
| Form-Rad | Form wechseln |

Bewusst **sieben Aktionen**: Das ist genug Tiefe für ein Action-Adventure, aber noch auf einem Gamepad ohne Doppelbelegung spielbar.

### 6.2 Gegner werden befreit, nicht getötet

Fast alle Gegner sind **glasierte Lebewesen**, Tiere und Tonwesen unter einer harten Glasurschicht. Rill bricht die Glasur auf, darunter kommt das Wesen frei, flieht und kehrt in die Welt zurück. Das hebt das Gefüge der Region (siehe 7).

Es gibt **zwei Wege**, Glasur zu brechen:

1. **Rohe Gewalt:** Stein-Arme oder Spröde-Zustand. Mehrere schwere Treffer, langsam und riskant.
2. **Abschrecken:** Den Gegner **erhitzen** (Glut ausschütten, brennende Holzarme) und dann **mit Wasser übergießen**. Der Temperaturschock sprengt die Glasur in einem Schlag.

**Warum Abschrecken?** Es belohnt Vorbereitung und Umweltnutzung statt reiner Reaktionsgeschwindigkeit. Es zwingt dazu, *beide Gefäß-Füllungen* zu managen und die Arena zu lesen (Wo ist Wasser? Wo ist Glut?). Es basiert auf einem echten physikalischen Prinzip, das man intuitiv versteht. Spielerinnen und Spieler „erfinden“ die Lösung selbst, statt sie gezeigt zu bekommen.

**Warum nicht töten?** Das Thema ist Veränderung gegen Erstarrung. Rill bringt Leben zurück, statt es zu nehmen. Mechanisch speist jeder Kampf das Gefüge, Kämpfe sind also nicht nur Hindernis, sondern Teil der Heilung der Welt.

### 6.3 Gegnertypen (Grundset)

| Gegner | Verhalten | Gegenstrategie |
|---|---|---|
| **Glasurmilbe** | Klein, im Schwarm; hinterlässt glasierten Boden (rutschig, kein Wasser versickert) | Jeder Treffer genügt; Flächenangriffe |
| **Scherbenhund** | Schnell, schneidend, schlägt gezielt Segmente ab | Stein-Arme blocken; Moos-Ranken heranziehen |
| **Krugwächter** | Groß, schwer gepanzert, langsam | Abschrecken oder Stein-Erschütterung |
| **Brenner** | Glutgeist; trocknet Umgebung und Rill aus | Wasser löschen; nass bleiben |
| **Glasierter Lettenbock** | Tonhirsch unter Glasur; flieht, statt anzugreifen; befreien gibt viel Gefüge | Einholen (Kugel), festhalten (Ranken), abschrecken |

### 6.4 Beispiel-Boss: Die Glasierte Weide (Die Schwemme)

Eine riesige Weide am Fluss, völlig glasiert. Ihre Wurzeln peitschen über die Arena und schlagen Segmente ab. Brenner-Geister kreisen in ihrer Krone und trocknen den Boden aus.

- **Phase 1:** Der Fluss am Arenarand ist Wasserquelle, die Brenner sind Glutquelle. Rill muss Glut von einem Brenner auffangen, eine Wurzel erhitzen, Wasser holen und abschrecken.
- **Phase 2:** Die Weide glasiert den Fluss zu. Wasser gibt es nur noch aus Regenpfützen, die Rill in *Schalen*-Form sammeln muss. Formen geht aber nur, wenn Rill feucht genug ist. Die Spannung zwischen Kampfkraft (trocken) und Handlungsfähigkeit (feucht) wird zum Kern des Kampfes.
- **Belohnung:** Die Weide wird befreit. Ihr Holz wächst nach und wird zur erneuerbaren Holzquelle für die Region.

---

## 7. Das Gefüge (Säule 3)

Jede Region hat einen Wert namens **Gefüge** (0–100). Er beschreibt, wie lebendig und widerstandsfähig die Landschaft ist.

| Handlung | Wirkung |
|---|---|
| Material aus **lebendiger** Quelle nehmen (Baum, Moospolster, Fels in einer Brücke) | **−** (Quelle verschwindet sichtbar) |
| Material aus **toter** Quelle nehmen (Treibholz, Geröll, Scherben) | ±0, aber selten und begrenzt |
| Altes Segment an einer **Lücke** zurückgeben (zerbrochene Brücke, ausgetrocknetes Beet, Mauerloch) | **+** |
| Glasierte Lebewesen befreien | **+** |
| Glasurherz der Region zerstören | **++** |

**Auswirkungen:**
- **Blüte (hohes Gefüge):** Materialien wachsen nach, Bewohner kehren zurück, Abkürzungen öffnen sich, und Schlick wird stärker.
- **Brache (niedriges Gefüge):** Jedes Mal, wenn Rill an einer Quelle rastet, breitet sich die Glasur ein Stück aus und blockiert Wege. Materialien werden knapp.

**Zurückgeben als Rätselmechanik:** Lücken in der Welt lassen sich oft *nur* mit einem eigenen Segment füllen. Beispiel: Die Steinbeine werden zum Brückenpfeiler, und Rill muss den Rest des Weges kriechen oder sich neue Beine aus Moos wachsen lassen. Zurückgeben ist also nicht nur „moralisch“, sondern ein aktives Werkzeug.

**Warum ein Gefüge-System?**
- Es verbindet **Mikro-Entscheidungen** (Woher nehme ich diesen Stein?) mit **Makro-Folgen** (Wie sieht die Region in zwei Stunden aus?).
- Es ist **kein Gut/Böse-Zähler**. Es gibt keine moralische Bewertung, nur ökologische Folgen. Gieriges Spielen ist erlaubt und kurzfristig stark, macht aber die Welt schwerer.
- Es ist **umkehrbar**. Fehler sind nie endgültig, weil man jederzeit zurückgeben und befreien kann. Das verhindert das Gefühl, einen Spielstand „ruiniert“ zu haben.
- Es macht Rasten an Quellen bedeutsam (Zeit vergeht), ohne einen Echtzeit-Timer einzuführen.

**Sichtbarkeit:** Das Gefüge wird **nicht als Zahl im HUD** angezeigt. Man sieht es an der Landschaft (Farbe, Vegetation, Wasserstand) und als Ring an jeder Quelle. Scherbling kommentiert größere Veränderungen.

---

## 8. Gameplay-Loop

Der Loop arbeitet auf vier Zeitebenen. Jede Ebene speist die nächste:

```
┌──────────────────────────────────────────────────────────────────────┐
│ SEKUNDEN · Kampf & Bewegung                                          │
│   Situation lesen → Material/Feuchte/Gefäß einsetzen → handeln       │
│   → Material verlieren oder gewinnen → neu anpassen                  │
└───────────────────────────────┬──────────────────────────────────────┘
                                ▼
┌──────────────────────────────────────────────────────────────────────┐
│ MINUTEN · Erkunden eines Abschnitts                                  │
│   Hindernis entdecken (Wasser, Wand, Glasur) → passendes Material    │
│   suchen → Quelle wählen (lebendig = schnell, tot = schonend)        │
│   → Hindernis überwinden → Glasurnest befreien → Quelle erreichen    │
└───────────────────────────────┬──────────────────────────────────────┘
                                ▼
┌──────────────────────────────────────────────────────────────────────┐
│ STUNDEN · Region befreien                                            │
│   Neues Material & neue Form erhalten → zuvor versperrte Wege        │
│   öffnen sich → Glasurherz (Boss) besiegen → Schlick erstarkt        │
│   → Region blüht auf (je nach Gefüge)                                │
└───────────────────────────────┬──────────────────────────────────────┘
                                ▼
┌──────────────────────────────────────────────────────────────────────┐
│ SPIEL · Zustand der Welt                                             │
│   Gefüge aller Regionen bestimmt Glasur-Druck, verfügbare Hilfe      │
│   in Kachelhof und das Ende                                          │
└──────────────────────────────────────────────────────────────────────┘
```

**Kern-Motivation pro Ebene:**
- *Sekunden:* „Ich habe mich gerade richtig angepasst.“ (Kompetenz)
- *Minuten:* „Ich habe das Rätsel mit meinem Körper gelöst.“ (Kreativität)
- *Stunden:* „Ich kann jetzt dorthin, wo ich vorher nicht hinkam.“ (Fortschritt)
- *Spiel:* „Die Welt sieht so aus, weil ich so gespielt habe.“ (Wirkung)

### 8.1 Fortschritt ohne Erfahrungspunkte

| Fortschrittsart | Quelle | Wirkung |
|---|---|---|
| **Materialien** | Je eins pro Region | Neue Fähigkeiten in allen vier Segmenten |
| **Formen** | Je eine pro Region (1–3) | Neue Durchquerung |
| **Siegel** | Versteckt in der Welt | Prägungen, die ins Material gedrückt werden, z. B. *Siegel der Sehne: Holzarme +1 Reichweite*. Pro Segment ein Siegel. |
| **Wissen** | Erkunden, Scherbling | Kombinationen, Abschrecken, Schwächen |

**Warum keine Erfahrungspunkte?** EP belohnen Grinding und entkoppeln Stärke von Verständnis. In *Ungebrannt* wird man besser, weil man **mehr Optionen** hat und **besser versteht**, wann man welche nutzt, nicht weil eine Zahl gestiegen ist.

---

## 9. Eine Minute *Ungebrannt*: Szenario

> Rill steht am Ufer der Schwemme: Holzbeine, Lehmarme, Lehmrumpf und Lehmkopf, Feuchte *lederhart*. Am anderen Ufer ein Krugwächter, dahinter ein Durchgang.
>
> Rill schwimmt mit den Holzbeinen hinüber und kommt nass an (*feucht*). Der Krugwächter greift an, seine Schläge verformen Rill nur, weil Rill so nass ist. Rill ist aber zu schwach, um die Glasur anzukratzen.
>
> Rill weicht mehrmals aus und trocknet dabei auf *trocken*. Ein Brenner kreist in der Nähe. Rill wechselt in die Schalenform, aber das geht nicht mehr, Rill ist zu trocken. Also anders: Rill schlägt mit den Lehmarmen nach dem Brenner, der Brenner zerstiebt, und seine Glut fällt zu Boden. Rill nimmt die Glut ins Gefäß.
>
> Glut auf den Krugwächter, seine Glasur glüht. Aber das Wasser ist am Ufer, zehn Schritte entfernt. Rill rennt hin. Der Krugwächter trifft und schlägt den linken Arm ab (*trocken* = erhöhter Schaden). Rill schöpft Wasser mit dem Rumpf und gießt es aus. *Knack.* Die Glasur springt, ein kleiner Tonvogel flattert davon.
>
> Der Arm liegt noch am anderen Ufer. Rill könnte zurückschwimmen oder einen Ast vom lebendigen Baum nebenan nehmen. Das wäre schneller, kostet aber Gefüge.

Diese eine Minute berührt **alle drei Säulen** und **alle Kernsysteme**, ohne dass ein Menü geöffnet wird.

---

## 10. Was das Spiel bewusst NICHT hat

| Weggelassen | Ersetzt durch | Begründung |
|---|---|---|
| Lebensleiste | Materialsegmente | Schaden soll das Spiel verändern, nicht nur eine Zahl |
| Ausdauerleiste | Feuchte-Spektrum | Zwei Pole statt einer guten Richtung |
| Inventar-Menü | Körper + ein Gefäß | Jede Entscheidung fällt *in der Welt*, nicht im Menü |
| Erfahrungspunkte | Materialien, Formen, Siegel | Stärke = Verständnis + Optionen |
| Töten | Befreien | Thema und Gefüge-Kreislauf |
| Moral-Score | Gefüge | Ökologische Folge statt Bewertung |

---

## 11. Präsentation

- **Perspektive:** 2D top-down, leicht schräg (¾-Ansicht).
  *Begründung:* Rills vier Segmente und ihr Zustand müssen jederzeit klar lesbar sein. Die Draufsicht zeigt Arena, Wasser- und Glutquellen gleichzeitig, was für das Abschrecken entscheidend ist. Außerdem ist sie für einen Prototyp mit überschaubarem Aufwand realisierbar.
- **Visueller Stil:** Erdtöne, matt und taktil. Die Glasur ist das **einzige glänzende Element** im Spiel, mit Spiegelungen und harten Kanten. Feinde erkennt man sofort am Glanz.
- **Feuchte-Anzeige am Körper:** Nasser Ton ist dunkel und glänzend feucht, trockener Ton hell und staubig, spröder Ton fast weiß mit Haarrissen. Zusätzlich gibt es einen kleinen Balken als Absicherung für die Barrierefreiheit.
- **HUD:** Nur eine kleine Silhouette von Rill (4 Segmente mit Materialfarbe und Risszustand), das Gefäßsymbol und die Feuchteanzeige.
- **Klang:** Jedes Material hat einen eigenen Schritt- und Treffersound (dumpf, hohl, klirrend, knirschend). Angeschlagene Segmente klingen anders, sodass man Schaden auch hören kann.

---

## 12. Risiken und Gegenmaßnahmen

| Risiko | Wahrscheinlichkeit | Gegenmaßnahme |
|---|---|---|
| **Systemüberladung**: zu viele Wechselwirkungen am Anfang | hoch | Ein Material pro Region. Die erste Stunde nur mit Lehm und Holz. Feuchte wird erst in Region 1 nach dem Tutorial voll wirksam. |
| **Todesspirale** durch Segmentverlust | mittel | Teile fallen immer in Reichweite, schnelles Aufheben, Notform, Schlamm-Zustand als „Schutzmodus“ |
| **Gefüge wird ignoriert oder als Strafe empfunden** | mittel | Sichtbare, nicht-numerische Rückmeldung; immer umkehrbar; Zurückgeben ist auch Rätselwerkzeug |
| **Abschrecken ist zu umständlich** | mittel | Arenen so bauen, dass Wasser *und* Glut in Reichweite sind; rohe Gewalt als immer verfügbarer Plan B |
| **Material-Wechsel unterbricht den Kampffluss** | mittel | Aufnehmen dauert unter 0,5 s; Kontext-Auto-Slot (Beine für Bewegungsmaterialien); manuelle Wahl optional |
| **Prototyp-Umfang explodiert** | hoch | Strikt begrenzter Vertical Slice (siehe 13) |

---

## 13. Vorschlag für den nächsten Schritt: Prototyp-Umfang (noch nicht gebaut)

Ziel ist ein **spielbarer Vertical Slice**, der die riskantesten Annahmen testet, nicht das ganze Spiel.

**Umfang:**
- 1 Region: **Die Schwemme** (3 Bildschirme + Bossarena)
- 3 Materialien: **Lehm, Holz, Stein** (Stein ausnahmsweise vorgezogen, weil er die Gegenthese zu Holz bildet)
- Feuchte-Spektrum komplett (5 Stufen)
- Gefäß mit Wasser und Glut
- 1 Form: **Kugel**
- 3 Gegnertypen: Glasurmilbe, Krugwächter, Brenner
- 1 Miniboss: verkleinerte Glasierte Weide
- Gefüge für diese eine Region (vereinfacht)

**Technik (Vorschlag):** Browser, HTML5 Canvas mit TypeScript oder Phaser 3. Damit ist das Spiel ohne Installation sofort spielbar, und Tastatur sowie Gamepad werden unterstützt.

**Testfragen für den Prototyp:**
1. Erkennen Testspielende ihren Zustand (Segmente, Feuchte) **ohne Erklärung** innerhalb von 5 Minuten?
2. Entdecken mindestens die Hälfte das **Abschrecken selbst**, mit maximal einem Hinweis?
3. Fühlt sich der Materialwechsel wie eine **Entscheidung** an oder wie lästige Verwaltung?
4. Nehmen Testspielende bewusst von toten statt lebendigen Quellen, **ohne dass man es ihnen sagt**?

---

## 14. Offene Entscheidungen für dich

Diese Punkte würde ich gern mit dir klären, bevor es an den Prototyp geht:

1. **Tonalität:** Eher *melancholisch-poetisch* (Fokus auf Vells Trauer, Schlicks Sterben) oder *warm-humorvoll* (Fokus auf Scherblings Geplapper, skurrile Bewohner)? Mein Vorschlag ist eine Mischung mit melancholischem Kern und humorvoller Oberfläche.
2. **Perspektive:** Top-down (empfohlen, siehe 11) oder Seitenansicht? Eine Seitenansicht würde Stein (sinken) und Holz (schwimmen) noch stärker betonen, schwächt aber die Arena-Übersicht beim Abschrecken.
3. **Gefüge-Härte:** Soll niedriges Gefüge Wege tatsächlich blockieren (spürbare Konsequenz) oder nur kosmetisch und atmosphärisch wirken (zugänglicher)?
4. **Technologie für den Prototyp:** Reines HTML5/TypeScript (leichtgewichtig, alles selbst gebaut) oder Phaser 3 (schneller, mehr fertige Bausteine)?
5. **Ende:** Soll es mehrere Enden je nach Gefüge geben oder ein festes Ende mit variierenden Details?
