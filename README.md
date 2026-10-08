# PlakettenAlarm – Content

Öffentliches Content-Repo für die Android-App **PlakettenAlarm**. Wird über
GitHub Pages ausgeliefert und von der App genutzt.

## Inhalt

| Datei | Zweck | Öffentliche URL |
|---|---|---|
| `providers.json` | Remote-konfigurierbare Anbieterliste (Versicherungsvergleich) | https://scorparc.github.io/plakettenalarm-content/providers.json |

## Anbieterliste aktualisieren

`providers.json` ändern und committen – die App lädt beim nächsten Start die
neue Fassung (Fallback: gebündeltes Asset in der App). Schema siehe README der
App. Kein App-Update nötig.

## Rechtstexte

Impressum und Datenschutzerklärung liegen **nicht** mehr hier, sondern zentral
im Repo [scorparc/legal](https://github.com/scorparc/legal) – gemeinsam
genutzt von ScootRules, PlakettenAlarm und ScootKeeper:

- Impressum: https://scorparc.github.io/legal/impressum.html
- Datenschutz (PlakettenAlarm): https://scorparc.github.io/legal/plakettenalarm/datenschutz.html

Die App lädt die strukturierten JSON-Fassungen davon (`impressum.json`,
`plakettenalarm/datenschutz.json`) und cached sie lokal; siehe
`lib/services/legal_repository.dart` im App-Repo.
