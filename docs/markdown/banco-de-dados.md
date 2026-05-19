# Banco de Dados

## Modelagem Relacional

O sistema SmartImob utilizará banco de dados relacional.

---

## Principais Entidades

- usuários
- proprietários
- inquilinos
- imóveis
- contratos
- recibos
- reajustes
- alertas
- auditoria

---

## Relacionamentos

### Proprietário → Imóveis

1 proprietário pode possuir vários imóveis.

---

### Imóvel → Contratos

1 imóvel pode possuir vários contratos ao longo do tempo.

Apenas 1 contrato poderá estar ativo simultaneamente.

---

### Inquilino → Contratos

1 inquilino pode possuir vários contratos.

---

### Contrato → Recibos

1 contrato poderá gerar vários recibos.

---

### Contrato → Reajustes

1 contrato poderá possuir vários reajustes registrados.

---

## Integridade

O sistema deverá:

- preservar histórico;
- impedir exclusões críticas permanentes;
- utilizar chaves estrangeiras;
- manter rastreabilidade financeira.

---

## Campos Padrão

Todas as tabelas deverão possuir:

- id
- data_criacao
- data_atualizacao
- status
