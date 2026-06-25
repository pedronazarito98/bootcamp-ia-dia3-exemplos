# Camila — Inbox da Vida Adulta

## Objetivo do exemplo

Mostrar como uma demanda pessoal vaga pode virar um plano simples, possível e revisável com ajuda da IA.

A Camila não precisa de uma rotina perfeita. Ela precisa reduzir a sensação de caos, separar urgências reais de tarefas adiáveis e sair da conversa com próximos passos pequenos.

## Persona

Camila Rocha tem 32 anos, mora sozinha, trabalha de segunda a sexta e chega ao fim do dia com pouca energia. Ela acumulou pendências de vida adulta em canais diferentes: mensagens, e-mails, aplicativos, contas, assinaturas, documentos digitais e tarefas domésticas.

## Dor principal

Tudo parece importante ao mesmo tempo. Quando ela tenta organizar tudo de uma vez, o plano fica pesado, ela abandona e a lista volta a crescer.

## O que este exemplo pratica

Este exemplo ajuda a praticar:

- diferença entre pedido vago e pedido com contexto;
- leitura de arquivos antes de planejar;
- criação de uma mini-spec pessoal;
- classificação de pendências por urgência, esforço, prazo e energia;
- criação de um plano de 5 dias;
- validação da resposta da IA contra critérios;
- criação de um artefato visual e de um handoff.

## Arquivos da pasta `dados/`

| Arquivo | Formato | Para que serve |
|---|---|---|
| `01-ficha-pessoal-camila-rocha.docx` | DOCX | Apresenta a persona, rotina, limites e contexto humano |
| `02-extrato-inbox-e-comunicacoes.pdf` | PDF | Simula mensagens, e-mails e lembretes espalhados em canais diferentes |
| `03-pendencias-camila.csv` | CSV | Lista pendências com origem, categoria, urgência, prazo, esforço e risco |
| `04-contas-assinaturas-e-prazos.csv` | CSV | Traz contas, assinaturas, vencimentos, status e ações sugeridas |
| `05-janela-energia-e-rotina.csv` | CSV | Mostra janelas disponíveis, energia por período e restrições da semana |

## Como usar

1. Abra o arquivo `prompts.md`.
2. Comece pelo **Prompt 1**, sem anexar nada, para mostrar a resposta genérica da IA.
3. No **Prompt 2**, anexe os arquivos da pasta `dados/`.
4. Siga os prompts em sequência.
5. Antes de aceitar qualquer plano, use o prompt de validação.
6. Finalize com o artefato visual e o handoff.

## O que observar durante a simulação

Ao longo da conversa, observe se a IA:

- evita inventar dados;
- separa fato, hipótese e dúvida;
- prioriza o que tem prazo, risco ou impacto;
- respeita o limite de energia da Camila;
- evita criar uma rotina rígida demais;
- deixa claro o que pode ser adiado sem culpa;
- transforma a conversa em algo que a Camila conseguiria usar fora do chat.

## Critérios de sucesso

Uma boa resposta final deve:

- ter no máximo 3 tarefas por dia;
- priorizar pendências realmente urgentes;
- deixar tarefas pesadas para períodos de mais energia;
- preservar espaço para imprevistos;
- separar tarefas obrigatórias de tarefas adiáveis;
- incluir revisão no final dos 5 dias.

## Aprendizado central

Contexto não serve para deixar a resposta mais longa. Contexto serve para impedir que a IA crie um plano bonito, mas impossível.
