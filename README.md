# BEOG_Pythonscript
Dieses Pythonscript lädt über eine SRU-Abfrage aus Alma die Metadaten (MARCXML) der Titel herunter, welche mit "bbggr" kodiert sind. Danach extrahiert es die Titeldaten und die GND-ID für den Ort, welcher in der Ortsgeschichte beschrieben wird. 

Mit der GND-ID können über die BErnerOrtsTabelle (BEOT) die Identifiers für Wikidata (Q_ID), das Historische Lexikon der Schweiz (id_hls) und ortsnamen.ch (id_ortsnamen) zugeordnet werden.

Anhand der Q-ID werden dann die gewünschten Daten (Koordinaten, Wappen und Webseite der Gemeinde, Wikipedia- und geo.admin.ch-Link) aus Wikidata heruntergeladen.

Dass Script kann in Google Colab ausgeführt werden: [Pythonscript auf Colab](https://drive.google.com/drive/folders/1olFt4UmHhmwMwLAt5w6k3gWg4vRLAw4M) 
(Achtung! Dazu muss man sich mit einem Google Account einloggen.)
