# 🧠 LLM Ecosystem Explorer

Explore o ecossistema de Grandes Modelos de Linguagem (LLMs) através de um diagrama interativo e um glossário avançado. Este projeto foi construído para estudantes e desenvolvedores autodidatas que desejam entender, testar e aplicar técnicas de modelagem, treinamento, inferência, recuperação de informações (RAG) e engenharia de prompts.

**TL;DR:**  
Abra `llm_diagram/index.html` no seu navegador, clique nos nós para ler descrições detalhadas e consulte o glossário em `advanced_glossary.md` para um estudo mais aprofundado.

---

## 🌟 Principais Funcionalidades

- **Diagrama Interativo:** Seis visualizações temáticas (Visão Geral, Modelos, Treinamento, RAG, Inferência e Prompting) permitem navegar por diferentes componentes do ecossistema. Os nós exibem informações contextuais quando selecionados e as conexões mostram o fluxo de dados entre etapas.

- **Experiência de Navegação:** Amplie, reduza ou arraste o canvas. Use a busca para filtrar e destacar nós em tempo real. Ative a animação de fluxo para ver partículas representando o movimento de dados entre componentes.

- **Glossário Avançado:** O arquivo `advanced_glossary.md` fornece explicações detalhadas sobre modelos de fundação, técnicas de treinamento (RLHF, DPO, LoRA/QLoRA, destilação), parâmetros de inferência, recuperação aumentada por geração (RAG) e engenharia de prompts. Cada conceito é apoiado por referências a artigos e papers técnicos.

- **Fluxo de Desenvolvimento Solo:** O glossário oferece recomendações práticas para quem está construindo projetos sozinho, incluindo boas práticas de fine‑tuning eficiente, utilização de RAG para evitar alucinações e estratégias de prompting para melhorar resultados.

---

## 🚀 Começando

1. **Clone ou baixe este repositório.**
2. **Navegue até a pasta `llm_diagram/`.**
3. **Abra o arquivo `index.html` em um navegador moderno (Chrome, Edge ou Firefox).**  
   Não há dependências externas ou servidor; tudo roda no front‑end.
4. **Use os botões do cabeçalho para trocar de visualização, pesquise por conceitos e clique nos nós para ler explicações aprofundadas no painel lateral.**

---

## Exemplos de Uso

| Caso | Passos | O que você aprende |
|------|--------|-------------------|
| **Ajuste fino eficiente com LoRA/QLoRA** | Selecione Treinamento > clique em LoRA e QLoRA > leia as descrições e conexões | Entenda como LoRA mantém pesos congelados e injeta matrizes de baixa dimensão, e como QLoRA adiciona quantização para ajustar modelos gigantes [arxiv.org](https://arxiv.org/) |
| **Construção de base de conhecimento com RAG** | Selecione RAG > siga a sequência Documentos → Chunking → Embeddings → Vector DB | Aprenda como dividir documentos em chunks, converter em embeddings, armazenar em bancos vetoriais e recuperar contexto para melhorar a precisão [learn.microsoft.com](https://learn.microsoft.com/) |
| **Comparar estratégias de inferência** | Em Inferência, explore Temperatura, Top‑K, Top‑P e estratégias Beam Search e Greedy | Veja como ajustar os parâmetros de geração para balancear criatividade e precisão. |
| **Engenharia de Prompts** | Acesse Prompting > clique em Zero‑Shot, Few‑Shot, Chain‑of‑Thought, etc. | Descubra como diferentes técnicas de prompting influenciam o comportamento do modelo, com dicas práticas de aplicação [promptingguide.ai](https://promptingguide.ai/) [arxiv.org](https://arxiv.org/) |

---

## 📸 Exemplos Visuais

**Prompting – Engenharia de Prompts**  
![Prompting](images/prompting.png)

**Visão Geral do Ecossistema**  
![Overview](images/overview.png)

**Inferência – Parâmetros e Estratégias**  
![Inference](images/inference.png)

---

## 📚 Glossário de Modelos de Linguagem

Para um estudo aprofundado, leia o arquivo `advanced_glossary.md`, que detalha:

- **Modelos de Fundação, Multimodais e SLMs** – diferenças entre modelos gerais, multimodais e modelos compactos (Small Language Models).
- **Treinamento** – conceitos de pré‑treino, RLHF, DPO, dados sintéticos, destilação, LoRA/QLoRA/PEFT e checkpoints  
  [huggingface.co](https://huggingface.co/) [arxiv.org](https://arxiv.org/).
- **Prompting & Inferência** – técnicas de zero‑shot, few‑shot e chain‑of‑thought; ajustes de temperatura, top‑k, top‑p e uso de seeds  
  [promptingguide.ai](https://promptingguide.ai/).
- **Recuperação Aumentada por Geração (RAG)** – como integrar busca semântica com modelos generativos para reduzir alucinações e citar fontes  
  [blogs.nvidia.com](https://blogs.nvidia.com/).

Essas seções são acompanhadas de dicas práticas para desenvolvimento autodidata, incluindo integração com ferramentas de design (Figma), frameworks (React) e orquestradores de workflows (n8n).

---

## 🛠️ Estrutura do Projeto

```
.
├── advanced_glossary.md   # Glossário detalhado e referenciado
├── advanced_glossary.svg  # Diagrama avançado utilizado neste README
├── llm_diagram/           # Aplicação interativa (HTML, CSS, JS)
│   ├── index.html         # Diagrama interativo completo
│   └── README.md          # Documentação técnica da aplicação
├── images/                # Prints do diagrama
│   ├── overview.png
│   ├── inference.png
│   ├── prompting.png
└── README.md              # Este arquivo
```

---

## 🤝 Contribuindo

Contribuições são bem‑vindas! Se você encontrar um problema ou tiver sugestões de melhoria:

- Abra uma issue descrevendo a questão ou a nova funcionalidade.
- Fork o repositório e crie uma branch para sua alteração.
- Envie um pull request com uma descrição clara do que foi alterado.

Antes de contribuir, leia o glossário para manter consistência no vocabulário e nas definições técnicas.

---

## 📄 Licença

Este projeto é licenciado sob os termos da licença MIT. Consulte o arquivo LICENSE para mais detalhes.

---

## 📬 Contato

- Linkedin: [Ivanildo Nogueira](https://www.linkedin.com/in/ivanildo-nogueira-459550211/)

Sinta‑se à vontade para explorar, aprender e adaptar este projeto às suas necessidades.  
Bom estudo e boas criações com modelos de linguagem! 🙌