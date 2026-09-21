Fußball-Mathe V20 – Fix für Spielernamen

EA hängt aktuell teilweise die Position an den Namen, z.B. „Harry Kane ST“.
Der Updater entfernt dieses Suffix nun aus name/search; pos bleibt separat erhalten.
Außerdem erkennt das Sicherheitsnetz vorhandene Spieler anhand der eaId.
Die bereits entstandenen Doppelungen in players.json wurden anhand der eaId entfernt.
