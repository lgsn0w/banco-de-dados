# Desenvolver banco de dados

Material de apoio da **UC5 — Desenvolver banco de dados** (72h, 4h/dia, de
segunda a sexta). São 18 dias, do modelo no papel até o banco rodando,
consultado, protegido e documentado.

A unidade é conduzida como uma operação: a turma se divide em **células**, cada
célula inventa uma empresa no primeiro dia e passa os 18 dias construindo o
banco dessa empresa. O acompanhamento (os atos, o placar, o caderno de consulta
e a entrega das missões) fica no site:

**https://uc5-banco-de-dados.vercel.app**

---

## Estrutura do repositório

```
Hoje/                        o material da aula de hoje
Aulas Passadas/              todo o material anterior
```

A pasta `Hoje/` guarda o material da operação atual. Quando a operação seguinte
começa, a pasta inteira é movida para `Aulas Passadas/` e `Hoje/` recebe a nova.
Cada pasta tem um README dizendo em que ordem usar o material.

---

## Os cinco atos

| Ato | Dias | O que acontece |
|---|---|---|
| I — O reconhecimento | 1–2 | O que é banco de dados e SGBD; instalar o ambiente. |
| II — A planta | 3–7 | Entidades, relacionamentos, chaves, DER e normalização até a 3FN. |
| III — Erguer e povoar | 8–10 | `CREATE TABLE`, restrições, índices e os dados dentro. |
| IV — Interrogar o banco | 11–15 | `SELECT`, filtros, agregações, `JOIN`, subconsulta e view. |
| V — Mover e proteger | 16–18 | Importação, permissões, backup e o dossiê final. |

---

## O formato do material

Cada operação vira **um PDF**, feito para ser impresso e respondido a caneta.
Não é slide e não é apostila para ler no computador: tem espaço de resposta,
checkpoints e checklist de entrega dentro.

A estrutura de todo PDF é a mesma:

**problema → explicação → exemplo → exemplo → exercício**

Começa sempre por algo quebrado — uma planilha que apodrece, uma consulta que
mente, um backup que não volta — porque banco de dados não foi inventado por
elegância, foi inventado por dor. A teoria vem depois, para explicar o que doeu.

Os exemplos não ficam todos no mesmo domínio de propósito: oficina, clínica,
petshop, escola de idiomas. Quem só vê um domínio decora o exemplo; quem vê
quatro entende o conceito.

---

## Como usar

1. Imprima o PDF da operação do dia, um por aluno.
2. Siga os capítulos na ordem. Os **checkpoints** são pontos de parada: ninguém
   segue com um checkpoint aberto.
3. Os **testes** depois de cada checkpoint dizem o que deveria acontecer, e o
   que fazer quando não acontece.
4. Os **extras** do anexo B são opcionais. Pular todos não atrapalha nas
   operações seguintes.
5. A missão da célula é entregue pelo site, no botão **Entregar no site** do
   card da missão.

---

## O caderno

A teoria completa não mora aqui: mora no **Caderno**, no site, aberto o tempo
todo, inclusive durante as missões. O PDF de cada dia é o roteiro da aula; o
caderno é a consulta rápida.

**https://uc5-banco-de-dados.vercel.app/caderno.html**
