# DAWICON Rückstellungs-Manager — Paket-Endpunkt

Statischer Endpunkt (F-82/F-84): `latest.json` ist das signierte Manifest,
daneben liegen die signierten Zins- und Erklärtextpakete (`*.dwpkg.json`).
Die Anwendung prüft jede Signatur gegen die einkompilierten DAWICON-Schlüssel;
unsignierte oder veränderte Dateien werden verworfen. Hier liegen keine
Mandantendaten.

Veröffentlicht wird ausschließlich über die Redaktionskonsole
(`rsm-redaktion veroeffentlichen`, Vier-Augen-Freigabe); danach die Dateien
hierher kopieren und pushen. `manifest.unsigniert.json` bleibt in der Redaktion.
