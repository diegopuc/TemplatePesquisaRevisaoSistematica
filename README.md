# Template de Revisão Sistemática

Repositório-modelo para planejamento, execução, acompanhamento e documentação de uma revisão sistemática conduzida por estudantes e pesquisadores.

> Substitua todos os campos indicados por `[PREENCHER]` antes de iniciar a execução da revisão.

## 1. Identificação da pesquisa

| Informação | Descrição |
|---|---|
| Título da revisão | [PREENCHER] |
| Instituição | [PREENCHER] |
| Curso / Programa | [PREENCHER] |
| Disciplina / Projeto | [PREENCHER] |
| Professor / Orientador | [PREENCHER] |
| Pesquisadores | [PREENCHER] |
| Data de início | [PREENCHER] |
| Última atualização | [PREENCHER] |
| Status geral | Não iniciado |

## 2. Tema e problema de pesquisa

**Tema:** [PREENCHER]

**Problema de pesquisa:** [PREENCHER]

## 3. Objetivo

[PREENCHER]

## 4. Questões de pesquisa

- RQ1 — [PREENCHER]
- RQ2 — [PREENCHER]
- RQ3 — [PREENCHER]

As questões completas e suas possíveis subdivisões devem ser mantidas em `01-protocolo/questoes-pesquisa.md`.

## 5. Protocolo

O protocolo metodológico deve ser definido e versionado antes da execução das buscas. O documento principal está em `01-protocolo/protocolo.md`.

Alterações realizadas após o início da revisão devem ser registradas em `01-protocolo/alteracoes-protocolo.md`, contendo data, alteração, justificativa e responsável.

## 6. Estratégia de busca

**Bases planejadas:** [PREENCHER]

As strings completas, adaptações por base, datas de execução e quantidade de resultados devem ser registradas em `02-estrategia-busca/`.

## 7. Critérios de elegibilidade

### Critérios de inclusão

- IC01 — [PREENCHER]
- IC02 — [PREENCHER]

### Critérios de exclusão

- EC01 — [PREENCHER]
- EC02 — [PREENCHER]

Os critérios detalhados devem ser mantidos em `01-protocolo/criterios-inclusao-exclusao.md`.

## 8. Andamento da revisão

| Etapa | Status | Responsável | Observação |
|---|---|---|---|
| Definição do protocolo | ⬜ Não iniciado | | |
| Questões de pesquisa | ⬜ Não iniciado | | |
| Critérios de inclusão/exclusão | ⬜ Não iniciado | | |
| Strings de busca | ⬜ Não iniciado | | |
| Execução das buscas | ⬜ Não iniciado | | |
| Consolidação dos resultados | ⬜ Não iniciado | | |
| Remoção de duplicatas | ⬜ Não iniciado | | |
| Triagem por título e resumo | ⬜ Não iniciado | | |
| Leitura em texto completo | ⬜ Não iniciado | | |
| Seleção final | ⬜ Não iniciado | | |
| Extração dos dados | ⬜ Não iniciado | | |
| Avaliação da qualidade | ⬜ Não iniciado | | |
| Síntese dos resultados | ⬜ Não iniciado | | |
| Fluxograma PRISMA | ⬜ Não iniciado | | |
| Redação do artigo/relatório | ⬜ Não iniciado | | |

Legenda: ⬜ Não iniciado · 🟡 Em andamento · ✅ Concluído · ⛔ Bloqueado

## 9. Números da seleção

| Etapa | Quantidade |
|---|---:|
| Registros identificados | 0 |
| Duplicatas removidas | 0 |
| Registros submetidos à triagem | 0 |
| Registros excluídos na triagem | 0 |
| Textos completos avaliados | 0 |
| Textos completos excluídos | 0 |
| Estudos incluídos | 0 |

## 10. Organização do repositório

```text
01-protocolo/           Definições metodológicas e histórico do protocolo
02-estrategia-busca/   Bases, strings e registro das buscas
03-identificacao/       Exportações originais, consolidação e duplicatas
04-triagem/             Triagem por título/resumo e conflitos
05-elegibilidade/       Leitura completa e motivos de exclusão
06-estudos-incluidos/   Conjunto final de estudos
07-extracao-dados/      Formulário, extração e qualidade
08-analise/             Síntese, tabelas, gráficos e scripts
09-prisma/              Controle do relato e fluxograma PRISMA
10-publicacao/          Artigo/relatório e materiais suplementares
docs/                   Referências e documentos de apoio
```

## 11. Regras de registro

1. Não apagar resultados brutos exportados das bases; armazená-los em `03-identificacao/resultados-brutos/`.
2. Registrar cada execução de busca, mesmo quando a string não retornar resultados.
3. Não alterar critérios de elegibilidade silenciosamente; registrar toda alteração do protocolo.
4. Registrar o motivo de exclusão de estudos avaliados em texto completo.
5. Manter identificadores consistentes para os estudos ao longo de todas as planilhas.
6. Utilizar commits com mensagens que indiquem claramente a etapa realizada.
7. Não versionar PDFs de artigos quando houver restrição de direitos autorais ou de licença.
8. Não incluir dados pessoais, credenciais, chaves de API ou materiais confidenciais no repositório.

## 12. Diretrizes metodológicas

Recomenda-se utilizar as diretrizes PRISMA 2020 para o relato da revisão e PRISMA-P para o protocolo. Consulte sempre as versões oficiais e as extensões aplicáveis ao tipo de revisão.

- PRISMA 2020: https://www.prisma-statement.org/prisma-2020
- Protocolos / PRISMA-P: https://www.prisma-statement.org/protocols

## 13. Reprodutibilidade

Ao final, outra pessoa deve conseguir compreender e, quando possível, reproduzir:

1. como as fontes foram escolhidas;
2. quais estratégias de busca foram executadas;
3. como duplicatas foram tratadas;
4. como ocorreu a seleção dos estudos;
5. quais dados foram extraídos;
6. como a qualidade/risco de viés foi avaliado;
7. como os resultados foram sintetizados.

## 14. Citação e licença

Atualize `CITATION.cff` com os dados da pesquisa. Consulte `LICENSE.md` antes de publicar materiais, dados ou scripts.
