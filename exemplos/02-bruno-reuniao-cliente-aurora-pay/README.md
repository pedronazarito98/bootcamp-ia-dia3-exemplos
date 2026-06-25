# Bruno — Reunião com cliente Aurora Pay

## Objetivo do exemplo

Mostrar como preparar uma reunião com cliente usando IA sem cair em uma pauta genérica ou em conclusões apressadas.

O foco é transformar documentos soltos, e-mails, ata curta e CSVs em uma preparação clara para uma reunião de 30 minutos, com fatos, hipóteses, dúvidas, riscos, decisões esperadas e próximos passos.

## Persona

Bruno é analista responsável por preparar uma reunião com a Aurora Pay, cliente fictício B2B. O cliente trouxe dúvidas sobre conciliação, divergências entre exportação CSV e dashboard online, além de sinais que ainda precisam de validação técnica e de negócio.

## Dor principal

A reunião pode virar uma conversa solta, defensiva ou técnica demais se Bruno não separar fatos, hipóteses e dúvidas antes de propor encaminhamentos.

O objetivo da preparação não é descobrir a causa raiz sozinho. O objetivo é chegar com uma pauta segura, perguntas boas e próximos passos claros.

## O que este exemplo pratica

Este exemplo ajuda a praticar:

- leitura de documentos em formatos diferentes;
- separação entre fato, hipótese e dúvida;
- comparação segura de CSVs;
- análise sem fingir certeza;
- preparação de pauta de 30 minutos;
- validação da pauta contra critérios;
- criação de artefato visual de apoio;
- handoff para continuidade após a reunião.

## Arquivos da pasta `dados/`

| Arquivo | Formato | Para que serve |
|---|---|---|
| `01-briefing-cliente-aurora-pay.docx` | DOCX | Contexto do cliente, objetivo da reunião e informações iniciais |
| `02-thread-email-e-ata-reuniao.pdf` | PDF | Simula histórico de comunicação, e-mails e ata curta |
| `03-exportacao-csv-relatorio-conciliacao.csv` | CSV | Exportação fictícia do relatório de conciliação |
| `04-dashboard-online-visao-conciliacao.csv` | CSV | Visão fictícia do dashboard online para comparação |
| `05-amostra-divergencias.csv` | CSV | Amostra de divergências com possível motivo, classificação e responsável sugerido |

## Como usar

1. Abra o arquivo `prompts.md`.
2. Comece pelo **Prompt 1**, sem anexar nada, para mostrar como a IA tende a criar uma pauta genérica.
3. No **Prompt 2**, anexe todos os arquivos da pasta `dados/`.
4. Siga os prompts em sequência.
5. Use o prompt de comparação dos CSVs para mostrar como pedir análise sem forçar causa raiz.
6. Use o prompt de validação antes de aceitar a pauta.
7. Finalize com o artefato visual e o handoff.

## O que observar durante a simulação

Ao longo da conversa, observe se a IA:

- separa fatos, hipóteses e dúvidas;
- evita afirmar causa raiz sem evidência suficiente;
- identifica riscos de comunicação;
- compara os CSVs com cuidado;
- transforma divergências em perguntas para a reunião;
- evita investigar linha a linha durante a pauta;
- termina com responsáveis e próximos passos.

## Critérios de sucesso

Uma boa resposta final deve:

- caber em 30 minutos;
- reduzir ambiguidade;
- deixar claro o que já é fato e o que ainda é hipótese;
- evitar promessa de correção antes de validação;
- preparar perguntas para as pessoas certas;
- terminar com decisões esperadas, responsáveis e próximos passos.

## Aprendizado central

No contexto de trabalho, uma boa conversa com IA não é só pedir uma pauta. É dar dados, limites e critérios para que a IA ajude a preparar uma conversa mais segura, objetiva e acionável.
