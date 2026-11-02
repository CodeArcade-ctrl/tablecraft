# Tablecraft

Zet CSV om in nette Markdown-, HTML- of tabgescheiden tabellen. Bekijk het resultaat voordat je het in een README, issue, document of spreadsheet plakt.

**Talen:** [English](README.md) | [Nederlands](README.nl.md)

## Functies

- Verwerkt velden tussen aanhalingstekens, dubbele aanhalingstekens en komma's binnen velden
- Exporteert Markdown, HTML en TSV
- Kies komma, puntkomma of tab als scheidingsteken
- Bepaal of de eerste rij een kopregel is
- Veilige HTML-escaping en een tekstgebaseerd tabelvoorbeeld
- Draait lokaal zonder dependencies of uploads

## Gebruiken

Open `index.html`, plak CSV, kies het scheidingsteken en klik op **Omzetten**. Je kunt op elk moment van uitvoerformaat wisselen. De pagina werkt offline.

## Publiceren met GitHub Pages

Push naar de branch `main`. De meegeleverde GitHub Actions-workflow publiceert de site naar GitHub Pages. Stel bij de repository-instellingen zo nodig **Pages > Build and deployment > Source** in op **GitHub Actions**.

## Licentie

MIT. Zie [LICENSE](LICENSE).
