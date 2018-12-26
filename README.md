DoorPiWeb - Wen Interface for DoorPi
================

Dieses Repository hat zwei Funktionen.

Auf der einen Seite kann es lokal zusammen mit DoorPi abgelegt und genutzt werden.
In der config-Datei von DoorPi wird es dann eingebunden:

```
[DoorPiWeb]
www = !BASEPATH!/../DoorPiWeb
```

Auf der anderen Seite ist es ein "Online-Fallback".
Wenn die gesuchte Seite nicht lokal gefunden werden kann, so wird die gesuchte Seite aus diesem Repository geladen.
So kann DoorPi genutzt werden, ohne dass die Dateien lokal liegen müssen.
Das ist vor allem für die Erstinstallation von DoorPi gedacht.
