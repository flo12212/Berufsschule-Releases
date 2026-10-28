# Berufsschule

Windows-App für die Ludwig-Geissler-Schule: Stundenplan mit Ausfall und
Vertretung aus WebUntis, Moodle-Kurse mit Aufgaben, Textseiten und PDFs,
Hausaufgaben mit automatischer Frist, Kalender, Prüfungs-Countdown und ein
Wochenrückblick fürs Berichtsheft.

In diesem Repo liegen nur die fertigen Versionen, der Quellcode ist privat.

## Herunterladen

Unter **[Releases](https://github.com/flo12212/Berufsschule-Releases/releases/latest)**
die neueste `Berufsschule-x.y.z.zip` laden, entpacken und `Berufsschule.exe`
starten. Keine Installation, keine Adminrechte. Auf dem Schulrechner am besten
nach `H:\` entpacken, dann ist sie an jedem Schulrechner da.

Beim ersten Start meldet Windows „Der Computer wurde geschützt“, weil die Datei
nicht signiert ist. Auf „Weitere Informationen“ und dann „Trotzdem ausführen“.

Was du zum Einrichten brauchst, steht in der `LIESMICH.txt` in der ZIP.
Kurz: Benutzername und Untis-Mobile-Schlüssel aus WebUntis (Profil,
Freigaben) und deinen Moodle-Zugang.

## Updates

Die App schaut beim Start hier nach, ob es eine neuere Version gibt, und
zeigt dann in der Seitenleiste „Version x ist da“. Neue ZIP laden und über die
alte entpacken, deine Daten bleiben.

## Datenschutz

Zugangsdaten bleiben verschlüsselt auf deinem Rechner. Die App spricht nur mit
WebUntis, Moodle, Open-Meteo (Wetter) und hier mit GitHub für den Update-Hinweis.
Es gibt keinen eigenen Server und kein Tracking.

## Hinweis

Gemacht von Florian Taschke (10 IT 2). Kein offizielles Angebot der Schule,
von Untis oder von Moodle.
