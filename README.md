# IDS

Alle Unterlagen die für die Enführungsaufgabe notwendig sind, findest Du unter <https://github.com/ckmk14/IDS>.

- Erstelle ein Repository auf https://github.com/ und füge mich (ckmk14) als collaborator hinzu. Füge zusätzlich die Dateien exercise.pcap, local.rules und die Readme (mit den Anworten) in dein Repository hinzu.
- Analysiere das PCAP-File mit den Snort-Regeln. Beantworte folgende Fragen:
  - IP-Adresse der infizierten Maschine: ?   -- 65.181.125.20            
  - Mac-Adresse der infizierten Maschine: ?  -- 00:09:B6:BA:37:F1        
  - Wie lautet der Link (in der Email) der zur Infektion geführt hat: ? -- http://wme0hsxg.e6to8jdmiysycbmeepm29nfprvigdwev.top/1dkfJu=wME0HsXGMATTHEW
  - Wie lautet das VB-Script das zur Infektion geführt hat: ?
  - Füge zusätzliche Regeln hinzu, die weitere Indikatoren dedektieren, um Alerts zu generieren.
    - Hinweis: Kommunikation mit IP-Adresse: 65.181.112.240
- Schreibe ein kleines Python-Programm welches die Alerts von Snort als Eingabe erhält und als Ausgabe lediglich die Uhrzeit und den Text der Message auf der Konsole ausgibt.
  - Pushe Dein Programm ebenfalls ins Repo.