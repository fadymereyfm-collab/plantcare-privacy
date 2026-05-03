# Datenschutzerklärung — PlantCare

**Stand:** Mai 2026
**Anbieter:** Fady Mereyfm
**Kontakt:** fadymerey.fm@gmail.com

## 1. Allgemeines
PlantCare ist eine Android-App zur Pflege von Zimmerpflanzen.
Wir erheben personenbezogene Daten nur soweit erforderlich für den Betrieb der App.

## 2. Welche Daten verarbeitet werden
- **E-Mail-Adresse** (bei Registrierung) — zur Identifikation des Kontos
- **Pflanzenfotos** (optional) — gespeichert lokal + in Firebase Storage
- **Standort** (Stadt-Ebene, optional) — für wetterbasierte Pflegehinweise
- **Krankheitsdiagnose-Fotos** (optional) — siehe §5

## 3. Auth + Cloud Sync (Firebase)
Bei E-Mail- oder Google-Anmeldung werden Auth-Token und
Pflanzen­metadaten in Firebase Authentication + Firestore gespeichert.
- **Anbieter:** Google Ireland Limited
- **Standort:** EU (europe-west1)
- **Rechtsgrundlage:** Art. 6 Abs. 1 lit. b DSGVO (Vertragserfüllung)

## 4. Wetter (OpenWeatherMap)
Bei aktivierter Standortfreigabe werden GPS-Koordinaten an
OpenWeatherMap gesendet, um lokale Wetterdaten abzurufen.
- **Anbieter:** OpenWeather Ltd. (UK)
- **Datenschutz:** https://openweather.co.uk/privacy-policy

## 5. Krankheitsdiagnose (Google Gemini AI)
Wenn Sie die Krankheitsdiagnose nutzen, wird das aufgenommene
Foto an den KI-Dienst **Google Gemini 2.5 Flash** übermittelt.
- **Anbieter:** Google Ireland Limited
- **Standort:** EU (über Paid-Tier-Billing)
- **Verarbeitung:** ausschließlich zur Diagnose, **keine Trainingsnutzung**
  (Paid-Tier-Garantie)
- **Speicherung:** das Foto wird auf Google-Servern bis zu 24 Stunden
  gecacht, danach gelöscht
- **Rechtsgrundlage:** Art. 6 Abs. 1 lit. b DSGVO + ausdrückliche
  Einwilligung beim ersten Gebrauch
- **Google-Datenschutz:** https://policies.google.com/privacy

## 6. AdMob (Werbung)
Für kostenlose Nutzer zeigt die App Werbebanner über Google AdMob.
- **Anbieter:** Google Ireland Limited
- **Personalisierung:** kann in Einstellungen → Werbung deaktiviert werden

## 7. Crashlytics (Fehlerberichte)
Bei zugestimmtem Consent werden anonyme Absturzberichte an
Firebase Crashlytics gesendet.
- **Standort:** EU
- **Inhalt:** Stack-Trace + Geräte-Modell — keine personenbezogenen Daten

## 8. Ihre Rechte (Art. 15-21 DSGVO)
- **Auskunft:** Einstellungen → Daten exportieren
- **Löschung:** Einstellungen → Konto löschen
- **Widerspruch:** Onboarding-Consent jederzeit widerrufbar in Einstellungen
- **Beschwerde:** Bayerisches Landesamt für Datenschutzaufsicht

## 9. Änderungen dieser Erklärung
Änderungen werden in der App angekündigt.
Letzte Aktualisierung: Mai 2026.

## Referenzbilder von Drittanbietern

Nach einer Krankheitsdiagnose werden zur visuellen Bestätigung Referenzbilder von folgenden Diensten in die App geladen:

- **Wikipedia / Wikimedia Commons** — betrieben von der Wikimedia Foundation, San Francisco, USA. [Datenschutzerklärung](https://foundation.wikimedia.org/wiki/Privacy_policy)
- **iNaturalist** — betrieben von der California Academy of Sciences, San Francisco, USA. [Datenschutzerklärung](https://www.inaturalist.org/pages/privacy)
- **PlantVillage** — Bilder werden über das jsDelivr-CDN (betrieben von Cloudflare/Volentix) ausgeliefert. [Datenschutzerklärung jsDelivr](https://www.jsdelivr.com/terms/privacy-policy-jsdelivr-net)

Beim Laden dieser Bilder kann deine IP-Adresse von den genannten Diensten erfasst werden (technisch notwendig für die Bildauslieferung). **Dein eigenes Pflanzenfoto wird NICHT an diese Dienste übertragen** — es bleibt ausschließlich zwischen deinem Gerät und Google Gemini.

Rechtsgrundlage: Art. 6 Abs. 1 lit. f DSGVO (berechtigtes Interesse an einer hilfreichen visuellen Bestätigung der Diagnose).
