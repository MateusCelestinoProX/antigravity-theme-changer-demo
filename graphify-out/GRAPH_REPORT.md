# Graph Report - antigravity-theme-changer-demo  (2026-11-12)

## Corpus Check
- 8 files · ~83,167 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 465 nodes · 887 edges · 32 communities (26 shown, 6 thin omitted)
- Extraction: 97% EXTRACTED · 3% INFERRED · 0% AMBIGUOUS · INFERRED: 24 edges (avg confidence: 0.85)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `121320c4`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- copy
- ogl.js
- constructor
- 💻 Central de Utilitários de Terminal & Screensavers Estéticos macOS
- 🔍 Detalhamento das Rotas
- webgl-backgrounds.js
- parse
- intersectBounds
- 🏛️ Arquitetura Técnica — Google Antigravity Theme & Font Engine
- multiply
- 🎯 Gramática de Comandos do Agente
- computeFrenetFrames
- Restauração e Posicionamento do Seletor de Agentes no Google Antigravity
- ✨ Destaques da Experiência Demonstrativa
- render
- applyState
- distance
- addSegment
- loadImage
- castMouse
- Jt
- squaredDistance
- applyMatrix3
- fromQuaternion
- identity
- rotate
- applyQuaternion
- compose
- conjugate
- fromOrthogonal
- getScaling
- translate

## God Nodes (most connected - your core abstractions)
1. `constructor()` - 45 edges
2. `multiply()` - 21 edges
3. `copy()` - 20 edges
4. `sub()` - 19 edges
5. `Is()` - 19 edges
6. `🔍 Detalhamento das Rotas` - 18 edges
7. `add()` - 17 edges
8. `update()` - 14 edges
9. `parse()` - 14 edges
10. `createOptimizedRenderer()` - 14 edges

## Surprising Connections (you probably didn't know these)
- `initAcidSquares()` --calls--> `setSize()`  [EXTRACTED]
  js/webgl-backgrounds.js → js/ogl.js
- `initLightTunnel()` --calls--> `setSize()`  [EXTRACTED]
  js/webgl-backgrounds.js → js/ogl.js
- `initMoltenMetal()` --calls--> `setSize()`  [EXTRACTED]
  js/webgl-backgrounds.js → js/ogl.js
- `initTopography()` --calls--> `setSize()`  [EXTRACTED]
  js/webgl-backgrounds.js → js/ogl.js
- `initWebThreads()` --calls--> `setSize()`  [EXTRACTED]
  js/webgl-backgrounds.js → js/ogl.js

## Import Cycles
- None detected.

## Communities (32 total, 6 thin omitted)

### Community 0 - "copy"
Cohesion: 0.06
Nodes (50): add(), ce(), clone(), computeBoundingBox(), computeBoundingSphere(), v(), copy(), de() (+42 more)

### Community 1 - "ogl.js"
Cohesion: 0.05
Nodes (18): ar(), Bi(), cr(), fromAxisAngle(), fromMatrix4(), fromPerspective(), fromRotationMatrix(), Ii() (+10 more)

### Community 2 - "constructor"
Cohesion: 0.06
Nodes (46): activeTexture(), addAttribute(), an(), b(), bind(), br(), buildPlane(), constructor() (+38 more)

### Community 3 - "💻 Central de Utilitários de Terminal & Screensavers Estéticos macOS"
Cohesion: 0.06
Nodes (34): 10. fastfetch — Utilitário de Telemetria de Sistema em C, 11. Setups Multi-Painel Recomendados, 1. bottom (btm) — Monitor Gráfico em Rust, 2. weathr — Previsão Meteorológica em Arte ASCII, 3. lavat — Simulador Físico de Metaballs / Lava Lamp, 4. pipes.sh — Tubulações Tridimensionais Procedurais, 5. tty-clock — Relógio Digital ncurses de Alta Precisão, 6. donut.c — Toroide 3D Matemático Rotatório (+26 more)

