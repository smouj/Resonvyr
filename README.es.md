# Resonvyr

<p align="center">
  <img src="./assets/branding/logo.svg" alt="Logo de Resonvyr" width="88" />
</p>

![Language](https://img.shields.io/badge/language-Python%203.11%2B-blue)
![License](https://img.shields.io/github/license/smouj/Resonvyr)
![Last Commit](https://img.shields.io/github/last-commit/smouj/Resonvyr)
![CI](https://img.shields.io/github/actions/workflow/status/smouj/Resonvyr/ci.yml?branch=main)
[![Ko-fi](https://img.shields.io/badge/Ko--fi-Support%20this%20project-ff5f5f?logo=ko-fi&logoColor=white)](https://ko-fi.com/smouj013_dev)

<p align="center">
  <a href="./README.md"><img src="https://img.shields.io/badge/README-English-1f6feb?style=for-the-badge" alt="English"></a>
  <a href="./README.es.md"><img src="https://img.shields.io/badge/README-Español-c92a2a?style=for-the-badge" alt="Español"></a>
</p>

**Voice-to-task automation pipeline for local control.**

## Visión
Transforms speech intents into deterministic task events with local execution.

## Problema que resuelve
Voice interfaces often require cloud dependencies and high latency.

## Superpoder principal
- ⚡ **Low-latency voice intent mapping to automation actions**

## Casos de uso clave
- ✅ Hands-free commands
- ✅ Audio-driven workflows
- ✅ Intent routing
- ✅ Secure local control


## Superficie API
`WS /voice`, `GET /health`

## Stack técnico
- **Stack base:** FastAPI + local STT/TTS pipeline
- **Ejecución:** local-first, apto para self-hosting
- **Infra:** compatibilidad con Docker Compose + Caddy + Redis/Chroma/Ollama

## Estado actual (Feb 2026)
- ✅ Scaffold público disponible
- ✅ README bilingüe (EN por defecto + ES)
- ✅ Base de CI + release configurada
- 🚧 Endurecimiento de funcionalidades en progreso

## Inicio rápido
```bash
git clone https://github.com/smouj/Resonvyr.git
cd Resonvyr
python -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
python -m src.resonvyr.cli --help
```

## Documentación
- [Guía de implementación](./docs/IMPLEMENTATION.md)
- [Arquitectura](./docs/ARCHITECTURE.md)
- [Runbook](./docs/RUNBOOK.md)
- [Guía de despliegue](./docs/DEPLOYMENT.md)
- [Proceso de releases](./docs/RELEASE.md)
- [Changelog](./CHANGELOG.md)

## Contribución
Las contribuciones son bienvenidas. Lee [CONTRIBUTING.md](./CONTRIBUTING.md).

## Licencia
MIT © 2026 smouj

---

### Otras skills
Explora el ecosistema completo aquí: **[smouj/smouj](https://github.com/smouj/smouj)**

**Firma:** [@Smouj013](https://x.com/smouj013)
