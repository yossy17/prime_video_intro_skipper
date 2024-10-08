Dieses Skript bietet die Möglichkeit, Intros und Enden für die folgenden Dienste automatisch zu überspringen:

- [Prime Video](https://amazon.co.jp/gp/video/storefront)
- [Netflix](https://netflix.com)

## Verwendung

Sie können die Einstellungen mit Tastenkombinationen ändern.  
Die letzten beiden einzelnen Einstellungen können nur geändert werden, wenn die gesamte Überspring-Funktion auf `ON` gesetzt ist.

- `Alt + n`: Umschalten der gesamten Überspring-Funktion `EIN`/`AUS`.
- `Alt + x`: Umschalten des Intro-Überspringens `EIN`/`AUS`.
- `Alt + c`: Umschalten des Ending-Überspringens `EIN`/`AUS`.

Der Status des Skripts kann über das HUD überprüft werden, das oben links auf dem Bildschirm angezeigt wird.  
Das HUD zeigt den aktuellen Status des Intro- und Ending-Überspringens an.

---

## Mitwirken

Fehlerberichte und Funktionsvorschläge sind willkommen. Bitte [öffnen Sie ein Issue](https://github.com/yossy17/streaming-video-skipper/issues) oder [erstellen Sie einen Pull Request](https://github.com/yossy17/streaming-video-skipper/pulls).

Dieses Skript funktioniert nach einem einfachen Mechanismus, indem es den Klassennamen von Schaltflächen-Elementen angibt und diese Elemente physisch anklickt.
Daher kann es grundsätzlich auf Streaming-Diensten funktionieren, die Schaltflächen wie `Intro überspringen` oder `Nächste Episode` haben.
Da ich selbst jedoch nicht viele Dienste abonniert habe, habe ich keine Möglichkeit, diese Elemente zu kennen.
Durch Hinzufügen zum Code kann dieses Skript allein mit mehr Diensten kompatibel gemacht werden.
Wenn möglich, wäre ich dankbar, wenn Sie die Selektoren für jeden Dienst bereitstellen könnten, da dies zur Verbesserung des Dienstes beitragen würde.

## Lizenz

Dieses Projekt steht unter der MIT-Lizenz.
