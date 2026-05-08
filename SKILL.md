---
name: readme-github-personalizado-pro
description: >
  Skill ULTRA COMPLETO para crear READMEs profesionales multilingües en GitHub.
  Soporte para 7 idiomas, banner interactivo con accesos directos, badges de tecnologías e IA,
  sección de modelos y datos técnicos, preguntas vía WhatsApp +526121077805, email directo,
  capturas de pantalla, GIFs, y más. Se activa al mencionar: crear README, documentar repo,
  subir proyecto a GitHub, hacer el README bonito, agregar badges, documentación profesional.
  Compatible con Claude Code, Antigravity y NoCode.
  Incluye datos de contacto, donación XRP y WhatsApp de Oscar Omar Gómez Peña.
compatibility:
  - claude
  - antigravity
  - nocode
  - cursor
  - windsurf
---

# Skill: README GitHub Personalizado — Edición PRO Multilingüe

Genera READMEs de clase mundial, visualmente hipnóticos, con soporte multi-idioma, secciones de IA, métricas técnicas, y canales de contacto directo por WhatsApp y email. Inspirado en los repositorios más estelares del ecosistema open source.

---

## 🌍 Soporte Multi-Idioma (7 idiomas)

El skill detecta automáticamente el idioma del usuario o permite seleccionarlo. Genera el README completo en cualquiera de estos idiomas:

| Idioma | Badge | Activación |
|---|---|---|
| 🇪🇸 Español | `ES` | Por defecto |
| 🇺🇸 English | `EN` | "in English", "English README" |
| 🇧🇷 Português | `PT` | "em português", "README em PT" |
| 🇫🇷 Français | `FR` | "en français", "README en FR" |
| 🇩🇪 Deutsch | `DE` | "auf Deutsch", "README auf DE" |
| 🇯🇵 日本語 | `JA` | "日本語で", "README en japonés" |
| 🇨🇳 中文 | `ZH` | "中文", "README en chino" |

**Selección visual de idiomas en el README:**
```html
<p align="center">
  <a href="README.md"><img src="https://img.shields.io/badge/🇪🇸_Español-ES-red?style=flat-square" alt="ES"/></a>
  <a href="README_EN.md"><img src="https://img.shields.io/badge/🇺🇸_English-EN-blue?style=flat-square" alt="EN"/></a>
  <a href="README_PT.md"><img src="https://img.shields.io/badge/🇧🇷_Português-PT-green?style=flat-square" alt="PT"/></a>
  <a href="README_FR.md"><img src="https://img.shields.io/badge/🇫🇷_Français-FR-lightblue?style=flat-square" alt="FR"/></a>
</p>
```
Si se solicita un idioma distinto al español, se genera el archivo correspondiente (ej. README_EN.md) y un README.md en español que enlace a los demás idiomas.

---

## 🧠 Sección de IA y Modelos

Para proyectos que utilicen inteligencia artificial, machine learning o modelos de lenguaje, se incluye esta sección:

```markdown
## 🤖 Inteligencia Artificial y Modelos

<p align="center">
  <img src="https://img.shields.io/badge/OpenAI-GPT--4o-412991?style=for-the-badge&logo=openai&logoColor=white" alt="GPT-4o"/>
  <img src="https://img.shields.io/badge/Anthropic-Claude_3.5-d97706?style=for-the-badge&logo=anthropic&logoColor=white" alt="Claude"/>
</p>

### 🧬 Arquitectura del modelo

| Componente | Tecnología | Descripción |
|---|---|---|
| 🧠 LLM Principal | GPT-4o / Claude 3.5 Sonnet | Motor de razonamiento principal |
| 🔍 Embeddings | text-embedding-3-large | Generación de vectores semánticos |
| 🗄️ Vector Store | Pinecone / Supabase pgvector | Almacenamiento de embeddings |
| ⛓️ Orquestación | LangChain / LlamaIndex | Cadena de procesamiento |
```

### 📊 Métricas del modelo

| Métrica | Valor | Benchmark |
|---|---|---|
| Precisión | 94.7% | MMLU |
| Latencia promedio | < 200ms | API local |
| Tokens procesados | 1M+ | Dataset interno |
| Tasa de alucinación | < 2% | Evaluación humana |

### 🏋️ Datos de entrenamiento / Fine-tuning

- **Dataset**: Descripción del dataset usado (tamaño, origen, licencia)
- **Técnica**: LoRA / QLoRA / Full fine-tuning
- **Épocas**: 3
- **Learning rate**: 2e-5
- **Hardware**: 1x NVIDIA A100 80GB

Si el proyecto NO usa IA, esta sección se omite o se reemplaza por una sección de Arquitectura Técnica tradicional.

---

## 📱 Sección de Contacto Directo — WhatsApp y Email

Datos fijos de Oscar Omar Gómez Peña:

- **WhatsApp**: +526121077805
- **Email**: El usuario deberá proporcionarlo, o se usará un placeholder tu@email.com