### Community 4 - "🔍 Detalhamento das Rotas"
Cohesion: 0.07
Nodes (28): 0. `GET /api/ping`, 10. `POST /api/scheduler/dispatch-now`, 11. `POST /api/scheduler/toggle-agent-state`, 12. `GET /api/scheduler/conversations`, 13. `GET /api/scheduler/projects` e `POST /api/scheduler/projects/create`, 14. `POST /api/scheduler/upload-context`, 15. `GET /api/agents` e `POST /api/agents/save` / `toggle` / `delete`, 16. `GET /api/mcps` e `POST /api/mcps/save` / `toggle` / `delete` (+20 more)

### Community 5 - "webgl-backgrounds.js"
Cohesion: 0.17
Nodes (23): setSize(), buildStrandsPalette(), createOptimizedRenderer(), hexToRgb(), hexToRgbArr(), hexToVec4Arr(), initAcidSquares(), initBalatro() (+15 more)

### Community 6 - "parse"
Cohesion: 0.10
Nodes (25): addChild(), addFrustumCull(), createTexture(), loadBuffers(), onBeforeRender(), parse(), parseAccessor(), parseAnimations() (+17 more)

### Community 7 - "intersectBounds"
Cohesion: 0.10
Nodes (25): Ai(), applyMatrix4(), cross(), dot(), Dt(), Ei(), ge(), getBarycoord() (+17 more)

### Community 8 - "🏛️ Arquitetura Técnica — Google Antigravity Theme & Font Engine"
Cohesion: 0.08
Nodes (23): 1. Camada de Configuração do Usuário (`config.json`), 1. Injeção de Fontes Web via Google Fonts, 2. Ativação Forçada de Ligaduras, 2. Camada do Language Server (`antigravity_state.pbtxt`), 3. Camada de Injeção em Tempo Real (CDP), 3. Escopos de Aplicação (Dual-Scope), 🌐 Arquitetura do Servidor Local HTTP Multithread, 🏛️ Arquitetura Técnica — Google Antigravity Theme & Font Engine (+15 more)

### Community 9 - "multiply"
Cohesion: 0.13
Nodes (17): ae(), bindAttributes(), Bt(), createVAO(), di(), divide(), draw(), fe() (+9 more)

### Community 10 - "🎯 Gramática de Comandos do Agente"
Cohesion: 0.12
Nodes (15): 1. Inicialização Integrada (`init`), 2. Consulta de Estado em Tempo Real (`status`), 3. Listagem de Catálogo (`list`), 4. Troca Instantânea de Tema (`theme -[FLAG]`), 5. Troca Instantânea de Tipografia (`font -[FLAG] [-code-only]`), 6. Agendamento e Fila Autônoma (`schedule` e `queue`), 7. Gestão de MCPs e Conectores (`mcps`), 🗣️ Compreensão de Linguagem Natural (+7 more)

### Community 11 - "computeFrenetFrames"
Cohesion: 0.18
Nodes (16): computeFrenetFrames(), Ct(), findSegmentIndexAtLength(), getDerivativeAt(), getLength(), getPointAt(), getPointAtLength(), getTangentAt() (+8 more)

### Community 12 - "Restauração e Posicionamento do Seletor de Agentes no Google Antigravity"
Cohesion: 0.13
Nodes (14): 1. Contexto do Problema, 2.1 Estrutura do Frontend, 2.2 Análise do React Fiber e Árvore de Componentes, 2. Diagnóstico Técnico & Engenharia Reversa, 3.1 Eliminação do Seletor Turbo, 3.2 Realocação do Seletor de Agentes para a Barra Geral de Chat, 3.3 Habilitação Permanente do DevTools, 3. Solução Definitiva (Patch Cirúrgico no Electron) (+6 more)

### Community 13 - "✨ Destaques da Experiência Demonstrativa"
Cohesion: 0.14
Nodes (13): 1. 🎬 Tela Base & Animação Coreografada de Entrada, 2. 🎨 Catálogo Completo de 31 Temas de Elite, 3. 🔤 13 Fontes de Código com Ligaduras Nativas, 4. 🔮 Motor de Shaders Procedurais WebGL (OGL.js), 5. ⚡ Agendador, Agentes & Hub MCP com Dados Mock Sanitizados, 🏛️ Arquitetura e Engenharia, 👨‍💻 Autoria & Portfólio, 📌 Aviso Oficial de Demonstração (Frontend-Only) (+5 more)

