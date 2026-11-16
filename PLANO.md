# 📋 Plano do projeto: laboratorio2-pc

_Gerado em 16/11/2026, 20:22:38 — sem IA, lendo os arquivos._

## 📊 Visão geral
| Item | Valor |
|---|---|
| Arquivos | 70 |
| Linhas | 16.796 |
| Telas/páginas | 4 |
| Rotas do backend | 0 |
| Chamadas do app | 0 |
| Tabelas do banco | 0 |
| Variáveis de ambiente | 6 |

**Linguagens:** JavaScript (53), HTML (4), Outros (3), Markdown (3), Imagem (2), JSON (2), YAML (1), CSS (1), Python (1)

## 💡 O que fazer (em ordem)
1. 🧹 Tirar a Replit de 5 arquivo(s) (🏗️ Preparar → Fazer tudo)
2. 🔐 Criar um .env.example com: DADOS_EM, LOCALAPPDATA, PONTE_BASE, PONTE_CODIGO, PONTE_PORTA, TESTE_SAIR (os valores você coloca no servidor, nunca no código)
3. 📝 Criar um README.md explicando como rodar

## 🚀 Por onde começa
- `app/ferramentas/meu-chat/index.html`
- `app/index.html`

## ⌨️ Comandos (package.json)
| Pasta | Comando | O que roda |
|---|---|---|
| . | `npm run programa` | `electron .` |
| . | `npm run exe` | `electron-builder --win nsis portable --x64 --publish never` |

## 📱 Telas e páginas
| Endereço | Arquivo |
|---|---|
| `app/ferramentas/colador.html` | app/ferramentas/colador.html |
| `app/ferramentas/meu-chat/index.html` | app/ferramentas/meu-chat/index.html |
| `app/index.html` | app/index.html |
| `electron/navegador.html` | electron/navegador.html |

## 🖥️ Rotas do backend
_Nenhum encontrado._

## 📡 O que o app pede ao servidor
_Nenhum encontrado._

## 🔌 O que falta no backend
✅ Tudo que o app chama tem rota no projeto (ou o app não usa servidor).

## 🗄️ Banco de dados
_Nenhuma tabela encontrada._

## 🔐 Variáveis de ambiente (configurar no servidor)
- `DADOS_EM`
- `LOCALAPPDATA`
- `PONTE_BASE`
- `PONTE_CODIGO`
- `PONTE_PORTA`
- `TESTE_SAIR`

_Só os nomes. Os valores (chaves, senhas) nunca vão no código nem no GitHub._

## 🤖 IA usada
- generativelanguage.googleapis.com
- api.groq.com
- console.groq.com
- openrouter.ai
- api.openai.com
- platform.openai.com
- api.anthropic.com
- console.anthropic.com

## 🌐 Serviços de fora que ele acessa
- aistudio.google.com
- api-dashboard.search.brave.com
- api.anthropic.com
- api.deepseek.com
- api.groq.com
- api.npmjs.org
- api.openai.com
- api.perplexity.ai
- api.search.brave.com
- api.tavily.com
- app.tavily.com
- cdn.jsdelivr.net
- cdn.tailwindcss.com
- console.anthropic.com
- console.groq.com
- data.jsdelivr.com
- esm.sh
- generativelanguage.googleapis.com
- github.com
- google.serper.dev
- meuchat.local
- nodejs.org
- ollama.com
- openrouter.ai
- platform.deepseek.com
- platform.openai.com
- r.jina.ai
- raw.github.com
- raw.githubusercontent.com
- registry.npmjs.org
- serper.dev
- stuartk.com
- stuk.github.io
- unpkg.com
- www.npmjs.com
- www.perplexity.ai

## 📦 Peças principais (dependências)
`msedge-tts` · `ws`

## 🧹 Arquivos com coisa da Replit
- app/ferramentas/meu-chat/js/33-contextos.js
- app/ferramentas/meu-chat/js/lib/guia-maikon.js
- app/js/15a-tar.js
- app/js/16-lab-ferramentas.js
- app/js/19-embutido.js

