# Awesome Hermes Termux 🚀

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GitHub stars](https://img.shields.io/github/stars/EiomSirius/awesome-hermes-termux)](https://github.com/EiomSirius/awesome-hermes-termux/stargazers)
[![Termux](https://img.shields.io/badge/Termux-Android-brightgreen)](https://termux.dev)
[![Hermes Agent](https://img.shields.io/badge/Hermes-Agent-blue)](https://github.com/NousResearch/hermes-agent)

> **Recursos curados, verificados y funcionales para ejecutar [Hermes Agent](https://github.com/NousResearch/hermes-agent) en [Termux](https://termux.dev) (Android).**
> Cada recurso ha sido probado en Termux real. Zero humo, zero AI slop. 💯

## 📋 Contenido

- [🚀 Instalación](#-instalación)
- [⚙️ Configuración](#️-configuración)
- [📦 Skills & Plugins](#-skills--plugins)
- [🛠️ Herramientas](#️-herramientas)
- [🔧 Troubleshooting](#-troubleshooting)
- [📱 Hardware Reports](#-hardware-reports)
- [🌐 Comunidad](#-comunidad)
- [💎 Packs Premium](#-packs-premium)

---

## 🚀 Instalación

| Recurso | Descripción | Estado |
|--------|-------------|--------|
| [Hermes Agent - Instalación Oficial](https://hermes-agent.nousresearch.com/docs) | Documentación oficial de Hermes Agent | ✅ Probado |
| [Hermes Agent en Termux (Guía Rápida)](https://github.com/NousResearch/hermes-agent?tab=readme-ov-file#termux) | Guía oficial para Termux | ✅ Probado |
| [Hermes-Agent-On-Android](https://github.com/AbuZar-Ansarii/Hermes-Agent-On-Android) | Script one-line installer (130⭐) | ✅ Probado |
| [Termux Setup Guide](https://termux.dev/en/) | Documentación oficial de Termux | ✅ Probado |

### 📦 Dependencias esenciales

```bash
pkg update && pkg upgrade
pkg install python rust clang nodejs-lts git openssh termux-api
pip install hermes-agent
```

---

## ⚙️ Configuración

| Recurso | Descripción | Estado |
|--------|-------------|--------|
| [Termux:Boot](https://wiki.termux.com/wiki/Termux-boot) | Arrancar Hermes al encender el teléfono | ✅ Probado |
| [Termux:API](https://wiki.termux.com/wiki/Termux-api) | Acceso a sensores, SMS, notificaciones | ✅ Probado |
| [Termux:Widget](https://wiki.termux.com/wiki/Termux-widget) | Atajos desde pantalla de inicio | ✅ Probado |
| [Wake Lock Setup](https://wiki.termux.com/wiki/Wake_lock) | Mantener Hermes activo en background | ⚠️ Parcial |
| [Proot Distro (Ubuntu)](https://wiki.termux.com/wiki/PRoot) | Ejecutar distribuciones Linux completas | ✅ Probado |

---

## 📦 Skills & Plugins

| Recurso | Descripción | Estado |
|--------|-------------|--------|
| [Hermes Skills Hub](https://github.com/NousResearch/hermes-agent?tab=readme-ov-file#skills) | Skills oficiales de Hermes Agent | ✅ Probado |
| [Awesome Hermes Agent](https://github.com/0xNyk/awesome-hermes-agent) | Listado general de recursos Hermes (3,960⭐) | ✅ Probado |
| [Hermes Writing Agent Pack](https://eiom.gumroad.com/l/xalbn) | 5 skills para escritura automatizada (€29, 💎 Premium) | ✅ Probado |
| [MCP Server Bundle](https://eiom.gumroad.com/l/xielly) | 5 servidores MCP pre-configurados (€39, 💎 Premium) | ✅ Probado |

---

## 🛠️ Herramientas

| Recurso | Descripción | Estado |
|--------|-------------|--------|
| [Gumroad MCP Server](https://github.com/rmarescu/gumroad-mcp) | Gestiona tu tienda Gumroad desde Hermes | ✅ Probado |
| [Chrome DevTools MCP](https://github.com/NousResearch/hermes-agent) | Debug de navegador desde Hermes | ✅ Probado |
| [Playwright MCP](https://playwright.dev) | Automatización de navegador headless | ⚠️ Parcial |
| [Ollama en Termux](https://github.com/ollama/ollama) | Modelos locales en tu teléfono | ⚠️ Parcial |

---

## 🔧 Troubleshooting

| Problema | Solución |
|----------|----------|
| `jiter`/`maturin` falla en kernel 4.19 | Usar `pkg install rust` y `pip install --no-binary jiter jiter` |
| `ctranslate2` sin wheels | Usar `pip install ctranslate2 --no-binary ctranslate2` |
| `ANDROID_API_LEVEL` no detectado | `export ANDROID_API_LEVEL=$(getprop ro.build.version.sdk)` |
| /tmp no accesible | Usar `export TMPDIR=$PREFIX/tmp` |
| Hermes se duerme en background | Usar `termux-wake-lock` + Termux:Boot |
| `hermes update` lento | Usar `hermes update --no-deps` |

---

## 📱 Hardware Reports

| Dispositivo | RAM | Android | Hermes | Rendimiento |
|------------|:--:|:-------:|:------:|:----------:|
| Poco X6 Pro | 12GB | 16 | ✅ | Excelente |
| Galaxy S24 | 8GB | 14 | ✅ | Muy bueno |
| OnePlus 12 | 16GB | 14 | ✅ | Excelente |
| Pixel 8 | 8GB | 14 | ✅ | Bueno |
| Redmi Note 13 | 6GB | 13 | ⚠️ | Aceptable |

> ¿Tu dispositivo no está? ¡Abre un issue!

---

## 🌐 Comunidad

| Plataforma | Enlace |
|-----------|--------|
| Reddit Hermes | [r/hermesagent](https://reddit.com/r/hermesagent) (65k miembros) |
| Reddit Termux | [r/termux](https://reddit.com/r/termux) |
| GitHub Hermes | [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) (206k⭐) |
| Discord Nous Research | [Discord](https://discord.gg/nous-research) |

---

## 💎 Packs Premium

¿Quieres llevar Hermes en Termux al siguiente nivel? Estos packs están verificados funcionales en Termux:

| Producto | Precio | Incluye |
|----------|:-----:|--------|
| 🔥 **Termux Skills Bundle** *(próximamente)* | €9.99 | Skills pre-configuradas para Termux + scripts de setup |
| ✍️ [Hermes Writing Pack](https://eiom.gumroad.com/l/xalbn) | €29 | 5 skills de escritura automatizada |
| 🔌 [MCP Server Bundle](https://eiom.gumroad.com/l/xielly) | €39 | 5 servidores MCP listos para usar |

---

## 🤝 Contribuir

¿Probaste Hermes en tu Android y funciona? ¡Abre un PR! Las contribuciones son bienvenidas.

Cada recurso debe estar **verificado funcional** antes de incluirse.

---

## 📜 Licencia

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

*Mantenido por [Eiom](https://github.com/EiomSirius) — porque tu teléfono es más que una pantalla táctil.*