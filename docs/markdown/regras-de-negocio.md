# Regras de Negócio

## RN01 — Numeração Automática de Recibos

Os recibos deverão possuir numeração automática, única e não reutilizável.

---

## RN02 — Histórico Permanente

Recibos, contratos e reajustes deverão permanecer registrados permanentemente.

---

## RN03 — Edição Antes da Emissão

O recibo poderá ser editado apenas antes da emissão final.

---

## RN04 — Obrigatoriedade de Campos

Não será permitido criar contratos sem:

- Inquilino;
- Imóvel;
- Valor do aluguel;
- Data de vencimento.

---

## RN05 — Status Contratual

Todo contrato deverá possuir status:

- Ativo;
- Encerrado;
- Renovado;
- Suspenso.

---

## RN06 — Contratos Vencidos

Contratos vencidos deverão:

- Gerar alerta;
- Permanecer em histórico;
- Ser exibidos nos filtros.

---

## RN07 — Renovação Contratual

Ao renovar contrato:

- manter vínculo do imóvel;
- manter proprietário;
- manter histórico.

---

## RN08 — Cálculo Financeiro

O sistema deverá calcular automaticamente:

- valor bruto;
- descontos;
- valor líquido.

---

## RN09 — Reajustes

O sistema deverá registrar:

- valor anterior;
- novo valor;
- percentual;
- índice utilizado;
- data do reajuste.

---

## RN10 — Controle de Permissões

O acesso deverá ocorrer apenas mediante autenticação válida.

---

## RN11 — Integridade dos Dados

Exclusões críticas deverão utilizar exclusão lógica (soft delete).

---

## RN12 — Contrato Ativo Único

Um imóvel não poderá possuir mais de um contrato ativo simultaneamente.
