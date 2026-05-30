# Artigos UAI.py

Repositório oficial de publicações acadêmicas do projeto [**UAI.py**](https://github.com/uaipy), uma iniciativa de computação sustentável que reutiliza TV Boxes apreendidas pela [Receita Federal do Brasil](https://www.gov.br/receitafederal) no âmbito do programa **Além do Horizonte**.

Os dispositivos passam por descaracterização e recebem uma distribuição Linux (Armbian), transformando-se em **Centrais de Tratamento de Dados (CTD)** de baixo custo. Essas CTDs atuam como gateways locais em arquiteturas de Internet das Coisas (IoT), coletando dados de sensores, processando-os localmente e transmitindo-os para uma infraestrutura em nuvem.

Este repositório centraliza artigos, banners e formulários de submissão produzidos pela equipe em eventos científicos nacionais e internacionais.

## Publicações

### Mostra Nacional de Robótica (MNR)

| Ano | Título | Arquivos |
|-----|--------|----------|
| 2023 | **UAI.PY – A Internet das Coisas na Reatribuição de Valor** | [artigo](mostra-nacional-de-robotica/2023/artigo.pdf) · [banner](mostra-nacional-de-robotica/2023/banner.pdf) |
| 2024 | **UAI.PY: Facilitando o Acesso às Soluções de Internet das Coisas** | [artigo](mostra-nacional-de-robotica/2024/artigo.pdf) · [banner](mostra-nacional-de-robotica/2024/banner.pdf) |
| 2025 (Mundial) | **UAI.PY: Facilitando o Acesso às Soluções de Internet das Coisas** | [artigo](mostra-nacional-de-robotica/2025-mundial/artigo.pdf) · [banner](mostra-nacional-de-robotica/2025-mundial/banner.pdf) |

### Sociedade Brasileira de Computação (SBC)

| Evento | Ano | Título | Arquivos |
|--------|-----|--------|----------|
| [SCoRe](https://score.sbc.org.br/) | 2025 | **Reutilização Sustentável de TV Boxes como Centrais de Tratamento de Dados para Aplicações de IoT em Nuvem** | [artigo](sociedade-brasileira-de-computacao/SCoRe/2025/artigo.pdf) |
| [ERI-TM](https://www.sbc.org.br/eri-tm/) | 2026 | **Reutilização Sustentável de TV Boxes como Centrais de Tratamento de Dados para Aplicações de IoT em Nuvem** | [artigo](sociedade-brasileira-de-computacao/eri-tm/2026/artigo.pdf) |

### ATINER

| Ano | Título | Arquivos |
|-----|--------|----------|
| 2024 | **UAI.py: Sustainable Technology in Telemetry Applied to Agriculture** | [abstract](atiner/2024/abstract-form.pdf) |

## Estrutura do repositório

```
artigos-uaipy/
├── mostra-nacional-de-robotica/
│   ├── 2023/
│   ├── 2024/
│   └── 2025-mundial/
├── sociedade-brasileira-de-computacao/
│   ├── SCoRe/
│   └── eri-tm/
└── atiner/
```

Cada evento possui subpastas por ano. Os arquivos seguem nomes padronizados:

| Arquivo | Descrição |
|---------|-----------|
| `artigo.pdf` | Artigo completo ou versão publicada nos anais |
| `banner.pdf` | Banner ou pôster apresentado no evento |
| `abstract-form.pdf` | Formulário ou resumo submetido (quando aplicável) |

### Adicionando uma nova publicação

1. Crie a pasta do evento e do ano, se ainda não existir (ex.: `mostra-nacional-de-robotica/2026/`).
2. Adicione os PDFs com os nomes padronizados acima.
3. Atualize a tabela de publicações neste README.

## Instituições parceiras

O projeto envolve pesquisadores e estudantes de diversas instituições, entre elas:

- Instituto Federal do Triângulo Mineiro (IFTM)
- Universidade Federal de Uberlândia (UFU)
- Escola Superior de Agricultura Luiz de Queiroz — USP
- Receita Federal do Brasil

## Repositórios relacionados

| Repositório | Descrição |
|-------------|-----------|
| [iot-gateway](https://github.com/uaipy/iot-gateway) | Gateway IoT em FastAPI para orquestração de dados entre sensores e a nuvem |

## Citação

Ao utilizar ou referenciar este material, cite o artigo correspondente ao evento em que foi publicado. Os metadados completos (autores, afiliações e DOI, quando disponível) estão nos próprios PDFs.

## Licença

Os artigos permanecem sujeitos aos termos de copyright de cada evento científico. Consulte os anais ou proceedings originais para condições de redistribuição e citação.
