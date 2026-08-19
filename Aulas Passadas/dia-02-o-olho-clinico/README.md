# Hoje: operação 02 — O olho clínico

Segundo dia do **Ato I — O reconhecimento**, e o segundo (e último) dia de papel
e caneta. A turma aprende a **ler uma tabela pronta e enxergar o que está errado
nela**: atomicidade, chave primária e uma coisa por tabela. No fim, cada célula
desenha a primeira tabela da empresa que inventou ontem.

Use **`dia-02.pdf`** do começo ao fim. Ele é só roteiro: **não
tem espaço de resposta**. A turma responde tudo no caderno, e é o caderno que as
células trocam entre si no teste final.

## A regra do dia

**Sem dispositivos, de novo.** Ninguém escreve SQL, ninguém instala SGBD,
ninguém pesquisa resposta. A instalação passou para a operação 03. Adiantar a
instalação hoje custaria a única coisa que não dá para recuperar depois: o tempo
de olhar tabela devagar, com a turma discutindo em voz alta.

**Traga a ficha de fundação da operação 01.** Ela é o insumo do capítulo 7. Quem
faltou ontem precisa fechar a ficha com a célula antes do capítulo 7 começar.

## Os sete capítulos

| Cap | Assunto | Termina em |
|---|---|---|
| 1 | A tabela que parece certa | Exercício 1 |
| 2 | As quatro perguntas que se faz a uma tabela | Checkpoint 1 + Exercício 2 |
| 3 | Um valor por campo (atomicidade) | Exercício 3 |
| 4 | O que identifica uma linha (chave primária) | Checkpoint 2 + Exercício 4 |
| 5 | Uma coisa por tabela | Checkpoint 3 |
| 6 | Melhorar a tabela dos outros | Exercício 5 |
| 7 | A missão: a primeira tabela da sua empresa | Checkpoint 4 |

Mais três anexos: **A** com os cinco erros de leitura que o dia produz, **B** com
sete extras opcionais e **C** com o checklist de entrega.

## Como conduzir

O capítulo 1 é o gancho e depende de a turma **não** ter o roteiro ainda. A
tabela do petshop é bonita de propósito: cada aluno acha dois ou três defeitos,
e ninguém acha todos. Não entregue as quatro perguntas antes do exercício 1
terminar, senão o efeito do exercício 2 se perde.

O capítulo 2 é o eixo do dia. As quatro perguntas (do que é / o que identifica a
linha / um valor por campo / o que repete) voltam em todos os capítulos
seguintes e em todo o Ato II. Vale escrevê-las no quadro e deixar lá até o dia 7.

Os capítulos 3 a 5 são teoria com exercício no fim. Cada checkpoint é ponto de
parada da turma inteira: confira em voz alta antes de seguir.

**Vocabulário fixo, use sempre o mesmo termo.** Neste material, `célula` é
**sempre** o grupo de alunos e `campo` é **sempre** o quadradinho da tabela (o
encontro de uma linha com uma coluna). A definição está numa nota no capítulo 2.
A turma se perde rápido se a mesma palavra virar duas coisas na sua fala: chame
o quadradinho de campo, do dia 2 até o dia 18. Vale para o resto do vocabulário
também: tabela, linha, coluna, campo, chave. Não alterne com "registro",
"atributo" ou "célula da planilha".

Os enunciados dos exercícios estão escritos em frases curtas, uma instrução por
frase, no imperativo. Foi de propósito, e é para ler em voz alta assim mesmo.

O capítulo 6 é o primeiro em que a célula produz desenho em vez de diagnóstico.
Espere lentidão aqui, é onde o dia trava.

O capítulo 7 é a aula toda. **Reserve a última hora para ele.**

## Onde a turma trava

- **Exercício 4, item d (agendamento de barbearia).** "Cliente + data + hora"
  parece resolver até aparecer o segundo barbeiro atendendo no mesmo horário.
  Deixe a discussão correr três minutos antes de intervir.
- **Exercício 4, item e (sensor).** Primeira chave composta da UC. Se ninguém
  chegar lá sozinho, conduza: "o mesmo sensor lê duas vezes?", "dois sensores
  leem no mesmo instante?".
- **Exercício 5, o plano da academia.** A decisão boa não é separar, é perguntar
  se o preço do plano é o mesmo para todo mundo. Célula que discutiu isso
  entendeu o capítulo 5 melhor do que quem só separou.
- **Separar demais.** Depois do capítulo 5 aparece a célula que cria tabela para
  cor, bairro e status. O exemplo do estacionamento (capítulo 6) e o erro 4 do
  anexo A existem para segurar isso.

## A missão da célula

**A primeira tabela da empresa.** A célula escolhe a entidade principal da lista
de coisas a guardar (tem que ser algo que existe sozinho, não um evento),
define de 5 a 8 colunas, escolhe e justifica a chave primária, e **preenche três
linhas de exemplo com dados inventados**.

As três linhas de exemplo são o coração da missão: é ali que aparece a coluna
que fica vazia sempre, a que precisa de vírgula para caber e a que repete a
coluna do lado. Não deixe nenhuma célula entregar sem escrever as três.

O passo 4 do capítulo 7 lista, em oito itens, exatamente o que vai no caderno.

A entrega é pelo botão **Entregar no site**, no card da missão. Uma por célula.

## Pendência no site

O `curriculo.js` ainda descreve o dia 2 como "Instalar o cofre" e a missão do
dia 2 como "Instalar o SGBD". Com a instalação empurrada para a operação 03, o
currículo do site precisa ser ajustado (título, `vemos` e o card da missão),
senão a turma abre o site e vê outra coisa.

## O que o dia prepara

A tabela desenhada no caderno é o insumo da operação 03: a célula instala o SGBD,
cria a base da empresa e transforma esse desenho na primeira tabela de verdade. As
quatro perguntas voltam como roteiro fixo em todo o Ato II.

## Consulta

A teoria deste dia corresponde às seções **A — Banco de dados** e **B —
Modelagem** do Caderno:

https://uc5-banco-de-dados.vercel.app/caderno.html#ref-modelagem
