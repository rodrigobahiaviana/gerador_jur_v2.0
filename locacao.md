# Referência — Contrato de Locação

Lei de referência: Lei 8.245/1991 (Lei do Inquilinato).

Campos do levantamento para este tipo: `locador_nome`,
`locatario_nome`, `endereco_imovel`, `valor_aluguel`, `prazo_meses`,
`modalidade_garantia`.

## Cláusulas obrigatórias

1. **Qualificação das partes** — `locador_nome` e `locatario_nome`.
2. **Identificação do imóvel** — endereço completo
   (`endereco_imovel`) e finalidade da locação (residencial ou
   comercial, inferida do contexto se não vier explícita).
3. **Valor e forma de pagamento do aluguel** — `valor_aluguel`, dia de
   vencimento, forma de reajuste (índice a definir entre as partes,
   ex.: IGP-M ou IPCA, anual).
4. **Prazo da locação** — `prazo_meses`. Durante o prazo estipulado, o
   locador não pode reaver o imóvel (Lei 8.245/91, art. 4º, caput).
5. **Garantia locatícia** — conforme `modalidade_garantia`, inclua
   **apenas uma** das cláusulas abaixo (a Lei 8.245/91, art. 37,
   parágrafo único, proíbe, sob pena de nulidade, mais de uma
   modalidade de garantia no mesmo contrato):
   - `caucao` → caução em dinheiro, limitada a 3 (três) meses de
     aluguel, depositada em caderneta de poupança (Lei 8.245/91,
     art. 38, §2º).
   - `fiador` → fiança, com o fiador respondendo até a efetiva entrega
     das chaves (Lei 8.245/91, art. 37, II).
   - `seguro-fianca` → apólice de seguro de fiança locatícia, cobrindo
     inadimplemento de aluguel e encargos (Lei 8.245/91, art. 37,
     III).
   - Qualquer outro valor em `modalidade_garantia` → registre o texto
     recebido tal como veio e marque `[REVISAR: confirmar se a
     modalidade de garantia informada corresponde a uma das previstas
     no art. 37 da Lei 8.245/1991]`.
6. **Multa por rescisão antecipada** — proporcional ao período
   restante do contrato (Lei 8.245/91, art. 4º, caput e parágrafo
   único). Inclua o marcador de revisão do item abaixo.
7. **Obrigações do locador** (entregar o imóvel em condições de uso,
   garantir uso pacífico) e **obrigações do locatário** (pagar em dia,
   usar conforme a finalidade, restituir no estado recebido) — Lei
   8.245/91, arts. 22 e 23.
8. **Foro** — comarca de situação do imóvel.

## Cláusulas opcionais (incluir só se o levantamento sustentar)

- **Benfeitorias** — se houver menção a reforma/benfeitoria no
  levantamento, regra de indenização ou não conforme acordado.
- **Direito de preferência na venda** — só se o levantamento indicar
  intenção de venda futura do imóvel (Lei 8.245/91, art. 27).

## Pontos sempre sinalizados com `[REVISAR: ...]`

Inclua exatamente este marcador na cláusula de multa por rescisão
antecipada (item 6):

```
[REVISAR: confirmar proporcionalidade da multa rescisória, art. 4º da Lei 8.245/1991]
```
