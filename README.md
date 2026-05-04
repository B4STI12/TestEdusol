---

# TestEdusol

Dieses Projekt enthält vier Versionen der Edusol-Website zum Vergleich.

## Einstieg

Öffne **[index.html](https://b4sti12.github.io/TestEdusol/)** im Browser — dort kannst du direkt auswählen, welche Version du ansehen möchtest.

## Ordner-Struktur

- **[Original/](Original/)** – Die ursprüngliche Version der Website
- **[Humanized/](Humanized/)** – Die überarbeitete/humanisierte Version
- **[V2/](V2/)** – Kompletter Neuaufbau mit Poppins-Font, Bootstrap 5, Dropdown-Navigation und erweitertem Seitenumfang
- **[V3/](V3/)** – Weiterentwicklung von V2 mit Partial-System (Navbar & Footer per fetch())
- **[V3.1/](V3.1/)** – Refactoring von V3: zentrales Stylesheet statt Inline-Styles, CSS Custom Properties, Bugfixes

## Seiten

### Original & Humanized

| Seite | Original | Humanized |
| ----- | -------- | --------- |
| Startseite | [Original/index.html](Original/index.html) | [Humanized/index.html](Humanized/index.html) |
| Über uns | [Original/ueber-uns.html](Original/ueber-uns.html) | [Humanized/ueber-uns.html](Humanized/ueber-uns.html) |
| Kontakt | [Original/kontakt.html](Original/kontakt.html) | [Humanized/kontakt.html](Humanized/kontakt.html) |
| Schulentwicklung | [Original/schulentwicklung.html](Original/schulentwicklung.html) | [Humanized/schulentwicklung.html](Humanized/schulentwicklung.html) |
| Coaching & Supervision | [Original/coaching-supervision.html](Original/coaching-supervision.html) | [Humanized/coaching-supervision.html](Humanized/coaching-supervision.html) |
| Krisenmanagement | [Original/krisenmanagement.html](Original/krisenmanagement.html) | [Humanized/krisenmanagement.html](Humanized/krisenmanagement.html) |
| Fachvorträge | [Original/fachvortraege.html](Original/fachvortraege.html) | [Humanized/fachvortraege.html](Humanized/fachvortraege.html) |
| NPO | [Original/npo.html](Original/npo.html) | [Humanized/npo.html](Humanized/npo.html) |

### V2

| Seite | Link |
| ----- | ---- |
| Startseite | [V2/index.html](V2/index.html) |
| Wir sind EDUSOL | [V2/ueber-uns.html](V2/ueber-uns.html) |
| Kontakt | [V2/kontakt.html](V2/kontakt.html) |
| Coaching & Supervision | [V2/coaching-supervision.html](V2/coaching-supervision.html) |
| Fachvorträge | [V2/fachvortraege.html](V2/fachvortraege.html) |
| Krisenmanagement | [V2/krisenmanagement.html](V2/krisenmanagement.html) |
| NPO | [V2/npo.html](V2/npo.html) |
| Schulentwicklung | [V2/schulentwicklung.html](V2/schulentwicklung.html) |
| Datenschutz | [V2/datenschutz.html](V2/datenschutz.html) |
| Impressum | [V2/impressum.html](V2/impressum.html) |

### V3 & V3.1

| Seite | V3 | V3.1 |
| ----- | -- | ---- |
| Startseite | [V3/index.html](V3/index.html) | [V3.1/index.html](V3.1/index.html) |
| Wir sind EDUSOL | [V3/ueber-uns.html](V3/ueber-uns.html) | [V3.1/ueber-uns.html](V3.1/ueber-uns.html) |
| Kontakt | [V3/kontakt.html](V3/kontakt.html) | [V3.1/kontakt.html](V3.1/kontakt.html) |
| Coaching & Supervision | [V3/coaching-supervision.html](V3/coaching-supervision.html) | [V3.1/coaching-supervision.html](V3.1/coaching-supervision.html) |
| Fachvorträge | [V3/fachvortraege.html](V3/fachvortraege.html) | [V3.1/fachvortraege.html](V3.1/fachvortraege.html) |
| Krisenmanagement | [V3/krisenmanagement.html](V3/krisenmanagement.html) | [V3.1/krisenmanagement.html](V3.1/krisenmanagement.html) |
| NPO | [V3/npo.html](V3/npo.html) | [V3.1/npo.html](V3.1/npo.html) |
| Schulentwicklung | [V3/schulentwicklung.html](V3/schulentwicklung.html) | [V3.1/schulentwicklung.html](V3.1/schulentwicklung.html) |
| Datenschutz | [V3/datenschutz.html](V3/datenschutz.html) | [V3.1/datenschutz.html](V3.1/datenschutz.html) |
| Impressum | [V3/impressum.html](V3/impressum.html) | [V3.1/impressum.html](V3.1/impressum.html) |

## Was ist neu in V2?

- **Navbar** mit Dropdown-Menü für alle Wirkungsfelder (inkl. SVG-Icons)
- **Wirkungsfelder-Seiten** mit Hero, Inhaltstext, Feature-Karten und CTA-Kasten
- **Über uns** mit Titel „Das sind wir" und zwei Inhaltssektionen
- **Footer** mit LinkedIn-Link, Navigationslinks, Datenschutz & Impressum
- **Neue Seiten**: Datenschutz, Impressum, Kontaktformular

## Was ist neu in V3?

- **Partial-System** – Navbar und Footer als eigene Dateien (`navbar.html`, `footer.html`), per `fetch()` eingebunden
- **Eule-Icons** pro Wirkungsfeld auf der Startseite
- **Einblicke-Sektion** mit vier Praxisbeispielen und WhatsApp-CTA

## Was ist neu in V3.1?

- **Zentrales Stylesheet (`style.css`)** – Alle Farben als CSS Custom Properties, keine Inline-Styles mehr
- **Semantische CSS-Klassen** – z.B. `.card-insight`, `.hero-main`, `.btn-edusol-primary` statt langer `style="..."`-Attribute
- **Bugfix** – Fachvorträge-Bild in Navbar und Detailseite wurde nicht angezeigt (Encoding-Problem im Dateinamen behoben)
