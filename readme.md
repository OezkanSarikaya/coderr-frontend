# Coderr Frontend

**Version**: 1.0  
Coderr ist eine Plattform mit Freelancern in der Web-Entwicklung. Dies ist ein Lernprojekt und wurde in reinem Vanilla JavaScript entwickelt.  
Das dazugehörige Backend ist hier zu finden: [Coderr Backend Repository](https://github.com/OezkanSarikaya/coderr-backend).

## Funktionen

- **Registrierung und Login** als Business (Anbieter) oder Customer User (Kunde).  
- **Profilverwaltung**: Jeder Benutzer kann sein eigenes Profil bearbeiten.  
- **Angebote**: Nur Business User (Anbieter) können Angebote erstellen und bearbeiten.  
- **Bestellungen**:  
  - Customer User (Kunden) können Angebote bestellen.  
  - Nur Business User (Anbieter) können Bestellungen bearbeiten.    
- **Bewertungen (Reviews)**:  
  - Nur Kunden können Bewertungen erstellen, bearbeiten oder löschen.  
- HTML Tags werden von allen Texteingaben entfernt (funktioniert durch das Backend).

## Vorschau

![Coderr Frontend Screenshot](screenshot-coderr.JPG)

## Konfiguration

Die Konfiguration befindet sich in der Datei `shared/scripts/config.js`:
- **Backend Endpoint**: Hier ist die URL des Backends hinterlegt (standardmäßig `http://127.0.0.1:8000/`).
- **Gast-Zugangsdaten**: Benutzername und Passwort für die Gast-Benutzer.  

⚠️ **Es wird empfohlen, die Datei `config.js` nicht zu verändern**, da Änderungen auch Anpassungen im Backend erfordern würden.

## Installation und Nutzung

1. **Repository klonen**  
   ```bash
   git clone git@github.com:OezkanSarikaya/coderr-frontend.git