## 🔁 Roteiro para recriar fora da Replit
1. Importar o projeto no Mini SK e tocar em 🏗️ Preparar → ✅ Fazer tudo (tira a Replit, cria os arquivos que faltam).
2. Não tem backend: o site sozinho basta (Netlify ou GitHub Pages).
3. Variáveis: cadastrar 6 variável(is) no servidor (lista acima).
4. Testar a prévia; se der erro, 🤖 Mandar os erros para a IA.
5. App: 📲 Instalável (PWA), 📦 APK ou 🖥️ Desktop (.exe) pelo 🏗️ Preparar.

## 🌳 Árvore de arquivos
```
├─ 📁 .github/
│  └─ 📁 workflows/
│     └─ programa-exe.yml
├─ 📁 app/
│  ├─ 📁 ferramentas/
│  │  ├─ 📁 meu-chat/
│  │  │  ├─ 📁 css/
│  │  │  │  └─ app.css
│  │  │  ├─ 📁 icons/
│  │  │  │  ├─ icon-192.png
│  │  │  │  └─ icon-512.png
│  │  │  ├─ 📁 js/
│  │  │  │  ├─ 📁 lib/
│  │  │  │  │  ├─ cofre-arquivo.js
│  │  │  │  │  ├─ guia-maikon.js
│  │  │  │  │  └─ jszip.min.js
│  │  │  │  ├─ 00-base.js
│  │  │  │  ├─ 10-banco.js
│  │  │  │  ├─ 20-provedores.js
│  │  │  │  ├─ 30-memoria.js
│  │  │  │  ├─ 33-contextos.js
│  │  │  │  ├─ 35-jeito.js
│  │  │  │  ├─ 40-voz.js
│  │  │  │  ├─ 50-internet.js
│  │  │  │  ├─ 60-previa.js
│  │  │  │  ├─ 70-texto.js
│  │  │  │  ├─ 80-chat.js
│  │  │  │  ├─ 85-config.js
│  │  │  │  ├─ 87-cofre.js
│  │  │  │  ├─ 90-backup.js
│  │  │  │  ├─ 95-ponte-lab.js
│  │  │  │  └─ 99-app.js
│  │  │  ├─ index.html
│  │  │  ├─ LEIA-ME.txt
│  │  │  ├─ manifest.json
│  │  │  ├─ sw.js
│  │  │  └─ voz-francisco.py
│  │  └─ colador.html
│  ├─ 📁 js/
│  │  ├─ 00-casca.js
│  │  ├─ 02-importar.js
│  │  ├─ 03-dependencias.js
│  │  ├─ 04-analisar.js
│  │  ├─ 05-plano.js
│  │  ├─ 05a-markdown.js
│  │  ├─ 06-scripts.js
│  │  ├─ 06b-scripts-fim.js
│  │  ├─ 07-terminal.js
│  │  ├─ 07a-busca-npm.js
│  │  ├─ 08-exportar.js
│  │  ├─ 09-integracao.js
│  │  ├─ 10-celular.js
│  │  ├─ 11-lab-base.js
│  │  ├─ 12-lab-mapa.js
│  │  ├─ 13-lab-previa.js
│  │  ├─ 14-lab-pesquisa.js
│  │  ├─ 15-lab-comparar.js
│  │  ├─ 15a-tar.js
│  │  ├─ 16-lab-ferramentas.js
│  │  ├─ 17-lab-termux.js
│  │  ├─ 18-lab-desmontar.js
│  │  └─ 19-embutido.js
│  ├─ 📁 lib/
│  │  ├─ acorn.min.js
│  │  ├─ jszip.min.js
│  │  └─ pako.min.js
│  ├─ index.html
│  └─ LEIA-ME.md
├─ 📁 electron/
│  ├─ instalar.nsh
│  ├─ main.cjs
│  ├─ navegador.html
│  ├─ ponte.cjs
│  ├─ preload-nav.cjs
│  ├─ preload.cjs
│  ├─ saude.cjs
│  ├─ terminal.cjs
│  └─ voz.cjs
├─ .gitignore
├─ LEIA-ME.md
├─ package.json
└─ PLANO.md
```
