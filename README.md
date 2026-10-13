# LOES AI B*tch - Salespage Generator

Claude-plugin van Loes (letsgetloes.nl). LOES AI B*tch schrijft samen met jou je Ideale Salespagina, blok voor blok.

## Installeren

**In Claude (desktop of web):** Instellingen, Plugins, marketplace toevoegen met `Loes-AI/salespage-generator`, daarna de plugin **salespage-generator** installeren.

**In Claude Code:**

```
/plugin marketplace add Loes-AI/salespage-generator
/plugin install salespage-generator@loes-ai
```

Bij installatie wordt de koppeling met de server van Loes meegeleverd. Sta die toe als Claude erom vraagt; zonder die koppeling kan LOES de vragen en schrijfinstructies per blok niet ophalen.

## Gebruiken

Begin een gesprek met "salespagina", "verkooppagina" of "help me met mijn salestekst", of roep de skill aan met `/salespage-generator`. LOES neemt het vanaf daar over.

## Wat zit erin

- `plugins/salespage-generator/skills/salespage-generator/SKILL.md`: LOES zelf (persona, flow per blok, documentopbouw)
- `plugins/salespage-generator/.mcp.json`: de koppeling met de server die per blok de vragen en schrijfinstructies levert
