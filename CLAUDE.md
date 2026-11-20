# Portfolio-Website

Einseitige Portfolio-Website auf Deutsch, mit zwei Bereichen:
- **Social Media:** Reels im Hochformat
- **Film & Video:** Videos im Querformat

## Dateien
- `index.html` ist die komplette Website. CSS, JavaScript und alle Vorschaubilder (als base64) stecken in dieser einen Datei.
- `Portfolio.html` ist eine veraltete Version und kann gelöscht werden.
- Online-Version (Claude Artifact): https://claude.ai/artifact/V1Hby1WWsDyzwuJ9ThnTuw
- Gehostet auf Netlify. Zum Hochladen die `index.html` in einen Ordner legen und den Ordner unter „Deploys“ hochladen.

## Design
- Schriften: Inter Tight für Überschriften, Manrope für Text (Google Fonts). Sie sollen modern und clean wirken, an Apple erinnern, aber nicht danach aussehen.
- Hintergrund off-white `#f8f6f2`. Lila nur als Akzent: Tags, Unterstreichung in der Überschrift. Kein Dark Mode, keine lila Flächen.
- Die Überschrift wechselt mit dem Tab: „Geschichten im Hochformat.“ für Social Media, „Geschichten im Querformat.“ für Film & Video.
- Reel-Raster: 4 Spalten ab 1180px Breite, sonst 2 Spalten, ab 600px 1 Spalte. Karten im Format 4:5.
- Reel-Karten sehen aus wie Instagram-Posts: Herz, Kommentar-Sprechblase wie bei Instagram und gleich groß wie das Herz, Lesezeichen.
- Kein Kontaktbereich.

## Technik
- Videos werden nicht eingebettet. Sie sind mit „Auf YouTube ansehen ↗“ verlinkt und öffnen sich in einem neuen Tab.
- Vorschaubilder sind als base64-JPG direkt in der Datei, etwa 720px breit. Der Ausschnitt wird pro Bild mit `object-position` eingestellt.
- Die Regel `[hidden] { display: none !important; }` muss im CSS bleiben. Ohne sie funktioniert der Wechsel zwischen den Tabs außerhalb von Claude nicht, zum Beispiel auf Netlify.
- Die Datei braucht einen vollständigen Kopfbereich: doctype, `lang="de"`, charset utf-8, viewport.

## Inhalte
Reels (Social Media):
1. LoIN4n_uZK0, Tag „Queens Nails“: ausführlicher Prozess von der Modellage bis zum Nude-Ombré.
2. OC3bd7o5lz8, Tag „Queens Nails“: kurze Inspo-Variante mit rosa Farbkreisen, die Modellage ist nur kurz zu sehen.
3. E7GomoT8d9Y, Tag „Maledives Underwater Restaurant“: Dinner unter Wasser auf den Malediven.
4. dKyrnUkAn4Q, Tag „Kebab Bowl“: High-Protein-Rezept.
5. 30QJ7uJbZjo, Tag „Karpaltunnelsyndrom“: ein Arzt erklärt das Karpaltunnelsyndrom, Einstieg mit der Frage „Schläft deine Hand ein?“.

Querformat (Film & Video):
1. 6vBuQZyQ14I, „Decoding It The Hard Way“: Kurzporträt der Profitänzerin Lea Karnutsch und ihres Bühnenstücks.
2. SQQMLNZyOJ4, „Pam & Solany“: Beitrag für die ATV-Sendung „Für immer Italien“.
3. mSKwUJojVOs, „Asterix“: Beitrag für die ATV-Sendung „Für immer Italien“.

## Arbeitsregeln
- Texte müssen ehrlich bleiben. Keine Details erfinden, nur Fakten verwenden, die die Autorin nennt oder die im Vorschaubild sichtbar sind. Annahmen klar kennzeichnen.
- Keine großen Versprechen wie „Content, der hängen bleibt“.
- Über die Autorin so wenig wie möglich schreiben. Der Abschnitt „Über mich“ hat nur das Medientechnik-Studium, den TV-Schnitt und den Bogen zu Reels.
- Vor jedem Download nachfragen, auch bei YouTube-Vorschaubildern.
- Antworten auf Deutsch.

## Offene Fragen
- Schreibweise „Maledives“: Gemeint ist vermutlich „Maldives“ oder „Malediven“.
- Welche Rolle die Autorin bei den Filmen hatte, zum Beispiel Kamera oder Schnitt.
