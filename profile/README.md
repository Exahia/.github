# Exahia — Infrastructure IA Souveraine B2B

> **"Sovereignty as a Service"** — L'IA d'entreprise sans compromis sur la souveraineté des données.

## Le Problème : Shadow AI

**49% des employés** utilisent des outils IA non autorisés au travail. **87% des cabinets juridiques** ont des collaborateurs qui utilisent ChatGPT sur des données sensibles. Chaque prompt envoyé à un service cloud américain expose potentiellement des données confidentielles aux serveurs soumis au **Cloud Act**.

Pour les secteurs réglementés — juridique, santé, finance, défense — c'est un dilemme entre **productivité** et **conformité**.

## La Solution : IA Souveraine Managée

Exahia déploie des **modèles open-source** (Mistral, Llama, Qwen, DeepSeek) sur du **hardware bare-metal OVHcloud en France**. Aucune donnée ne quitte le territoire. Aucune donnée n'est persistée.

### Badges (en texte, pas d'images)

🇫🇷 Made in France · 🔒 RGPD Natif · 🛡️ Zero Retention · ☁️ Cloud Act Free · 🏗️ OVHcloud Bare-Metal

### Stack Technique

| Composant | Technologie |
|-----------|-------------|
| **Inférence** | vLLM (API compatible OpenAI) |
| **Hébergement** | OVHcloud bare-metal (France) |
| **GPUs** | Nvidia L4, L40S, H100 |
| **Sécurité PII** | Presidio + spaCy (détection PII français, <2ms) |
| **Interface** | Open WebUI (ChatGPT-like) |
| **Orchestration** | Docker Compose + Traefik |

### Offres

| Offre | Type | Cible | GPU |
|-------|------|-------|-----|
| **ACCESS** | GPU mutualisé | Freelances, petites équipes | L40S partagé |
| **BUNKER** | Instance dédiée | PME, ETI | L4 / L40S / H100 |
| **ENTERPRISE** | Sur mesure | CAC40, secteur public | Cluster custom |

### Comparaison vs Alternatives

| Critère | Exahia | OpenAI/ChatGPT | Azure OpenAI | Mistral (Le Chat) | Scaleway |
|---------|--------|----------------|--------------|-------------------|----------|
| Hébergement France | ✅ OVHcloud | ❌ USA | ❌ USA/Irlande | ⚠️ Partiel | ✅ France |
| Cloud Act Free | ✅ | ❌ | ❌ | ⚠️ | ✅ |
| Zero Retention | ✅ RAM only | ❌ | ❌ | ⚠️ | ❌ |
| Modèles Open-Source | ✅ | ❌ Propriétaire | ❌ | ✅ | ✅ |
| Interface ChatGPT-like | ✅ | ✅ | ✅ | ✅ | ❌ |
| RAG intégré | ✅ | ⚠️ Limité | ⚠️ | ❌ | ❌ |
| Détection PII | ✅ Automatique | ❌ | ❌ | ❌ | ❌ |
| Instance dédiée | ✅ BUNKER | ❌ | ⚠️ | ❌ | ✅ |

### Secteurs Cibles

- **Juridique** — Secret professionnel, analyse de contrats, jurisprudence
- **Santé** — Données patients (Art. 9 RGPD), comptes-rendus médicaux
- **Finance** — Conformité AMF/ACPR, analyse documentaire, MiFID II / DORA
- **Défense & Industrie** — Brevets, R&D, données classifiées
- **Secteur Public** — Administrations, collectivités, conformité RGPD stricte

### Nos Repos Open-Source

| Repo | Description |
|------|-------------|
| [exahia](https://github.com/Exahia/exahia) | Présentation complète de la plateforme |
| [pii-detector-fr](https://github.com/Exahia/pii-detector-fr) | Détection et anonymisation de PII françaises |
| [llm-benchmark-fr](https://github.com/Exahia/llm-benchmark-fr) | Benchmarks LLM sur tâches métier françaises |
| [shadow-ai-audit](https://github.com/Exahia/shadow-ai-audit) | Audit Shadow AI pour DSI/RSSI |

---

**🌐 [exahia.com](https://exahia.com)** · 📧 admin@exahia.ia
