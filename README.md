# PlakettenAlarm – Content & Rechtstexte

Öffentliches Content-Repo für die Android-App **PlakettenAlarm**. Wird über
GitHub Pages ausgeliefert und von der App bzw. der Google Play Console genutzt.

## Inhalt

| Datei | Zweck | Öffentliche URL |
|---|---|---|
| `providers.json` | Remote-konfigurierbare Anbieterliste (Versicherungsvergleich) | https://scorparc.github.io/plakettenalarm-content/providers.json |
| `legal/datenschutz.html` | Datenschutzerklärung (Play-Console-Pflicht-URL) | https://scorparc.github.io/plakettenalarm-content/legal/datenschutz.html |
| `legal/impressum.html` | Impressum (§ 5 DDG) | https://scorparc.github.io/plakettenalarm-content/legal/impressum.html |

## Anbieterliste aktualisieren

`providers.json` ändern und committen – die App lädt beim nächsten Start die
neue Fassung (Fallback: gebündeltes Asset in der App). Schema siehe README der
App. Kein App-Update nötig.

Die Rechtstexte hier müssen inhaltlich mit den nativen Fassungen in der App
(`lib/screens/legal_screens.dart`) übereinstimmen.
