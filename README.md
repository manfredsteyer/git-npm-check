# npm und git check

Prüfen Sie, ob Sie per git und npm das Seed-Projekt des Angular-Teams herunterladen und ausführen können:

```
git clone https://github.com/angular/angular2-seed
cd angular2-seed
npm install
npm start
// ein wenig warten
// Unter localhost:3000 sollte nun eine Demo-Anwendung zu finden sein
```

# Probleme

Bei Problemen sollte man die Proxy-Einstellung oder die Proxy-Konfiguration prüfen.

Ggf. kann man die Probleme auch lokal lösen. Um lokal den Proxy für npm zu setzen geht man wie folgt vor:

```
npm config set proxy [http|https]://[proxy-address]:[port]
npm config set https-proxy [http|https]://[proxy-address]:[port]
```

Analog geht man für git vor:

```
git config --global http.proxy [http|https]://[proxy-address]:[port]
```

Benutzername und Passwort für den Proxy können auch direkt in die Url aufgenommen werden:

```
[http|https]://[username]:[passwort]@[proxy-address]:[port]
```

Alternativ dazu können diese Informationen auch in den Konfigurationsdateien von npm und git eingetragen werden. Infos dazu finden sich in den Dokumentationen dieser beide Produkte.

# Nach dem Lösen der Probleme

Vergessen Sie bitte nicht, die nötigen Befehle inkl. Proxy-Einstellungen an alle Teilnehmer weiterzugeben.

# Keine Problemlösung?

Falls Sie eventuelle Probleme vor dem Termin nicht lösen können, geben Sie mir bitte kurz bescheid. In diesem Fall können wir auf andere Lösungen ausweichen (z. B. zips per ftp).
