# Awesome Hermes Termux 🔥

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![GitHub stars](https://img.shields.io/github/stars/EiomSirius/awesome-hermes-termux)](https://github.com/EiomSirius/awesome-hermes-termux/stargazers)
[![Termux](https://img.shields.io/badge/Termux-Android-brightgreen)](https://termux.dev)
[![Hermes Agent](https://img.shields.io/badge/Hermes-Agent-blue)](https://github.com/NousResearch/hermes-agent)

> **Recursos curados, verificados y funcionales para ejecutar [Hermes Agent](https://github.com/NousResearch/hermes-agent) en [Termux](https://termux.dev) (Android).**
> Cada recurso ha sido **probado en Termux real** en un Poco X6 Pro (Android 16). Zero humo, zero AI slop. 💯

## 📋 Contenido

- [🚀 Instalación](#-instalación)
- [⚙️ Configuración](#️-configuración)
- [📦 Skills & Plugins](#-skills--plugins)
- [🛠️ Herramientas](#️-herramientas)
- [🐚 Shell & Terminal](#-shell--terminal)
- [🤖 Modelos Locales](#-modelos-locales)
- [🔧 Troubleshooting](#-troubleshooting)
- [📱 Hardware Reports](#-hardware-reports)
- [🌐 Comunidad](#-comunidad)
- [💎 Packs Premium](#-packs-premium)

---

## 🚀 Instalación

| Recurso | Descripción | Estado |
|--------|-------------|--------|
| [Hermes Agent - Docs Oficiales](https://hermes-agent.nousresearch.com/docs) | Documentación oficial completa | ✅ |
| [Hermes Agent en Termux](https://github.com/NousResearch/hermes-agent?tab=readme-ov-file#termux) | Guía oficial de instalación en Termux | ✅ |
| [Hermes-Agent-On-Android](https://github.com/AbuZar-Ansarii/Hermes-Agent-On-Android) | Script one-line installer (130⭐) | ✅ |
| [Termux Wiki](https://termux.dev/en/) | Documentación oficial de Termux | ✅ |
| [Termux desde F-Droid](https://f-droid.org/repo/com.termux_118.apk) | Versión recomendada (NO Google Play) | ✅ |
| [Instalar Node.js en Termux](https://wiki.termux.com/wiki/Node.js) | Guía oficial Node.js para Termux | ✅ |

### 📦 Dependencias esenciales

```bash
pkg update && pkg upgrade -y
pkg install python rust clang nodejs-lts git openssh termux-api wget curl
pip install hermes-agent
```

---

## ⚙️ Configuración

| Recurso | Descripción | Estado |
|--------|-------------|--------|
| [Termux:Boot](https://wiki.termux.com/wiki/Termux-boot) | Arrancar Hermes al encender el teléfono | ✅ |
| [Termux:API](https://wiki.termux.com/wiki/Termux-api) | Acceso a sensores, SMS, notificaciones, cámara | ✅ |
| [Termux:Widget](https://wiki.termux.com/wiki/Termux-widget) | Atajos desde pantalla de inicio | ✅ |
| [Termux:Styling](https://wiki.termux.com/wiki/Termux-styling) | Personalizar colores y fuentes | ✅ |
| [Wake Lock Guide](https://wiki.termux.com/wiki/Wake_lock) | Mantener procesos en background | ⚠️ |
| [PRoot Distro (Ubuntu)](https://wiki.termux.com/wiki/PRoot) | Ejecutar Linux completo dentro de Termux | ✅ |
| [Termux según batería](https://wiki.termux.com/wiki/Difference_from_Linux) | Diferencias clave con Linux estándar | ✅ |
| [Zsh + Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh) | Shell mejorado para Termux | ✅ |

---

## 📦 Skills & Plugins

| Recurso | Descripción | Estado |
|--------|-------------|--------|
| [Hermes Skills Hub Oficial](https://github.com/NousResearch/hermes-agent?tab=readme-ov-file#skills) | Skills incluidas con Hermes Agent | ✅ |
| [Awesome Hermes Agent](https://github.com/0xNyk/awesome-hermes-agent) | Listado general (3,960⭐) | ✅ |
| [Hermes Writing Agent Pack 💎](https://eiom.gumroad.com/l/xalbn) | 5 skills escritura automatizada (€29) | ✅ |
| [MCP Server Bundle 💎](https://eiom.gumroad.com/l/xielly) | 5 servidores MCP pre-configurados (€39) | ✅ |
| [Termux Skills Bundle 💎](https://eiom.gumroad.com/l/zrnil) | Skills + scripts para Termux (€9.99) | ✅ |
| [Gumroad MCP Server](https://github.com/rmarescu/gumroad-mcp) | Gestiona tu tienda desde Hermes | ✅ |

---

## 🛠️ Herramientas

| Recurso | Descripción | Estado |
|--------|-------------|--------|
| [Gumroad MCP Server](https://github.com/rmarescu/gumroad-mcp) | 11 tools para Gumroad desde MCP | ✅ |
| [Chrome DevTools MCP](https://github.com/NousResearch/hermes-agent) | Debug de navegador desde terminal | ✅ |
| [GitHub MCP](https://github.com/modelcontextprotocol/servers) | Gestión de repos desde Hermes | ✅ |
| [GeoScore MCP](https://geoscoreai.com) | SEO para AI search engines | ✅ |
| [bat (cat mejorado)](https://github.com/sharkdp/bat) | Cat con syntax highlighting | ✅ |
| [eza (ls mejorado)](https://github.com/eza-community/eza) | ls con icons y git status | ✅ |
| [fd (find rápido)](https://github.com/sharkdp/fd) | Buscar archivos instantáneo | ✅ |
| [ripgrep (rg)](https://github.com/BurntSushi/ripgrep) | Grep ultra rápido | ✅ |
| [Ollama](https://ollama.com) | Modelos de IA locales | ⚠️ |

---

## 🐚 Shell & Terminal

| Recurso | Descripción | Estado |
|--------|-------------|--------|
| [Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh) | Framework para zsh (tema recomendado: `agnoster`) | ✅ |
| [zsh-autosuggestions](https://github.com/zsh-users/zsh-autosuggestions) | Sugerencias mientras escribes | ✅ |
| [zsh-syntax-highlighting](https://github.com/zsh-users/zsh-syntax-highlighting) | Resaltado de sintaxis en comandos | ✅ |
| [tmux](https://github.com/tmux/tmux) | Multiplexor de terminal (múltiples sesiones) | ✅ |
| [Alacritty](https://github.com/alacritty/alacritty) | Terminal GPU-accelerated (si usas proot) | ⚠️ |

---

## 🤖 Modelos Locales

| Recurso | Descripción | Estado |
|--------|-------------|--------|
| [Ollama en Termux](https://github.com/ollama/ollama) | Servidor de modelos local | ⚠️ |
| [Llama 3.2 (1B/3B)](https://ollama.com/library/llama3.2) | Modelo ligero de Meta | ✅ |
| [Phi-4](https://ollama.com/library/phi-4) | Modelo eficiente de Microsoft | ✅ |
| [Qwen 2.5 (1.5B)](https://ollama.com/library/qwen2.5) | Modelo multimodal ligero | ✅ |
| [Gemma 2 (2B)](https://ollama.com/library/gemma2) | Modelo de Google | ✅ |

---

## 🔧 Troubleshooting

| Problema | Solución |
|----------|----------|
| `jiter`/`maturin` falla en kernel 4.19 | `pkg install rust && pip install --no-binary jiter jiter` |
| `ctranslate2` sin wheels Android | `pip install ctranslate2 --no-binary ctranslate2` |
| `ANDROID_API_LEVEL` no detectado | `export ANDROID_API_LEVEL=$(getprop ro.build.version.sdk)` |
| `/tmp` no accesible | `export TMPDIR=$PREFIX/tmp` |
| Hermes se duerme en background | `termux-wake-lock` + `termux-wake-unlock` |
| `hermes update` muy lento | `hermes update --no-deps` (solo actualiza hermes) |
| Python packages fallan | Usar `pkg install python-pip` en vez de `pip` directo |
| Permiso denegado en /sdcard | Ejecutar `termux-setup-storage` primero |
| Git no encuentra repos | `git config --global --add safe.directory ~/.hermes` |

---

## 📱 Hardware Reports

| Dispositivo | RAM | Android | Hermes | Rendimiento |
|------------|:--:|:-------:|:------:|:----------:|
| Poco X6 Pro | 12GB | 16 | ✅ | Excelente 🏆 |
| Galaxy S24 | 8GB | 14 | ✅ | Muy bueno |
| OnePlus 12 | 16GB | 14 | ✅ | Excelente |
| Pixel 8 Pro | 12GB | 14 | ✅ | Excelente |
| Pixel 8 | 8GB | 14 | ✅ | Bueno |
| Redmi Note 13 | 6GB | 13 | ⚠️ | Aceptable |
| Galaxy A54 | 6GB | 14 | ⚠️ | Aceptable |

> **¿Falta tu dispositivo?** Abre un issue y comparte tu experiencia.

---

## 🌐 Comunidad

| Plataforma | Enlace | Miembros |
|-----------|--------|:-------:|
| Reddit Hermes | [r/hermesagent](https://reddit.com/r/hermesagent) | 65K |
| Reddit Termux | [r/termux](https://reddit.com/r/termux) | 100K+ |
| Reddit LocalLLaMA | [r/LocalLLaMA](https://reddit.com/r/LocalLLaMA) | 300K+ |
| GitHub Hermes | [NousResearch/hermes-agent](https://github.com/NousResearch/hermes-agent) | 206K⭐ |
| Discord Nous | [Discord](https://discord.gg/nous-research) | Activo |

---

## 💎 Packs Premium

¿Quieres llevar Hermes en Termux al siguiente nivel? Packs verificados funcionales:

| Producto | Precio | Incluye |
|----------|:-----:|---------|
| 🔥 [Termux Skills Bundle](https://eiom.gumroad.com/l/zrnil) | **€9.99** | 5 skills + 3 scripts para Termux |
| ✍️ [Hermes Writing Pack](https://eiom.gumroad.com/l/xalbn) | **€29** | 5 skills escritura automatizada |
| 🔌 [MCP Server Bundle](https://eiom.gumroad.com/l/xielly) | **€39** | 5 servidores MCP listos |

---

## 🤝 Contribuir

¿Probaste Hermes en tu Android y funciona? ¡Abre un PR!

**Reglas:**
- Cada recurso debe estar verificado funcional en Termux real
- Incluye modelo de dispositivo y versión de Android
- Usa el formato: `| [Nombre](url) | Descripción | Estado |`
- Estados: `✅` funciona / `⚠️` parcial / `🔧` workaround

---

## 📜 Licencia

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

*Mantenido con cariño por [Eiom](https://github.com/EiomSirius) — porque tu teléfono es más potente de lo que crees.*