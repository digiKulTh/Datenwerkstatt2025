# Photogrammetrietesting
## Idee
Leicht zugängliche Tools sollen daraufhin getestet werden, ob sie sich für einen geradlinigen und störungsarmen Workflow zur Online-Weitergabe bzw. -Veröffentlichung von 3D-Digitalisaten eignen. Dieses Testing soll dokumentiert werden, d. h. detailliert beschrieben, wie und womit fotografiert wurde, welche Software wann und wie zum Einsatz kam usw. – gern auch mit einen Video/Screencast.
Die Veröffentlichung erfolgt hier via JS-Library [https://modelviewer.dev/](https://modelviewer.dev/) als GitHub-Page.
## Workflow
- Photographische Erfassung des Objekts
- Nutzung des PG-Tools der Wahl (auf MacOS z. B. [PhotoCatch](https://github.com/eospi/Object-Capture-UI))
- Transformation nach .glb und ggf. Nachbearbeitung in [Blender](https://www.blender.org/)
- Testing auf [https://modelviewer.dev/editor/](https://modelviewer.dev/editor/), Export via "Export Scene" (generiert ein .webp-File)
- Kompression des .glb z. B. mit [https://githubdragonfly.github.io/viewers/templates/GM%20Viewer.html](https://githubdragonfly.github.io/viewers/templates/GM%20Viewer.html)
- Integration des Tests/Beispiels mit Doku im html-Template showcase.html, dafür werden die Dateien mit den Endungen .glb (das 3D-Modell) und .webp (für die Voransicht) benötigt
- Angabe der Ersteller:innen nicht vergessen
- Aufrufen des Showcase unter [https://michaelmarkert.github.io/digiKulTh/Datenwerkstatt2025/showcase.html](https://michaelmarkert.github.io/digiKulTh/Datenwerkstatt2025/showcase.html) (die Modelle brauchen etwas Ladezeit)
