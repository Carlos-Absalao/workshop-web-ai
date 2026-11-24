# 🌐 Workshop — Inteligência Artificial na Web com Web AI

Material do workshop que apresentei para a graduação da **Faculdade Nova Roma** (2026): como rodar modelos de IA **diretamente no navegador**, sem servidor e sem enviar dados para a nuvem.

![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![Transformers.js](https://img.shields.io/badge/🤗%20Transformers.js-FFD21E)
![WebGPU](https://img.shields.io/badge/WebGPU%20%2F%20WASM-005A9C)

## Conteúdo

1. **Por que IA no navegador?** Privacidade, custo zero de servidor, funciona offline.
2. **Como funciona:** modelos ONNX, WebAssembly e WebGPU.
3. **Mão na massa:** três demos prontas para abrir no navegador.
4. **Limites e boas práticas:** tamanho de modelo, cache, desempenho em celular.

## HTML

| Demo | Tarefa | Arquivo |
|---|---|---|
| Análise de sentimento | Classifica um texto como positivo/negativo | [`demos/sentimento.html`](demos/sentimento.html) |
| Classificação zero-shot | Classifica em categorias que você define | [`demos/zero-shot.html`](demos/zero-shot.html) |
| Busca semântica | Encontra a frase mais parecida com a sua pergunta | [`demos/busca-semantica.html`](demos/busca-semantica.html) |

Para rodar: `python -m http.server 8000` na pasta do projeto e abra http://localhost:8000/demos/.
Ou publique no **GitHub Pages** (Settings → Pages → branch `main`) e acesse pelo link.

> Na primeira execução o modelo é baixado (dezenas de MB) e fica em cache no navegador.

## Slides
Apresentação segue na pasta Slides

---
Autor: [Carlos Absalão](https://www.linkedin.com/in/carlos-absalao-dados-ia) · Licença MIT
