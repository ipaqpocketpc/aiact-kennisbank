# EU AI Act Kennisbank

**De meest uitgebreide Nederlandse kennisbank over de EU AI Act (Verordening (EU) 2024/1689)**

Deze openbare repository bevat alle essentiële informatie over de EU AI Act, gestructureerd in JSON-formaat voor gebruik in applicaties, chatbots, en compliance tools.

## 📊 Statistieken

- **27 gestructureerde JSON bestanden**
- **180+ recitals gedocumenteerd**
- **113 artikelen geanalyseerd**
- **68 officiële definities**
- **8 sectorgidsen**
- **42+ hoog-risico use cases**

## Live Website

🌐 **[aiacteu.nl](https://aiacteu.nl)** - Interactieve website met AI-chat assistent

## Data Bestanden

### 📜 Kern Wetgeving

| Bestand | Inhoud | Artikelen |
|---------|--------|----------|
| `definitions-article-3.json` | **68 officiële definities** | Artikel 3 |
| `prohibited-practices.json` | **8 verboden AI-praktijken** | Artikel 5 |
| `articles-breakdown.json` | **Alle 113 artikelen per hoofdstuk** | Compleet |
| `recitals-key-considerations.json` | **45+ sleutel-overwegingen** | 180 recitals |

### ⚠️ Hoog-Risico AI

| Bestand | Inhoud |
|---------|--------|
| `high-risk-systems.json` | 8 gebieden, 42+ use cases |
| `annex-iii-high-risk-use-cases.json` | Gedetailleerde Bijlage III met voorbeelden |
| `risk-categories.json` | Uitleg risiconiveaus |

### 📋 Rollen & Verplichtingen

| Bestand | Inhoud |
|---------|--------|
| `roles-obligations.json` | Provider, deployer, importer, distributor, notified body |
| `transparency-obligations.json` | Artikel 50 verplichtingen |
| `gpai-requirements.json` | General-purpose AI, systemisch risico |
| `penalties.json` | Boetes: 7%/€35M, 3%/€15M, 1%/€7.5M |

### 📎 Annexen

| Bestand | Inhoud |
|---------|--------|
| `annex-i-harmonisation-legislation.json` | 20 EU productreguleringen met AI |
| `annex-ii-serious-offences.json` | Strafbare feiten voor biometrische ID |
| `annex-iii-high-risk-use-cases.json` | Complete hoog-risico use cases |
| `annex-iv-technical-documentation.json` | Technische documentatie vereisten |
| `conformity-assessment.json` | CE-markering, assessment procedures |

### 🏢 Sector-Specifieke Gidsen

| Bestand | Sectoren |
|---------|----------|
| `sector-guides.json` | **8 complete sectorgidsen:** |
| | • Gezondheidszorg |
| | • Financiële dienstverlening |
| | • HR & Recruitment |
| | • Onderwijs |
| | • Overheid & Publieke sector |
| | • Rechtshandhaving & Justitie |
| | • Technologie & AI-aanbieders |
| | • Retail & E-commerce |

### 🛠️ Implementatie & Praktijk

| Bestand | Inhoud |
|---------|--------|
| `implementation-timeline.json` | Alle deadlines 2024-2030 |
| `compliance-checklist.json` | Stap-voor-stap compliance taken |
| `ec-guidelines.json` | EC richtlijnen en Codes of Practice |
| `dutch-context.json` | Nederlandse toezicht, AP, IAMA |
| `ai-office.json` | EU AI Office structuur en taken |
| `sme-guide.json` | MKB handleiding en checklists |
| `use-cases-examples.json` | Praktijkvoorbeelden per sector |

### ❓ Referentie & FAQ

| Bestand | Inhoud |
|---------|--------|
| `faq.json` | Veelgestelde vragen (NL) |
| `glossary.json` | Begrippenlijst |
| `sources.json` | Officiële EU bronnen |
| `timeline.json` | Belangrijke datums |

## Belangrijke Deadlines

| Datum | Wat gaat in? | Status |
|-------|-------------|--------|
| **2 feb 2025** | Verboden praktijken + AI-geletterdheid | ✅ Van kracht |
| **2 aug 2025** | GPAI verplichtingen + Governance + Transparantie | ⏳ Binnenkort |
| **2 aug 2026** | Volledige hoog-risico verplichtingen | ⏳ In voorbereiding |
| **2 aug 2027** | Hoog-risico via Bijlage I productregelgeving | ⏳ Toekomst |

## Gebruik

### Raw JSON ophalen

```bash
curl https://raw.githubusercontent.com/ipaqpocketpc/aiact-kennisbank/main/data/definitions-article-3.json
```

### In JavaScript/TypeScript

```typescript
const response = await fetch(
  'https://raw.githubusercontent.com/ipaqpocketpc/aiact-kennisbank/main/data/sector-guides.json'
);
const sectorGuides = await response.json();
```

### Alle bestanden ophalen

```bash
# Clone de repository
git clone https://github.com/ipaqpocketpc/aiact-kennisbank.git

# Of download specifieke bestanden
curl -O https://raw.githubusercontent.com/ipaqpocketpc/aiact-kennisbank/main/data/articles-breakdown.json
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
