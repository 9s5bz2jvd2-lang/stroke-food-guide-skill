# Nutrition Science | Stroke Nutrition Guide

English version translated from the existing Chinese README.

An AI popular-science conversation assistant based on the **Dietary and Nutrition Guide for Adults After Stroke (2026 Edition)** issued by the **General Office of the National Health Commission**. | Nutrition Science Skill

> 🌱 I am new to AI and hope to use AI to share nutrition knowledge and help more people. If anything is insufficient, feedback is welcome. I will keep working on more nutrition-science skills. If you find this useful, please consider giving it a ⭐ Star. Thank you!

---

## Guideline Source

- **Full title**: *Dietary and Nutrition Guide for Adults After Stroke (2026 Edition)*
- **Issuing organization**: General Office of the National Health Commission

## Features

- **Swallowing safety**: water-swallow test self-check, food-texture levels, and thickener guidance
- **Dietary-nutrition principles**: detailed interpretation and practical advice for 8 official principles
- **Nutrition management**: precise energy, protein, fat, and carbohydrate intake; DASH dietary pattern
- **TCM dietary support**: 4 syndrome patterns, 4 constitutions, and seasonal health preservation
- **Regional menus**: 7 regions × 4 seasons × 3 energy levels
- **Rehabilitation guidance**: activity can begin as early as 48 hours when appropriate; exercise, swallowing, and language training
- **Winter warning**: stroke is more common in winter; keep warm and prevent recurrence
- **Popular-science style**: plain language, concrete quantities, and myth correction—precise without being condescending

## Quick Reference

| Item | Recommendation | Plain-language explanation |
|------|----------------|----------------------------|
| Salt | <5 g/day | About one beer-bottle cap |
| Cooking oil | ≤25 g/day | No more than about two tablespoons |
| Water | 1500–1700 mL/day | About three bottles of mineral water |
| Protein (general) | ≥1.0 g/kg/day | At least 60 g for 60 kg |
| Protein (infection/pressure injury) | 1.2–1.5 g/kg/day | Increase supplementation |
| Fat energy share | 20%–30% | Less oil and fatty meat |
| Carbohydrate energy share | 50%–65% | Add coarse grains to staple foods |
| Dietary fiber | 25–30 g/day | Helps prevent constipation |

## Knowledge System

| KPK ID | Topic | Source section |
|--------|-------|----------------|
| KPK-01~08 | Eight dietary-nutrition principles | Dietary-nutrition principles chapter |
| KPK-09~15 | Food choices, exchange tables, menus, formulas, swallowing assessment, texture levels, terminology | Appendices |
| KPK-16~18 | Disease definition, TCM understanding, and guideline use | Preface + disease characteristics + Q&A |

## File Structure

```text
- skill.yaml: Skill configuration
- system_prompt.md: System prompt with swallowing-safety priority
- knowledge_base.md: KPK knowledge base with 18 knowledge points
- recipes_data.md: 7 regions and 84 complete menus
- recipes_overview.md: Menu overview and usage guide
- README.md: Chinese README
- install.sh: Linux/macOS install script
- install.bat: Windows install script
```

## Statement

**Disclaimer**:
1. All content comes from the guideline above and is for dietary-nutrition popular-science reference only; it does not replace medication treatment or professional medical diagnosis.
2. It mainly applies to people in stroke recovery and sequelae stages; acute or critically ill patients require professional treatment guidance.
3. Swallowing-disorder assessment must be performed by professionals; information here is for reference only.
4. Food-medicine substances and nutrition supplements should be used under professional guidance and not taken in excessive amounts.
5. People with hypertension, diabetes, kidney disease, or other underlying conditions should receive professional physician and nutrition guidance.
6. This skill was built with AI assistance. Although it aims to stay faithful to the original guideline, paraphrasing errors may exist. If there is any doubt, please refer to the official published guideline text.


## Creator

**Runyuan Wang**
- Chinese Registered Dietitian
- M.S. in Nutrition and Food Hygiene, Kunming Medical University
- Built with WorkBuddy

## License

MIT
