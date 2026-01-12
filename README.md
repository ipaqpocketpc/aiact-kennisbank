# EU AI Act Kennisbank

**De meest uitgebreide Nederlandse kennisbank over de EU AI Act (Verordening (EU) 2024/1689)**

Deze openbare repository bevat alle essentiële informatie over de EU AI Act, gestructureerd in JSON-formaat voor gebruik in applicaties, chatbots, en compliance tools.

## Live Website

🌐 **[aiacteu.nl](https://aiacteu.nl)** - Interactieve website met AI-chat assistent

## Data Bestanden

### Kern Wetgeving

| Bestand | Inhoud | Artikelen |
|---------|--------|----------|
| `definitions-article-3.json` | **68 officiële definities** | Artikel 3 |
| `prohibited-practices.json` | **8 verboden AI-praktijken** | Artikel 5 |
| `high-risk-systems.json` | **8 gebieden, 42+ use cases** | Annex III |
| `transparency-obligations.json` | Transparantieverplichtingen | Artikel 50 |
| `conformity-assessment.json` | CE-markering, procedures | Artikelen 40-49 |

### Rollen & Verplichtingen

| Bestand | Inhoud |
|---------|--------|
| `roles-obligations.json` | Provider, deployer, importer, distributor, notified body |
| `gpai-requirements.json` | General-purpose AI verplichtingen, systemisch risico |
| `penalties.json` | Boetes: 7%/€35M, 3%/€15M, 1%/€7.5M |

### Annexen

| Bestand | Inhoud |
|---------|--------|
| `annex-i-harmonisation-legislation.json` | 20 EU productreguleringen met AI |
| `annex-ii-serious-offences.json` | Strafbare feiten voor biometrische identificatie |
| `annex-iv-technical-documentation.json` | Technische documentatie vereisten |

### Implementatie & Praktijk

| Bestand | Inhoud |
|---------|--------|
| `implementation-timeline.json` | Alle deadlines 2024-2030 |
| `ec-guidelines.json` | EC richtlijnen en Codes of Practice |
| `dutch-context.json` | Nederlandse toezicht, AP guidance, IAMA |
| `ai-office.json` | EU AI Office structuur en taken |
| `sme-guide.json` | MKB handleiding en checklists |
| `faq.json` | Veelgestelde vragen (NL) |
| `use-cases-examples.json` | Praktijkvoorbeelden per sector |

### Referentie

| Bestand | Inhoud |
|---------|--------|
| `glossary.json` | Begrippenlijst |
| `risk-categories.json` | Risicocategorieën uitleg |
| `sources.json` | Officiële EU bronnen |
| `timeline.json` | Belangrijke datums |

## Belangrijke Deadlines

| Datum | Wat gaat in? |
|-------|-------------|
| **2 feb 2025** | ✅ Verboden praktijken + AI-geletterdheid |
| **2 aug 2025** | ⏳ GPAI verplichtingen + Governance |
| **2 aug 2026** | ⏳ Hoog-risico + Transparantie |
| **2 aug 2027** | ⏳ Volledige toepassing |

## Gebruik

### Raw JSON ophalen

```bash
curl https://raw.githubusercontent.com/ipaqpocketpc/aiact-kennisbank/main/data/definitions-article-3.json
```

### In JavaScript/TypeScript

```typescript
const response = await fetch(
  'https://raw.githubusercontent.com/ipaqpocketpc/aiact-kennisbank/main/data/faq.json'
);
const faq = await response.json();
```

## Automatische Monitoring

GitHub Action controleert dagelijks om 9:00 (NL tijd) op nieuwe EU publicaties.
Bij updates wordt automatisch een GitHub Issue aangemaakt.

## Bronnen

Alle data is afkomstig van officiële bronnen:

- [EUR-Lex AI Act](https://eur-lex.europa.eu/legal-content/EN/TXT/HTML/?uri=CELEX:32024R1689)
- [EC Digital Strategy](https://digital-strategy.ec.europa.eu/en/policies/regulatory-framework-ai)
- [Autoriteit Persoonsgegevens](https://www.autoriteitpersoonsgegevens.nl/themas/algoritmes-ai/ai-verordening)
- [EU AI Office](https://digital-strategy.ec.europa.eu/en/policies/ai-office)

## Bijdragen

Suggesties en correcties zijn welkom via Issues of Pull Requests.

## Licentie

CC0 1.0 - Vrij te gebruiken voor elk doel.

---

**Onderhouden door [aiklik.nl](https://aiklik.nl)** | **Website: [aiacteu.nl](https://aiacteu.nl)**
