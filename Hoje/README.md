# Hoje: operação 04 — Quem se liga a quem

Segundo dia do **Ato II — A planta**, e o quarto dia de papel e caneta. A turma
aprende a **transformar os verbos anotados ontem em ligação entre tabelas**:
relacionamento, cardinalidade 1:1, 1:N e N:M, onde mora a chave estrangeira e
quando a ligação vira uma tabela nova.

Use **`dia-04-quem-se-liga-a-quem.pdf`** do começo ao fim. Ele é só roteiro:
**não tem espaço de resposta**. A turma responde tudo no caderno, e é o caderno
que as células trocam entre si no fim.

## A regra do dia

**Sem dispositivos, pelo quarto dia.** A instalação do SGBD continua adiada para
a operação 06, junto com o DER em ferramenta. Ver a nota no fim deste README.

**Traga o dicionário de dados da operação 03.** Ele é o insumo do capítulo 7.
Célula que não fechou o dicionário ontem precisa fechá-lo antes do capítulo 7
começar, senão não há o que ligar.

## Os sete capítulos

| Cap | Assunto | Termina em |
|---|---|---|
| 1 | Duas células, a mesma ligação | Exercício 1 |
| 2 | A frase nos dois sentidos | Checkpoint 1 + Exercício 2 |
| 3 | 1:N, a chave mora no lado N | Exercício 3 |
| 4 | N:M, a ligação vira tabela | Checkpoint 2 + Exercício 4 |
| 5 | 1:1, o caso raro | Checkpoint 3 |
| 6 | Corrigir o modelo dos outros | Exercício 5 |
| 7 | A missão: o mapa de ligações da empresa | Checkpoint 4 |

Mais três anexos: **A** com os cinco erros que o dia produz, **B** com sete
extras opcionais e **C** com o checklist de entrega.

## A prévia de SQL

Este é o primeiro PDF da unidade com SQL dentro. São **três caixas cor de
âmbar**, uma no capítulo 3, uma no capítulo 4 e uma no capítulo 5, marcadas
**Prévia de SQL · só para ler**.

Elas mostram a mesma decisão do papel escrita em SQL: a linha `REFERENCES` do
1:N, o `PRIMARY KEY` de duas colunas da tabela de ligação, e o `UNIQUE` que
separa o 1:1 do 1:N.

**A turma não escreve SQL hoje, e não copia as caixas.** Elas são leitura de
passagem, três minutos cada uma no máximo. O objetivo é a turma reconhecer a
palavra na operação 08 em vez de encontrá-la pela primeira vez. Célula que pedir
para escrever SQL hoje recebe a mesma resposta de sempre: a operação 08.

Se o tempo apertar, as três caixas são a primeira coisa a cortar. Nenhum
exercício e nenhum passo da missão depende delas.

## Como conduzir

O capítulo 1 é o gancho e depende de a turma **não** ter a regra ainda. Os dois
modelos da gráfica são plausíveis de propósito. Deixe a turma defender os dois
antes de entregar o capítulo 2.

O capítulo 2 é o eixo do dia. O **procedimento das duas frases** (ida e volta)
volta em todos os capítulos seguintes, na missão e no Ato III inteiro. Vale
escrever as duas frases no quadro e deixar lá até o dia 7, ao lado das quatro
perguntas da operação 02 e do substantivo e verbo da operação 03.

Os capítulos 3, 4 e 5 são uma cardinalidade cada. O capítulo 4 é o mais denso e
o que mais rende: a tabela de ligação e a coluna do encontro são o que faz a
operação 13 (JOIN) fazer sentido.

O capítulo 5 é curto de propósito. A mensagem dele não é como fazer um 1:1, é
**por que quase nunca se faz um**.

O capítulo 6 é onde o dia trava. Espere lentidão.

O capítulo 7 é a aula toda. **Reserve a última hora e meia para ele.**

## Onde a turma trava

- **Exercício 2, caminhão e rota.** É o item 5 e é de propósito: a fala do dono
  não decide a cardinalidade. Quase toda dupla marca 1:N sem perceber. A saída é
  a pergunta "a mesma rota sai sempre com o mesmo caminhão?". Deixe a discussão
  correr três minutos antes de intervir.
