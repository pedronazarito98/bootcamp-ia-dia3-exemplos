# Camila — Inbox da Vida Adulta

## Objetivo do exemplo

Mostrar como transformar uma lista solta de pendências da vida adulta em um plano simples, possível e revisável com ajuda da IA.

A Camila não precisa de uma rotina perfeita. Ela precisa reduzir a sensação de caos, separar urgências reais de tarefas adiáveis e sair da conversa com próximos passos pequenos.

## Persona

Camila Rocha tem 32 anos, mora sozinha, trabalha de segunda a sexta e chega ao fim do dia com pouca energia. Ela acumulou pendências pequenas: boleto, consulta, assinatura, farmácia, documentos, backup de fotos, cartão, mensagens e tarefas domésticas.

## Dor principal

Tudo parece importante ao mesmo tempo. Quando ela tenta organizar tudo de uma vez, o plano fica pesado, ela abandona e a lista volta a crescer.

## Arquivos da pasta `dados/`

| Arquivo | Para que serve |
|---|---|
| `contexto.md` | Contexto humano da persona, rotina e restrições |
| `comunicacoes.md` | Recortes fictícios de mensagens, e-mails e lembretes |
| `pendencias.csv` | Lista estruturada de pendências |
| `rotina_energia.csv` | Energia disponível por período e rotina semanal |

## Como usar

1. Comece com o prompt vago em `prompts.md`.
2. Observe se a IA responde com conselhos genéricos.
3. Anexe ou cole os dados da pasta `dados/`.
4. Rode os prompts seguintes em sequência.
5. Valide se o plano respeita energia, urgência e limite de tarefas.

## Aprendizado central

Contexto não serve para deixar a resposta mais longa. Contexto serve para impedir que a IA crie um plano bonito, mas impossível.
