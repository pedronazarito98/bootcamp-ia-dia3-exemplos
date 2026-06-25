# Prompts atualizados - Bruno e Aurora Pay com anexos

Use esta sequência para simular uma conversa mais parecida com trabalho real, onde Bruno traz documentos em formatos diferentes.

## Prompt 1 - Pedido vago

```text
Me ajuda a preparar uma reunião com um cliente?
```

## Prompt 2 - Anexar dados e pedir leitura inicial

```text
Atue como uma pessoa que me ajuda a preparar reuniões difíceis com clientes B2B.

Eu sou Bruno, analista responsável por preparar uma reunião de 30 minutos com a Aurora Pay.
Anexei materiais fictícios em formatos diferentes:

- briefing do cliente em DOCX;
- thread de e-mails e ata curta em PDF;
- exportação CSV do relatório de conciliação;
- visão CSV do dashboard online;
- amostra de divergências.

Primeiro, não monte a pauta ainda.
Leia os materiais e me devolva apenas:
1. fatos confirmados;
2. hipóteses;
3. dúvidas abertas;
4. riscos de comunicação;
5. dados que parecem importantes, mas ainda precisam de validação.

Importante: não conclua causa raiz. Use português simples.
```

## Prompt 3 - Mini-spec

```text
Transforme a leitura dos documentos em uma mini-spec para preparar a reunião.

Inclua:
- contexto;
- problema principal;
- objetivo da reunião;
- restrições;
- fora de escopo;
- critérios de sucesso;
- dúvidas abertas;
- riscos;
- decisões esperadas.

A mini-spec deve deixar explícito o que é fato, hipótese e dúvida.
```

## Prompt 4 - Comparar CSVs sem fingir certeza

```text
Compare a exportação CSV com a visão do dashboard online usando a amostra de divergências.

Quero uma análise segura, sem afirmar causa raiz.
Responda com:
- resumo numérico das divergências;
- padrões observados;
- hipótese mais provável;
- evidências que sustentam a hipótese;
- o que ainda precisa ser validado por Marina;
- perguntas que Bruno deve levar para Renata e Caio.
```

## Prompt 5 - Pauta de 30 minutos

```text
Com base na mini-spec e na análise dos documentos, crie uma pauta de 30 minutos para Bruno conduzir a reunião.

A pauta precisa ter:
- abertura;
- alinhamento de fatos;
- separação de hipóteses e dúvidas;
- perguntas para Renata e Caio;
- decisões esperadas;
- próximos passos;
- responsáveis.

Não investigar linha a linha durante a reunião.
Não prometer causa raiz ou correção sem confirmação técnica.
```

## Prompt 6 - Validar contra critérios

```text
Revise a pauta usando estes critérios:

1. Cabe em 30 minutos?
2. Reduz ambiguidade?
3. Separa fatos, hipóteses e dúvidas?
4. Evita prometer causa raiz?
5. Define responsáveis?
6. Termina com próximos passos claros?

Responda em tabela com: critério, status, evidência e ajuste recomendado.
```

## Prompt 7 - Artefato visual

```text
Crie um HTML único para Bruno usar como apoio antes e depois da reunião.

O HTML deve conter:
- cabeçalho;
- resumo executivo;
- fatos, hipóteses e dúvidas;
- pauta de 30 minutos;
- perguntas-chave;
- riscos de comunicação;
- decisões esperadas;
- próximos passos;
- template de resumo pós-reunião.

Regras:
- HTML e CSS no mesmo arquivo;
- sem bibliotecas externas;
- visual limpo, moderno e apresentável;
- texto em português;
- usar somente dados fictícios;
- deixar explícito que causa raiz ainda não foi confirmada.
```

## Prompt 8 - Handoff

```text
Crie um handoff da preparação da reunião para outra pessoa continuar o acompanhamento.

Inclua:
- decisões tomadas na preparação;
- pendências;
- responsáveis;
- riscos;
- próxima ação;
- o que revisar depois da reunião;
- quais documentos foram usados como fonte.
```
