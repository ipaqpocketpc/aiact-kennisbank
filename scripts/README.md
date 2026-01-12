# Monitoring Scripts

Automatische monitoring van EU AI Act bronnen.

## Opties

### 1. GitHub Action (Aanbevolen)

Automatisch actief in deze repo. Checkt wekelijks op maandag.

**Handmatig triggeren:**
1. Ga naar Actions tab
2. Selecteer "Monitor EU AI Act Sources"
3. Klik "Run workflow"

### 2. n8n Workflow

Importeer `n8n-monitoring-workflow.json` in je n8n instance.

**Setup:**
1. Importeer workflow in n8n
2. Configureer GitHub credentials
3. (Optioneel) Configureer Slack webhook
4. Activeer workflow

## Wat wordt gemonitord?

| Bron | URL | Frequentie |
|------|-----|------------|
| AI Office News | digital-strategy.ec.europa.eu | Wekelijks |
| EUR-Lex Updates | eur-lex.europa.eu | Wekelijks |

## Output

Bij nieuwe publicaties:
- GitHub Issue wordt aangemaakt
- (Optioneel) Slack notificatie
- (Optioneel) Email notificatie
