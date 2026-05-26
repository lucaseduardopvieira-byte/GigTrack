<div align="center">

```
 ██████╗ ██╗ ██████╗ ████████╗██████╗  █████╗  ██████╗██╗  ██╗
██╔════╝ ██║██╔════╝ ╚══██╔══╝██╔══██╗██╔══██╗██╔════╝██║ ██╔╝
██║  ███╗██║██║  ███╗   ██║   ██████╔╝███████║██║     █████╔╝ 
██║   ██║██║██║   ██║   ██║   ██╔══██╗██╔══██║██║     ██╔═██╗ 
╚██████╔╝██║╚██████╔╝   ██║   ██║  ██║██║  ██║╚██████╗██║  ██╗
 ╚═════╝ ╚═╝ ╚═════╝    ╚═╝   ╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝╚═╝  ╚═╝
```

**Controle financeiro para motoristas de aplicativo**

![Status](https://img.shields.io/badge/status-active-brightgreen?style=flat-square&color=00d4aa&labelColor=0a0f1e)
![PWA](https://img.shields.io/badge/PWA-ready-brightgreen?style=flat-square&color=ffffff&labelColor=0a0f1e)
![Offline](https://img.shields.io/badge/offline-supported-brightgreen?style=flat-square&color=888888&labelColor=0a0f1e)
![License](https://img.shields.io/badge/license-MIT-brightgreen?style=flat-square&color=444444&labelColor=0a0f1e)

</div>

---

## `// SOBRE O PROJETO`

**GigTrack** é uma aplicação web progressiva (PWA) desenvolvida para motoristas de plataformas como **Uber**, **99**, **iFood** e **InDriver** que precisam de controle financeiro simples, rápido e eficiente diretamente pelo celular.

Sem cadastro. Sem servidor. Sem mensalidade. Os dados ficam no **seu dispositivo**.

---

## `// FUNCIONALIDADES`

```
✦  Registro de ganhos por corrida e plataforma
✦  Controle de despesas (combustível, manutenção, alimentação, etc.)
✦  Dashboard com lucro líquido do dia em tempo real
✦  Histórico filtrado por Hoje / Semana / Mês
✦  Gráfico de ganhos dos últimos 7 dias
✦  Metas diárias e mensais com barra de progresso
✦  Breakdown de receita por plataforma
✦  Funciona 100% offline após instalação
✦  Instalável como app nativo no Android e iOS
```

---

## `// STACK`

| Tecnologia | Uso |
|---|---|
| `HTML5` | Estrutura e semântica |
| `CSS3` | Estilização, animações, dark mode nativo |
| `JavaScript ES6+` | Lógica, cálculos, renderização dinâmica |
| `Chart.js` | Visualização de dados |
| `LocalStorage` | Persistência de dados no dispositivo |
| `Service Worker` | Suporte offline e cache |
| `Web App Manifest` | Instalação como PWA |

---

## `// INSTALAÇÃO`

### Opção 1 — GitHub Pages (recomendado)

```bash
# 1. Clone o repositório
git clone https://github.com/seu-usuario/GigTrack.git

# 2. Acesse via navegador
# https://seu-usuario.github.io/GigTrack
```

### Opção 2 — Local

```bash
# Qualquer servidor estático funciona
npx serve .

# ou
python -m http.server 8080
```

> ⚠️ **Importante:** O Service Worker só registra em `localhost` ou conexões `HTTPS`. Não abra o `index.html` direto pelo sistema de arquivos.

---

## `// COMO USAR NO CELULAR`

**Android (Chrome)**
```
Menu ⋮  →  "Adicionar à tela inicial"  →  Instalar
```

**iOS (Safari)**
```
Compartilhar  →  "Adicionar à tela de início"  →  Adicionar
```

---

## `// ESTRUTURA`

```
GigTrack/
│
├── index.html       → App principal (single file)
├── sw.js            → Service Worker (cache e offline)
├── manifest.json    → Configuração PWA
└── README.md        → Documentação
```

---

## `// PLATAFORMAS SUPORTADAS`

```
  UBER  ·  99  ·  IFOOD  ·  INDRIVER  ·  OUTROS
```

---

## `// ROADMAP`

- [ ] Exportação de relatório em CSV
- [ ] Controle de quilometragem rodada
- [ ] Ganho por hora trabalhada
- [ ] Notificações de metas atingidas
- [ ] Backup e restauração de dados

---

## `// LICENÇA`

```
MIT License — livre para uso, modificação e distribuição.
```

---

<div align="center">

**Desenvolvido para quem vive na estrada.**

`GigTrack © 2026`

</div>