```markdown
## 💬 Preguntas y Soporte

¿Tienes dudas sobre el proyecto? ¿Quieres sugerir una funcionalidad?  
Estoy disponible para conversar directamente:

<p align="center">
  <a href="https://wa.me/526121077805?text=Hola%20Oscar%2C%20vi%20tu%20proyecto%20en%20GitHub%20y%20quisiera%20preguntarte...">
    <img src="https://img.shields.io/badge/💬_WhatsApp-Contactar-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp"/>
  </a>
  <a href="mailto:tu@email.com?subject=Consulta%20sobre%20el%20proyecto%20<repo>">
    <img src="https://img.shields.io/badge/📧_Email-Escríbeme-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
</p>

| Canal | Información | Respuesta típica |
|---|---|---|
| 💬 WhatsApp | [+52 612 107 7805](https://wa.me/526121077805) | < 4 horas |
| 📧 Email | [tu@email.com](mailto:tu@email.com) | < 24 horas |
| 🐛 Issues | [Abrir issue](https://github.com/oscaromargp/<repo>/issues/new) | < 48 horas |
```

---

## 📋 Plantilla Oficial COMPLETA

```markdown
<p align="center">
  <img src="assets/banner.png" alt="<Nombre del Proyecto>" width="100%" style="border-radius:16px; box-shadow: 0 8px 24px rgba(0,0,0,0.15);"/>
</p>

<h1 align="center"><Nombre del Proyecto></h1>

<p align="center">
  <strong><Descripción épica del proyecto, una frase que enganche></strong>
</p>

<p align="center">
  <a href="https://github.com/oscaromargp/<repo>">
    <img src="https://img.shields.io/badge/🔗_Repositorio-181717?style=for-the-badge&logo=github&logoColor=white" alt="Repo"/>
  </a>
  <a href="<URL_DEMO>">
    <img src="https://img.shields.io/badge/🌐_Demo_en_vivo-00C7B7?style=for-the-badge&logo=vercel&logoColor=white" alt="Demo"/>
  </a>
  <a href="<URL_DOCS>">
    <img src="https://img.shields.io/badge/📚_Documentación-4B8BBE?style=for-the-badge&logo=readthedocs&logoColor=white" alt="Docs"/>
  </a>
  <a href="https://wa.me/526121077805">
    <img src="https://img.shields.io/badge/💬_WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp"/>
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/license-MIT-blue?style=for-the-badge" alt="License"/>
  <img src="https://img.shields.io/github/stars/oscaromargp/<repo>?style=for-the-badge&color=yellow" alt="Stars"/>
  <img src="https://img.shields.io/github/forks/oscaromargp/<repo>?style=for-the-badge&color=blue" alt="Forks"/>
  <img src="https://img.shields.io/badge/status-active-brightgreen?style=for-the-badge" alt="Status"/>
  <img src="https://img.shields.io/badge/PRs-welcome-orange?style=for-the-badge" alt="PRs"/>
</p>

---

## 📖 Acerca del Proyecto

<Descripción detallada: problema que resuelve, para quién es, por qué es diferente.>

---

## ✨ Características

| Característica | Descripción |
|---|---|
| ⚡ <Feature 1> | <Descripción breve> |
| 🔒 <Feature 2> | <Descripción breve> |
| 🌐 <Feature 3> | <Descripción breve> |

---

## 📸 Capturas de pantalla

<p align="center">
  <img src="assets/screenshot-1.png" alt="Pantalla principal" width="700" style="border-radius:8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);"/>
</p>

---

## 🚀 Comenzando

### Prerrequisitos

| Herramienta | Versión | Instalación |
|---|---|---|
| Node.js | >= 18.x | [nodejs.org](https://nodejs.org) |
| npm / yarn | >= 9.x | Incluido con Node |

### Variables de entorno

Crea un archivo `.env` basado en `.env.example`:

```env
DATABASE_URL="postgresql://user:pass@localhost:5432/db"
OPENAI_API_KEY="sk-..."
```

### Instalación

```sh
git clone https://github.com/oscaromargp/<repo>.git
cd <repo>
npm install
cp .env.example .env
npm run dev
```

---

## 💡 Uso

### Ejemplo rápido

```javascript
import { funcionalidad } from 'proyecto'

const resultado = await funcionalidad({
  param1: 'valor',
  param2: 123
})

