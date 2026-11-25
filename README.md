# Operação Meta Batida

Pote da meta do time de Pré-Vendas da Magazord. A página é um HTML estático (`index.html`) que lê os números de uma planilha Google e se atualiza sozinha a cada minuto.

## Como atualizar os números

Edite as células amarelas da planilha "Pote da Meta – Pré-Vendas Magazord" (aba `Meta`):

| Campo | O que é |
|---|---|
| Qualificadas | Reuniões que já qualificaram |
| Meta de qualificadas | Total para bater a meta (12) |
| Meta no pote (%) | Quanto do pote a meta representa (40) |
| Agendadas a acontecer | Reuniões marcadas que ainda não aconteceram |
| Prazo | Data final, dd/mm/aaaa |

Reunião qualificou: some 1 em Qualificadas e tire 1 de Agendadas. Não qualificou: só tire 1 de Agendadas.

A planilha precisa estar compartilhada como "Qualquer pessoa com o link: Leitor".

## Trocar de planilha

Mude a constante `SHEET_ID` no `index.html`. A aba precisa se chamar `Meta`, com os campos em A2:B6.