- **Exercício 3, `id_venda` no exemplar.** É a primeira FK opcional do material.
  A dupla que marca tudo obrigatório não pensou no exemplar parado no estoque. É
  o mesmo erro 4 da operação 03, com outra roupa.
- **Exercício 4, a tabela `emprestimo`.** Ela liga três coisas: equipamento,
  aluno e mergulho. A célula trava porque o capítulo 4 só mostrou ligação de dois
  lados. Aceite `id_aluno` como FK comum dentro da tabela de ligação. O caso de
  três lados inteiro é o extra E3.1.
- **Exercício 5, a `sessao`.** A tabela de ligação já está lá e ninguém percebe,
  porque ela tem nome de negócio. É o ponto do exercício. Se ninguém chegar,
  conduza: "o que sobra na sessão depois de tirar data, horas e valor?".
- **Tabela de ligação para tudo.** Depois do capítulo 4 aparece a célula que cria
  `cliente_pedido` para um 1:N. É o erro 4 do anexo A. O sintoma é a célula
  achar que tabela de ligação é sempre mais seguro.
- **Coluna no plural.** `pedidos`, `alunos`, `telefones`. É o sintoma mais rápido
  de ligação no lugar errado, e serve para varrer o mapa da célula em dez
  segundos. Está no erro 2 do anexo A.

## A missão da célula

**O mapa de ligações da empresa.** A célula pega o dicionário da operação 03,
escreve no mínimo cinco pares de tabelas ligadas por verbo, aplica o
procedimento das duas frases em cada par, marca a cardinalidade, põe a FK do
lado certo em cada 1:N, cria a tabela de ligação de cada N:M e escreve o
dicionário completo de uma dessas tabelas de ligação.

**Exija no mínimo um N:M.** Mapa sem nenhum N:M quase sempre tem uma ligação não
descoberta, e o buraco só aparece na operação 13, quando a consulta não fecha.

O passo 4 é o que separa a entrega boa da fraca: a célula escreve o **caminho de
tabelas** de cada pergunta do dono. Caminho que quebra no meio revela a ligação
que falta, ainda no papel.

O passo 5 lista, em oito itens, exatamente o que vai no caderno. O modelo do mapa
para copiar está logo abaixo dele.

A entrega é pelo botão **Entregar no site**, no card da missão. Uma por célula.

## Pendências no site

1. O `curriculo.js` **ainda** descreve o dia 2 como "Instalar o cofre" e a missão
   do dia 2 como "Instalar o SGBD". A pendência está aberta desde a operação 02.
   Título, `vemos` e card da missão do dia 2 precisam ser ajustados.
2. O dia 4 no `curriculo.js` está correto: "Quem se liga a quem", relacionamentos
   e cardinalidade. Nada a mudar.
3. A missão do site para os dias 3 a 7 é "O modelo completo", uma entrega só para
   cinco dias. O dicionário da operação 03 foi a primeira parcela e o mapa de
   hoje é a segunda. O PDF já avisa isso numa nota do capítulo 7, mas o card do
   site continua sem avisar.

## A instalação do SGBD

Continua adiada, junto com o DER em ferramenta, para a **operação 06**. Quem
assumir a turma na operação 05 precisa saber: **a turma chega no dia 5 sem
ambiente instalado**, com dicionário e mapa de ligações no papel.

## O que o dia prepara

O mapa é o insumo direto de quatro operações. A operação 05 pega as FK marcadas
hoje e dá regra a elas: chave candidata, chave estrangeira e integridade
referencial. A operação 06 desenha o mapa no brModelo ou no dbdiagram. A operação
08 traduz cada FK numa linha `REFERENCES` e cada tabela de ligação num
`PRIMARY KEY` de duas colunas. A operação 13 percorre o caminho de tabelas
escrito hoje, e é ali que ligação errada custa caro.

## Consulta

A teoria deste dia corresponde à seção **B — Modelagem** do Caderno, na parte das
três cardinalidades e do modelo lógico:

https://uc5-banco-de-dados.vercel.app/caderno.html#ref-modelagem

**Diferença de termo, avisada no PDF:** o Caderno chama de *tabela intermediária*
o que este material chama de **tabela de ligação**. São a mesma tabela. Use um
termo só em voz alta, do dia 4 ao dia 18.
