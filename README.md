# Awwwards Agent Skills 🏆

<p align="center">
  <em>The Creative Frontend Framework for AI Agents. Elevate your layouts with GSAP, WebGL, Lenis, and Barba.js.</em>
</p>

<p align="center">
  <a href="https://github.com/d2ms2/awwwards-agent-skills/stargazers"><img src="https://img.shields.io/github/stars/d2ms2/awwwards-agent-skills?style=for-the-badge&logo=github&labelColor=1e293b&color=fbbf24" alt="GitHub stars"/></a>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-fbbf24?style=for-the-badge&labelColor=1e293b" alt="MIT License"/></a>
  <a href="#installing"><img src="https://img.shields.io/badge/Tools-Codex%20%C2%B7%20Cursor%20%C2%B7%20Claude%20%C2%B7%20Antigravity-111827?style=for-the-badge&labelColor=1e293b" alt="Supported agents"/></a>
</p>

---

## 💡 What is Awwwards Agent Skills?

**Awwwards Agent Skills** is a suite of structured developer instructions (Agent Skills) designed to guide AI coding assistants (like Cursor, Claude Code, ChatGPT, and Antigravity) to build premium, high-end, highly-interactive interfaces. 

Instead of generating generic, boring SaaS layouts (Inter font, purple mesh gradient, three equal card columns), these skills force the AI to implement **Awwwards-level design principles**:
*   **Typography scaling** & asymmetry (editorial layouts).
*   **GSAP & ScrollTrigger** timelines instead of simple CSS transitions.
*   **Lenis** smooth scroll integrations.
*   **WebGL, Canvas overlays, and custom GLSL shaders** for image distortion and liquid hover effects.
*   **Seamless page transitions** (via Barba.js or framework routers) with lifecycle cleanup to prevent memory leaks.

---

## 🚀 Installing

You can install these skills directly into your workspace using the [`npx skills add`](https://github.com/vercel-labs/agent-skills) CLI tool:

### 1. Install all skills in the bundle:
```bash
npx skills add https://github.com/d2ms2/awwwards-agent-skills
```

### 2. Install a specific skill:
```bash
# Core Creative Frontend guidelines (Typography, Grid, GSAP, Lenis)
npx skills add https://github.com/d2ms2/awwwards-agent-skills --skill "awwwards-creative-frontend"

# Advanced WebGL & Shaders (Three.js, GLSL, Canvas mapping)
npx skills add https://github.com/d2ms2/awwwards-agent-skills --skill "awwwards-webgl-shaders"

# Micro-interactions & Page Transitions (Cursors, LERP physics, Barba.js)
npx skills add https://github.com/d2ms2/awwwards-agent-skills --skill "awwwards-micro-interactions"
```

*Note: You can also copy the `SKILL.md` files directly and paste them into your LLM chats or add them to your project's `.cursorrules`.*

---

## 🛠️ Available Skills

### 🏆 Interactive Engineering Skills (Our Advanced Pack)
| Skill Folder | Install Name | Description | Key Technologies |
|---|---|---|---|
| **awwwards-creative-frontend** | `awwwards-creative-frontend` | Layout typography, asymmetric grids, fluid font-scaling, GSAP, and smooth scroll integration. | HTML5, Tailwind v4, GSAP, Lenis |
| **awwwards-webgl-shaders** | `awwwards-webgl-shaders` | Setting up interactive WebGL scenes, compiling custom GLSL vertex/fragment shaders, mapping DOM items to textures, and renderer loop optimization. | Three.js, WebGL, GLSL, Canvas |
| **awwwards-micro-interactions** | `awwwards-micro-interactions` | Custom cursors with LERP delay, magnetic buttons, tactile hover states, and memory-leak-safe Barba.js transitions. | Vanilla JS, LERP, Barba.js |

### 🎨 Visual & Strategic Design Skills (Original Taste-Skill Pack)
| Skill Folder | Install Name | Description | Purpose |
|---|---|---|---|
| **taste-skill** | `design-taste-frontend` | Core v2 design rules for layouts, clean grids, and anti-default visual hygiene. | Implementation |
| **taste-skill-v1** | `design-taste-frontend-v1` | Legacy v1 design guidelines for SaaS interfaces. | Implementation |
| **minimalist-skill** | `design-taste-minimalist` | Rules for creating clean, restrained, high-end minimalist interfaces. | Implementation |
| **brutalist-skill** | `design-taste-brutalist` | Rules for generating industrial, raw, monospace brutalist UIs. | Implementation |
| **brandkit** | `brandkit` | Prompts for generating premium brand guidelines decks, logos, and identity boards. | Image Generation |
| **imagegen-frontend-web** | `design-board-builder` | Prompts for generating desktop landing page mockups and layout inspirations. | Image Generation |
| **imagegen-frontend-mobile** | `design-board-builder-mobile` | Prompts for generating mobile app screen mockups and interface layout concepts. | Image Generation |
| **image-to-code-skill** | `image-to-code` | Deep guidelines on how to accurately translate visual mockups/images into pure HTML/Tailwind CSS. | Implementation |


---

## 📖 How to Use with AI Agents (Vibe-coding guidelines)

To get the best out of these skills during a coding session:

1. **Step-by-Step Iteration:** Do not ask the AI to build the entire site at once. Start with static layouts, then add smooth scroll, then layer animations, and finally add WebGL.
2. **Context Feeding:** Feed the relevant `SKILL.md` to your coding assistant (e.g. upload it or copy-paste it) and say:
   > *"Read my design preferences from the skill file. We are starting with Step X. Make sure to avoid the standard AI templates."*
3. **Reference the Dials:** You can explicitly adjust the dials in your chat:
   > *"Set DESIGN_VARIANCE: 9 and MOTION_INTENSITY: 8 for this next section."*

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