### Community 14 - "render"
Cohesion: 0.20
Nodes (11): bindFramebuffer(), enable(), getRenderList(), render(), setDepthMask(), setStencilMask(), setViewport(), traverse() (+3 more)

### Community 15 - "applyState"
Cohesion: 0.22
Nodes (10): applyState(), disable(), setBlendEquation(), setBlendFunc(), setCullFace(), setDepthFunc(), setFrontFace(), setStencilFunc() (+2 more)

### Community 16 - "distance"
Cohesion: 0.25
Nodes (9): decompose(), determinant(), distance(), gi(), len(), me(), ne(), ot() (+1 more)

### Community 17 - "addSegment"
Cohesion: 0.40
Nodes (5): addSegment(), bezierCurveTo(), lastPoint(), lineTo(), quadraticCurveTo()

### Community 18 - "loadImage"
Cohesion: 0.50
Nodes (4): as(), hn(), loadImage(), on()

### Community 19 - "castMouse"
Cohesion: 0.50
Nodes (4): castMouse(), er(), getTranslation(), unproject()

### Community 20 - "Jt"
Cohesion: 0.50
Nodes (4): Jt(), Ms(), ws(), ys()

### Community 21 - "squaredDistance"
Cohesion: 0.67
Nodes (4): Kt(), squaredDistance(), squaredLen(), xi()

### Community 22 - "applyMatrix3"
Cohesion: 0.67
Nodes (3): applyMatrix3(), _i(), Vr()

### Community 23 - "fromQuaternion"
Cohesion: 0.67
Nodes (3): fromQuaternion(), nr(), pr()

### Community 24 - "identity"
Cohesion: 0.67
Nodes (3): gr(), identity(), Ni()

### Community 25 - "rotate"
Cohesion: 0.67
Nodes (3): rotate(), tr(), wr()

## Knowledge Gaps
- **95 isolated node(s):** `OPTIMIZED_DPR`, `📌 Aviso Oficial de Demonstração (Frontend-Only)`, `1. 🎬 Tela Base & Animação Coreografada de Entrada`, `2. 🎨 Catálogo Completo de 31 Temas de Elite`, `3. 🔤 13 Fontes de Código com Ligaduras Nativas` (+90 more)
  These have ≤1 connection - possible missing edges or undocumented components. (Counts symbols only; 136 node(s) total have ≤1 connection when file, concept and rationale nodes are included.)
- **6 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `constructor()` connect `constructor` to `copy`, `ogl.js`, `webgl-backgrounds.js`, `parse`, `intersectBounds`, `multiply`, `computeFrenetFrames`, `render`, `applyState`, `translate`?**
  _High betweenness centrality (0.019) - this node is a cross-community bridge._
- **Why does `Is()` connect `copy` to `distance`, `ogl.js`, `multiply`?**
  _High betweenness centrality (0.019) - this node is a cross-community bridge._
- **Why does `setSize()` connect `webgl-backgrounds.js` to `ogl.js`, `constructor`, `render`?**
  _High betweenness centrality (0.008) - this node is a cross-community bridge._
- **Are the 10 inferred relationships involving `constructor()` (e.g. with `b()` and `l()`) actually correct?**
  _`constructor()` has 10 INFERRED edges - model-reasoned connections that need verification._
- **What connects `OPTIMIZED_DPR`, `📌 Aviso Oficial de Demonstração (Frontend-Only)`, `1. 🎬 Tela Base & Animação Coreografada de Entrada` to the rest of the system?**
  _95 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `copy` be split into smaller, more focused modules?**
  _Cohesion score 0.058069381598793365 - nodes in this community are weakly interconnected._
- **Should `ogl.js` be split into smaller, more focused modules?**
  _Cohesion score 0.04931972789115646 - nodes in this community are weakly interconnected._