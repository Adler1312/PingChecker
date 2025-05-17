# PingChecker

PowerShell-Skript zur Überwachung der Erreichbarkeit von Servern und IP-Adressen via Ping.

> Hinweis: Dieses Projekt ist ein älteres Schulprojekt und dient zur Archivierung sowie als Referenz für PowerShell-Grundlagen.

## 📘 Beschreibung

Dieses Skript wurde im Rahmen eines Schulprojekts (Modul 122) erstellt. Es dient dazu, eine Liste von IP-Adressen oder Hostnamen automatisiert per `ping` zu überprüfen. Die Ergebnisse werden übersichtlich in eine Logdatei geschrieben – inkl. Fehlerhinweisen und MessageBox bei Ausfällen.

## 🔧 Funktionen

- Liest IP-Adressen aus einer Datei (`ip.txt`)
- Führt pro Adresse 4 Ping-Versuche durch
- Erkennt 100% Paketverlust und gibt Warnungen aus
- Erstellt automatisch eine Log-Datei mit Zeitstempel (`result.txt`)
- Zeigt bei kritischen Fehlern eine grafische MessageBox an

## 🚀 Verwendung

1. Erstelle eine Datei `ip.txt` im Ordner `.\giri\` mit folgendem Inhalt (jede IP oder Domain in eine neue Zeile, **ohne Leerzeilen**):

    ```
    192.168.1.1
    www.google.com
    127.0.0.1
    ```

2. Starte das Skript über PowerShell (Verzeichnis vorher aufrufen):

    ```powershell
    Set-Location "Pfad\zum\Ordner"
    .\PingChecker.ps1
    ```

3. Prüfe anschließend die Datei `result.txt` im Ordner `.\giri\` für die Ergebnisse.

## 🖼️ Beispielausgabe

![Beispiel](https://github.com/user-attachments/assets/8e5eedf4-dae7-43d0-84f4-0edd66b8184c)

PowerShell-Skript zur Überwachung der Erreichbarkeit von Servern und IP-Adressen via Ping.

---







