# Automatische Monitoring

Elke dag om 9:00 (NL tijd) checkt een GitHub Action automatisch op nieuwe EU AI Act publicaties.

## Hoe werkt het?

1. GitHub Action draait dagelijks
2. Checkt AI Office nieuws pagina
3. Vergelijkt met vorige check
4. Als er iets nieuws is → maakt een GitHub Issue aan

## Melding ontvangen

Je krijgt automatisch een melding via:
- GitHub notificaties (als je "Watch" aan hebt staan op de repo)
- Email (als je GitHub email notificaties aan hebt)

## Handmatig checken

1. Ga naar [Actions](../../actions)
2. Selecteer "Monitor EU AI Act Sources"
3. Klik "Run workflow"

## Wat wordt gecheckt?

| Bron | Frequentie |
|------|------------|
| [AI Office News](https://digital-strategy.ec.europa.eu/en/news?topic=135) | Dagelijks |