console.log(resultado)
// Output: { success: true, data: {...} }
```

---

## 🤝 Contribuyendo

¡Las contribuciones son lo que hace grande al open source!

```
1. Fork del repositorio
2. Crea tu rama (git checkout -b feature/increible)
3. Commit de tus cambios (git commit -m 'feat: algo increible')
4. Push a la rama (git push origin feature/increible)
5. Abre un Pull Request
```

---

## 💬 Preguntas y Soporte

<p align="center">
  <a href="https://wa.me/526121077805?text=Hola%20Oscar%2C%20vi%20tu%20proyecto%20<repo>%20y%20quisiera%20preguntarte...">
    <img src="https://img.shields.io/badge/💬_WhatsApp-+52_612_107_7805-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp"/>
  </a>
  <a href="mailto:tu@email.com?subject=Consulta%20sobre%20<repo>">
    <img src="https://img.shields.io/badge/📧_Email-Escríbeme-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
  </a>
  <a href="https://github.com/oscaromargp/<repo>/issues/new">
    <img src="https://img.shields.io/badge/🐛_Issues-Reportar-181717?style=for-the-badge&logo=github&logoColor=white" alt="Issues"/>
  </a>
</p>

---

## 💖 Apoya este Proyecto

Si este proyecto te fue útil, considera apoyarlo.

<p align="center">
  <strong>Donaciones en XRP</strong><br><br>
</p>

> Dirección XRP: `rBthUCndKy3Xbb19Ln4xkZeMwusX9NrYfj`

---

## 📄 Licencia

Distribuido bajo la licencia MIT. Consulta [LICENSE](LICENSE) para más información.

---

## 📬 Contacto

<p align="center">
  <strong>Oscar Omar Gómez Peña</strong>
</p>

<p align="center">
  <a href="https://oscaromargp.github.io/Oscaromargp/">
    <img src="https://img.shields.io/badge/🌐_Portafolio-Visitar-blueviolet?style=for-the-badge&logo=githubpages&logoColor=white" alt="Portafolio"/>
  </a>
  <a href="https://github.com/oscaromargp">
    <img src="https://img.shields.io/badge/GitHub-@oscaromargp-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://wa.me/526121077805">
    <img src="https://img.shields.io/badge/WhatsApp-Contactar-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp"/>
  </a>
</p>

---

## 🙏 Agradecimientos

<p align="center">
  <br/>
  <em>
    "Porque Dios es el que en vosotros produce<br/>
    así el querer como el hacer,<br/>
    por su buena voluntad."
  </em>
  <br/>
  <strong>— Filipenses 2:13</strong>
  <br/><br/>
  Todo lo que aquí existe nació primero como un deseo en el corazón.<br/>
  Cada proyecto, cada línea, cada idea que toma forma —<br/>
  es un regalo de Aquel que nos dio tanto el sueño como la fuerza de alcanzarlo.<br/>
  <strong>A Dios, toda la gloria.</strong>
  <br/>
</p>
```

---

## 🔧 Proceso de generación

1. **DETECTAR IDIOMA**
   - ¿El usuario pidió idioma específico? → Usar ese
   - Sino → Español por defecto

2. **RECOPILAR DATOS**
   - Nombre del proyecto, descripción, tecnologías
   - ¿Tiene demo en vivo? URL
   - ¿Tiene capturas/GIFs? (sino → placeholders)
   - ¿Usa IA/ML? → Activar sección 🤖
   - ¿Quiere mostrar benchmarks? → Activar sección 📊
   - Email de contacto (obligatorio para la sección 💬)
   - URL del repo: https://github.com/oscaromargp/<repo>

3. **GENERAR BADGES**
   - Badges de estado (license, stars, forks, status)
   - Badges de tecnologías (con logos oficiales)
   - Badges de acceso (repo, demo, docs, WhatsApp)
   - Badges de IA (si aplica)

4. **CREAR CARPETA assets/**
   - assets/README_IMAGES.md explicando imágenes necesarias

5. **GENERAR ARCHIVO(S) README**
   - README.md en el idioma principal
   - README_XX.md para cada idioma adicional solicitado

6. **CONFIRMAR CON USUARIO** antes de guardar

---

## ⚠️ Datos fijos (NUNCA modificar)

| Dato | Valor |
|---|---|
| 👤 Autor | Oscar Omar Gómez Peña |
| 🐙 GitHub | @oscaromargp |
| 🌐 Portafolio | https://oscaromargp.github.io/Oscaromargp/ |
| 💎 XRP Address | rBthUCndKy3Xbb19Ln4xkZeMwusX9NrYfj |
| 📱 WhatsApp | +526121077805 |
| 🔗 Wa.me link | https://wa.me/526121077805 |
| 📧 Email | Solicitar al usuario (placeholder: tu@email.com) |
| 📜 Licencia | MIT (a menos que el usuario especifique otra) |
| ✝️ Versículo | Filipenses 2:13 |
| 🎨 Idioma por defecto | Español |

---

## 📦 Archivos generados

| Archivo | Contenido |
|---|---|
| README.md | README principal en el idioma por defecto |
| README_EN.md | Versión en inglés (si se solicita) |
| README_PT.md | Versión en portugués (si se solicita) |
| README_FR.md | Versión en francés (si se solicita) |
| assets/README_IMAGES.md | Guía para crear las imágenes necesarias |
| CONTRIBUTING.md | Guía de contribución (si se solicita) |