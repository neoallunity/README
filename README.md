# 🌟 NeoAllUnity Organization

**Professional Academic Publishing Platform** - Unified ecosystem for scholarly content processing

## 🎯 Our Mission

Empowering academic institutions, researchers, and content creators with elegant, powerful tools for modern scholarly publishing and content management.

## 🏗️ Repository Structure

The eight former `integral-philosophy-*` repositories were consolidated into one canonical monorepo and are archived read-only. Current structure:

```text
neoallunity/
├── integral-philosophy/     # CANON: modules/{cli,config,content,core,deploy,docs,tests,web}
├── allunity-wagtail/        # CMS rebuild of AllUnity.ru
├── Magazine/                # historical publishing snapshot
├── allunity-{knigi,zhurnaly,diskussii}/  # media mirrors, rights pending
└── .github/, README/        # organization metadata
```

## 📦 Quick Links

- **Canonical code**: [integral-philosophy](https://github.com/neoallunity/integral-philosophy) — use `modules/*`, not the archived one-repository-per-module projects.
- **CMS**: [allunity-wagtail](https://github.com/neoallunity/allunity-wagtail)
- **Media mirrors**: read-only until content rights are confirmed.

## 🎯 Core Philosophy

### 🔬 **Academic Excellence**
- TEI P5 compliance for scholarly publishing
- Support for multiple academic formats
- Citation and bibliography management
- Content integrity and validation

### 🏗️ **Modern Architecture**
- Microservices-based design
- Container-first development
- API-first approach
- Event-driven communication

## 🚀 Quick Start

### Complete System Setup
\`\`\`bash
# Clone the complete system with all components
git clone --recursive https://github.com/neoallunity/integral-philosophy.git
cd integral-philosophy

# Install all components
./setup-all.sh

# Start full development environment
./start-full.sh
\`\`\`

## 📄 License

All NeoAllUnity projects are licensed under **MIT License** for maximum compatibility and reuse.

---

**🌟 NeoAllUnity - Empowering Academic Excellence Through Technology** 🌟
