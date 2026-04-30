# 🧠 Ocifeyn — Método Feynman para OCI Foundations

> *Pare de estudar o OCI. Comece a entendê-lo.*

**Ocifeyn** é um web app de estudo ativo baseado na Técnica Feynman, construído para quem está se preparando para a certificação **Oracle Cloud Infrastructure Foundations 2024-1**. Sem flashcards, sem listas de vocabulário — só compreensão real em 15 minutos por dia.

🔗 **[Abrir o app](https://seu-usuario.github.io/ocifeyn)**

---

## O problema com o estudo convencional

Decorar definições funciona para prova de múltipla escolha. Não funciona quando o conceito aparece num cenário novo, numa questão redação ou no trabalho real. O método Feynman resolve isso forçando **produção ativa** em vez de reconhecimento passivo.

## Como o app funciona

O ciclo completo em 4 passos, com timer de 15 minutos:

| Passo | Ação | Por que funciona |
|---|---|---|
| **1 — Leitura** | Leia o conceito buscando sentido, não memorização | Ativa padrões naturais de aquisição |
| **2 — Produção** | Feche o material. Explique com suas palavras | Revela o mapa real do entendimento |
| **3 — Gaps** | Registre onde travou ou ficou vago | O gap é o aprendizado, não o fracasso |
| **4 — Cirúrgico** | Volte *apenas* ao que faltou. Repita | Máxima retenção com mínimo desperdício |

## Conteúdo incluído

8 conceitos essenciais do OCI Foundations, cada um com descrição técnica e **analogia do mundo real** (o coração do método Feynman):

- Tenancy e Regiões
- Compartments
- IAM — Identity and Access Management
- Compute — Instâncias e Shapes
- Object Storage, Block Volume e File Storage
- VCN e Componentes de Rede
- Alta Disponibilidade e Fault Domains
- Security Lists, NSGs e WAF

## Funcionalidades

- **Sessão ativa** com timer de 15 minutos e ciclo Feynman guiado
- **Dashboard de gaps** — registre e resolva seus pontos cegos
- **8 prompts especializados** para usar com qualquer IA (Claude, ChatGPT, Gemini)
- **Progresso persistente** via localStorage — seus dados não se perdem entre sessões
- **Zero dependências** — HTML puro, funciona offline após o primeiro carregamento

## Como usar no GitHub Pages

```bash
# 1. Clone ou faça fork deste repositório
git clone https://github.com/seu-usuario/ocifeyn.git
cd ocifeyn

# 2. O repositório já está pronto — apenas habilite o GitHub Pages
# Settings → Pages → Source: Deploy from branch → Branch: main → / (root)

# 3. Acesse em:
# https://seu-usuario.github.io/ocifeyn
```

Nenhum build, nenhum framework, nenhuma configuração. O `index.html` é o app inteiro.

## Filosofia

> *"A primeira etapa para conhecer algo é ter a coragem de admitir que você não sabe."*
> — Richard P. Feynman

Richard Feynman foi físico, ganhador do Nobel, e aprendeu português do zero em poucos meses para dar aulas no Brasil — não com método convencional, mas com exposição ativa, curiosidade genuína e tolerância ao erro. Este app aplica o mesmo princípio ao estudo de cloud.

## Estrutura do projeto

```
ocifeyn/
└── index.html    # App completo — tudo em um único arquivo
└── README.md
```

## Contribuindo

Quer adicionar conceitos, corrigir analogias ou adaptar para outra certificação (AWS, Azure, GCP)?

1. Faça um fork
2. Edite o array `CONCEPTS` em `index.html`
3. Abra um Pull Request

---

**Certificação alvo:** Oracle Cloud Infrastructure 2024 Foundations Associate (1Z0-1085-24)

*Feito com o método Feynman. Estude menos, entenda mais.*
