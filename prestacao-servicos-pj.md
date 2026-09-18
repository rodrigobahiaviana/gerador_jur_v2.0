# Referência — Contrato de Prestação de Serviços (PJ)

Lei de referência: Código Civil, arts. 593 a 609 (prestação de
serviço).

Campos do levantamento para este tipo: `contratante_razao_social`,
`contratada_razao_social`, `descricao_servicos`, `valor_servicos`,
`prazo_contrato`.

Este é o tipo de documento com **maior risco jurídico** deste sistema:
se a relação descrita na prática tiver pessoalidade, subordinação e
habitualidade, o contrato de prestação de serviços PJ pode ser
descaracterizado e reconhecido como vínculo empregatício
("pejotização"), independentemente do que o contrato diga. A cláusula
de risco abaixo é obrigatória e nunca pode ser omitida.

## Cláusulas obrigatórias

1. **Qualificação das partes** — `contratante_razao_social` e
   `contratada_razao_social` (pessoa jurídica).
2. **Objeto do serviço** — `descricao_servicos`, descrito como
   obrigação de resultado/atividade técnica específica, não como posto
   de trabalho (Código Civil, art. 593).
3. **Preço e forma de pagamento** — `valor_servicos`, condições e
   periodicidade do pagamento (nota fiscal, prazo de quitação).
4. **Prazo do contrato** — `prazo_contrato`, com regra de renovação
   (automática ou por termo aditivo) explícita.
5. **Autonomia técnica e ausência de subordinação** — declare
   expressamente que a contratada executa o serviço com técnica
   própria, sem horário fixo imposto pela contratante, sem
   exclusividade e sem subordinação hierárquica (Código Civil,
   arts. 593–594). Inclua aqui o marcador de revisão obrigatório
   abaixo.
6. **Rescisão** — rescisão mediante aviso prévio por qualquer das
   partes, e rescisão por inadimplemento (Código Civil, art. 599).
7. **Responsabilidade tributária e trabalhista** — a contratada é
   integralmente responsável por seus próprios tributos, encargos e
   eventuais empregados/subcontratados que utilizar na execução do
   serviço.
8. **Foro** — comarca do domicílio da contratante.

## Cláusulas opcionais (incluir só se o levantamento sustentar)

- **Propriedade intelectual do resultado** — só se `descricao_servicos`
  envolver criação de material passível de proteção (software, design,
  conteúdo, marca).
- **Confidencialidade** — só se a natureza do serviço envolver acesso
  a informação sensível da contratante; nesse caso, siga também a
  referência de `confidencialidade.md` para o texto da cláusula.

## Pontos sempre sinalizados com `[REVISAR: ...]`

Inclua **sempre**, sem exceção, este marcador logo após a cláusula de
autonomia técnica (item 5) — é o ponto mais crítico deste tipo de
documento:

```
[REVISAR: confirmar na prática a ausência de pessoalidade, subordinação e habitualidade na prestação do serviço — risco de reconhecimento de vínculo empregatício (pejotização), art. 3º da CLT]
```
