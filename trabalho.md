# Referência — Contrato de Trabalho (CLT)

Lei de referência: Consolidação das Leis do Trabalho (CLT), Decreto-Lei
5.452/1943, e art. 7º da Constituição Federal.

Campos do levantamento para este tipo: `empregador_razao_social`,
`empregado_nome`, `cargo`, `valor_salario`, `regime_trabalho`.

## Cláusulas obrigatórias

1. **Qualificação das partes** — `empregador_razao_social` e
   `empregado_nome`.
2. **Cargo e atribuições** — `cargo`, com descrição sucinta das
   funções compatíveis com o cargo informado.
3. **Prazo do contrato** — se o levantamento ou o contexto indicar
   contrato de experiência, o prazo não pode exceder 90 (noventa)
   dias, admitida uma única prorrogação dentro desse limite (CLT
   art. 445, parágrafo único). Caso contrário, o contrato é por prazo
   indeterminado (CLT art. 443, caput), e contrato por prazo
   determinado em geral não pode exceder 2 (dois) anos (CLT art. 445,
   caput).
4. **Jornada de trabalho** — 8 (oito) horas diárias e 44 (quarenta e
   quatro) semanais, salvo jornada diversa expressamente acordada
   (CLT art. 58, caput), com intervalo intrajornada conforme a lei.
5. **Regime de trabalho** — `regime_trabalho` (presencial, híbrido ou
   remoto), incluindo, se remoto/híbrido, referência ao regime de
   teletrabalho da CLT (arts. 75-A a 75-E).
6. **Remuneração** — `valor_salario`, periodicidade de pagamento
   (mensal) e data de pagamento.
7. **Direitos irrenunciáveis** — 13º salário, férias anuais
   acrescidas de 1/3, FGTS, aviso prévio e demais direitos do art. 7º
   da Constituição Federal — declare que se aplicam independentemente
   de constarem explicitamente no contrato.
8. **Rescisão** — hipóteses de rescisão sem justa causa, com justa
   causa (CLT art. 482) e pedido de demissão, com remissão ao
   pagamento das verbas rescisórias cabíveis em cada caso.
9. **Foro** — Vara do Trabalho da localidade da prestação de serviço.

## Cláusulas opcionais (incluir só se o levantamento sustentar)

- **Período de experiência** — detalhar apenas se o contexto indicar
  contrato de experiência (ver item 3).
- **Cláusula de confidencialidade/propriedade intelectual do
  trabalho** — só se o cargo ou a descrição sugerir acesso a
  informação sensível ou produção de propriedade intelectual da
  empresa.

## Pontos sempre sinalizados com `[REVISAR: ...]`

Inclua exatamente este marcador próximo à cláusula de remuneração
(item 6):

```
[REVISAR: confirmar enquadramento sindical/CBO do cargo e piso salarial da categoria aplicável — pode alterar o valor mínimo de valor_salario, art. 7º, IV e VI da Constituição Federal]
```
