# Hoje: operação 03 — O que a empresa guarda

Primeiro dia do **Ato II — A planta**, e o terceiro dia de papel e caneta. A
turma aprende a **descobrir o que a empresa guarda** e a escrever isso num
documento fechado: levantamento de dados, entidade e atributo, tipo, tamanho,
obrigatoriedade, e o **dicionário de dados**.

Use **`dia-03-o-que-a-empresa-guarda.pdf`** do começo ao fim. Ele é só roteiro:
**não tem espaço de resposta**. A turma responde tudo no caderno, e é o caderno
que as células trocam entre si no fim.

## A regra do dia

**Sem dispositivos, pelo terceiro dia.** A instalação do SGBD não acontece hoje.
O dia inteiro é conversa, papel e caneta. Ver a nota sobre a instalação no fim
deste README.

**Traga a ficha de fundação da operação 01 e o desenho da operação 02.** As duas
são insumo do capítulo 7. Quem faltou precisa fechar as duas com a célula antes
do capítulo 7 começar.

## Os sete capítulos

| Cap | Assunto | Termina em |
|---|---|---|
| 1 | Duas listas da mesma empresa | Exercício 1 |
| 2 | Onde o dado já está escrito | Checkpoint 1 + Exercício 2 |
| 3 | Entidade ou atributo | Exercício 3 |
| 4 | Tipo, tamanho e obrigatoriedade | Checkpoint 2 + Exercício 4 |
| 5 | O dicionário de dados | Checkpoint 3 |
| 6 | Corrigir o dicionário dos outros | Exercício 5 |
| 7 | A missão: o dicionário da empresa | Checkpoint 4 |

Mais três anexos: **A** com os cinco erros que o dia produz, **B** com sete
extras opcionais e **C** com o checklist de entrega.

## O tom do material

Este PDF é o primeiro escrito inteiro no estilo ASD-STE100 aplicado ao
português: frase curta, uma instrução por frase, imperativo, uma palavra um
significado. Vale para a teoria também, não só para os enunciados. É para ler em
voz alta assim mesmo.

**Vocabulário fixo, o mesmo da operação 02.** `célula` é sempre o grupo de
alunos e `campo` é sempre o quadradinho da tabela. Acrescentam-se hoje três
termos, e eles não têm sinônimo neste material: **entidade** (vira tabela),
**atributo** (vira coluna) e **domínio** (tipo mais tamanho mais
obrigatoriedade).

## Como conduzir

O capítulo 1 é o gancho e depende de a turma **não** ter o método ainda. As duas
listas da pousada são plausíveis de propósito. Deixe a turma defender as duas
antes de entregar o capítulo 2, senão o exercício 1 não produz divergência e o
capítulo 2 perde a razão de existir.

O capítulo 2 é o eixo do dia. O procedimento de **substantivo e verbo** e o
**critério da pergunta** voltam em todos os capítulos seguintes e na missão.
Vale escrever os dois no quadro e deixar lá até o dia 7.

Os capítulos 3 e 4 são teoria com exercício no fim. O capítulo 4 é o mais denso
e o mais chato: ele é o que faz a operação 08 render.

O capítulo 5 é curto e é o que a turma leva do dia. Os dois dicionários da
pousada são o modelo que a missão copia.

O capítulo 6 é o primeiro em que a célula corrige um documento inteiro em vez de
uma tabela. Espere lentidão aqui.

O capítulo 7 é a aula toda. **Reserve a última hora e meia para ele.** Ele é
maior que o capítulo 7 da operação 02, porque a missão é o documento inteiro e
não uma tabela.

## Onde a turma trava

- **Exercício 2, item 5 (marcenaria).** Falta o dado "dias trabalhados por
  ajudante em cada serviço". Quase nenhuma dupla acha sozinha. Conduza pela
  pergunta do dono: "para tirar a diária, você precisa saber o quê?".
- **Exercício 3, praça e ingrediente.** Os dois parecem atributo e são entidade.
  A diferença está nas informações do negócio, não no nome. Célula que decidiu
  sem reler a lista de informações erra os dois.
- **Exercício 4, `cpf_responsavel`.** Obrigatória para menor, inexistente para
  adulto. Não existe marca certa hoje. A saída é declarar opcional e escrever a
  regra na descrição. Deixe a discussão correr três minutos.
- **Marcar tudo como obrigatório.** É o erro 4 do anexo A e o mais comum do dia.
  O sintoma é a célula justificar com a palavra "importante". Importante não é o
  critério: o critério é impedir a linha de existir.
- **Separar demais, de novo.** A operação 02 já produziu isso. Hoje reaparece em
  `status`, `forma_pagamento` e `cor`. A regra do só nome, no capítulo 3, e o
  erro 3 do anexo A existem para segurar.

## A missão da célula

**O dicionário de dados da empresa.** A célula escreve as perguntas do dono,
levanta os candidatos pela ficha da operação 01, aplica o teste das três
perguntas, fecha entre 5 e 8 entidades, e escreve o **dicionário completo de
três tabelas** com as oito colunas. Uma das três é obrigatoriamente a tabela
desenhada na operação 02. As tabelas restantes entram só com nome, PK e de 3 a 5
colunas.

O passo 3 é o que separa a entrega boa da entrega fraca: a célula liga cada
pergunta do dono às colunas que respondem a pergunta. Célula que não consegue
fazer essa ligação descobre ali, no papel, que falta coluna.

O passo 4 lista, em oito itens, exatamente o que vai no caderno. O modelo do
dicionário para copiar está logo abaixo dele.

A entrega é pelo botão **Entregar no site**, no card da missão. Uma por célula.

## Pendências no site

1. O `curriculo.js` ainda descreve o dia 2 como "Instalar o cofre" e a missão do
   dia 2 como "Instalar o SGBD". A operação 02 foi dada como "O olho clínico",
   sem instalação. O título, o `vemos` e o card da missão do dia 2 precisam ser
   ajustados.
2. O dia 3 no `curriculo.js` já está correto: "O que a empresa guarda",
   modelagem conceitual, levantamento e dicionário de dados. Nada a mudar.
3. A missão do site para os dias 3 a 7 é "O modelo completo", uma entrega só
   para cinco dias. O dicionário de hoje é a primeira parcela dela. Vale marcar
   isso no card, senão a célula acha que a entrega de hoje é a entrega final.

## A instalação do SGBD

O README da operação 02 anunciou para hoje a instalação do SGBD. Ela foi
adiada de novo, de propósito: o dicionário de dados ocupa as quatro horas
inteiras, e instalação pela metade custa o capítulo 7.

A instalação e o DER em ferramenta (brModelo ou dbdiagram) ficam para a
operação 06, que já é o dia do desenho no site. Quem assumir a turma na
operação 04 precisa saber disso: **a turma chega no dia 4 sem ambiente
instalado**, com o modelo inteiro no papel.

## O que o dia prepara

O dicionário é o insumo direto de três operações. A operação 04 pega os verbos
anotados hoje e os transforma em relacionamento com cardinalidade. A operação 05
formaliza as PK e FK marcadas hoje. A operação 08 traduz o dicionário em
`CREATE TABLE`, quase linha por linha: tipo, tamanho, obrigatoriedade e valor
padrão já estão decididos.

## Consulta

A teoria deste dia corresponde às seções **A — Banco de dados** e
**B — Modelagem** do Caderno:

https://uc5-banco-de-dados.vercel.app/caderno.html#ref-modelagem
