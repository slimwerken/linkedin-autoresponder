# LinkedIn AutoResponder Chrome Extension

Deze Chrome-extensie automatiseert interacties op LinkedIn door:
- Automatisch reageren op comments met specifieke triggerwoorden
- Versturen van connectieverzoeken
- Plaatsen van vooraf ingestelde reacties

## Installatie

1. Download of clone deze repository
2. Open Chrome en ga naar `chrome://extensions/`
3. Activeer "Developer mode" rechtsboven
4. Klik op "Load unpacked" en selecteer de map met de extensie

## Configuratie

1. Klik op het extensie-icoon in Chrome
2. Stel in:
   - Triggerwoord
   - Connectieverzoek bericht
   - Direct bericht
   - Automatische reacties

## Bestanden

- `manifest.json`: Extensie configuratie
- `popup.html`: Gebruikersinterface
- `popup.js`: Popup logica
- `content.js`: LinkedIn pagina interactie
- `background.js`: Achtergrond processen