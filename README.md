# Análise de Performance — Canal WhatsApp Hotelaria 2026

## Sobre o projeto
Análise de dados do canal WhatsApp de um hotel na Serra Gaúcha, 
comparando atendimento humanizado (Kommo, 2025) com implementação 
de chatbot (ASK Suite, Jan–Abr 2026).

O objetivo foi identificar gargalos de conversão, avaliar performance 
por campanha e comparar a efetividade do atendimento humano versus robô.

## Ferramentas utilizadas
- Python (pandas) — limpeza e análise dos dados
- Google Colab — ambiente de desenvolvimento
- Google Looker Studio — visualização e dashboard
- Google Sheets — tratamento intermediário dos dados

## Principais achados

**Conversão por tipo de atendimento (mesmo período, Jan–Abr):**
| Indicador | Taxa |
|---|---|
| Kommo 2025 — humano | 3,87% |
| ASK 2026 — humano | 3,90% |
| ASK 2026 — geral | 3,40% |
| ASK 2026 — robô | 0,50% |

- Atendentes humanos mantiveram performance estável entre 2025 e 2026
- O robô atende 54% dos contatos e converte 7,8x menos que os humanos
- Campanha Link para Site: 142 leads, 21 reservas (14,8% de conversão)
- Campanha Outono C1: 408 leads, 3 reservas (0,7% de conversão)
- 98,9% dos contatos chegam sem UTM — ROAS real incalculável

## Contexto
A baixa conversão do robô não tem causa única. O atendimento 24/7 
é um ganho real. Limitações técnicas para cotações com múltiplos 
quartos e ausência de integração direta com o PMS são gargalos 
resolvíveis. A análise reflete um período de adaptação da ferramenta.

## Dashboard
[Acessar no Looker Studio](https://datastudio.google.com/reporting/12632736-0691-4266-bf0c-97754bbf4b7b)

## Dados
Os dados originais são proprietários e não estão disponíveis 
publicamente. O código de análise está disponível no notebook.
