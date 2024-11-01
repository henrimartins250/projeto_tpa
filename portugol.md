# Técnicas de Programação de Algoritmos - ETEC
Aprendendo técnicas de programação com algoritmos em portugol, exemplos práticos de atividades que nos ensinaram usando muitos tipos de comandos.

## 📌Introdução à Lógica de Programação
Neste módulo, apresentamos os fundamentos da lógica de programação, essenciais para o desenvolvimento de algoritmos. Você aprenderá sobre variáveis, tipos de dados e operações básicas.
<img src="INTRODUCAO.jpeg">

# 📌O que é o Portugol?
O Portugol é uma linguagem de programação didática criada para facilitar o ensino de programação para falantes de português. Ela utiliza a língua portuguesa como base para seus comandos, tornando o aprendizado mais intuitivo e acessível.

### ✏️Principais características:

<strong>Simplicidade:</strong> Sintaxe similar ao português, facilitando a compreensão.
<strong>Foco na lógica:</strong> Permite concentrar-se nos conceitos básicos da programação.
<strong>Base para outras linguagens:</strong> Serve como introdução para linguagens mais complexas.
<strong>Didática:</strong> Utilizada em cursos e escolas para ensinar programação.

### ✏️Para que serve:
<strong>Ensinar programação:</strong> Introduzir os conceitos de algoritmos e lógica de programação.
<strong>Criar pequenos programas:</strong> Resolver problemas simples e desenvolver a lógica de programação.

### ✏️Em resumo:
O Portugol é uma excelente ferramenta para quem está começando a programar. Ao aprender Portugol, você estará dando o primeiro passo para dominar outras linguagens de programação e se tornar um desenvolvedor.

# 📌Estruturas de Controle

Aqui, vamos explorar as principais estruturas de controle utilizadas na linguagem Portugol, fundamentais para a tomada de decisões e repetição de blocos de código.

### ✏️SE e SENÃO
A estrutura SE permite a execução de um bloco de código se uma condição for verdadeira, enquanto SENÃO fornece uma alternativa.
Exemplo:
```
 se(idade <= 4)
    seila = 1
    senao se(idade > 4 e idade <= 7)
    seila = 2
    senao se(idade > 7 e idade <= 10)
    seila = 3
    senao se(idade > 10 e idade <= 13)
    seila = 4
    senao se(idade > 13 e idade <= 17)
    seila = 5
    senao se(idade > 17)
    seila = 6
    senao
    seila = -1
```

### ✏️ESCOLHA CASO
A estrutura ESCOLHA CASO permite executar diferentes blocos de código com base no valor de uma variável.
Exemplo:
```
escolha(seila){
  caso 1:
    escreva("nao aceito\n")
      pare
  caso 2:
    escreva("infantil A")
      pare
  caso 3:
    escreva("infantil B")
      pare
  caso 4:
    escreva("juvenil A")
      pare
  caso 5:
    escreva("juvenil B")
      pare
  caso 6:
    escreva("sênior")
      pare
  caso contrario:
    escreva("invalido")
      pare
  
  
}
```

# 📌Estruturas de Repetição
Neste módulo, aprofundamos nas estruturas de repetição, discutindo quando e como utilizá-las. Você entenderá como aplicá-las para resolver problemas práticos.

### ✏️Tipos de Estruturas de Repetição

### ✏️PARA
A estrutura PARA é utilizada para repetições com um número fixo de iterações.
Exemplo:
``

 para (contador = 0; contador <= numero; contador++ ){
      se((contador % 2)== 0)
      somapar = somapar + contador
      senao{
        switch = verdadeiro
      }

 para (contador = 0; contador <= numero; contador++ ){
      se((contador % 2)== 1)
      somaimpar = somaimpar + contador
      senao{
        switch = falso
      }
``
### ✏️ENQUANTO
A estrutura ENQUANTO repete um bloco de código enquanto uma condição for verdadeira.
Exemplo:
``

  enquanto(switch == falso){
    para (contador = 0; contador <= numero; contador++ ){
      se((contador % 2)== 0)
      somapar = somapar + contador
      senao{
        switch = verdadeiro
      }
    }
    }

    enquanto(switch == verdadeiro){
    para (contador = 0; contador <= numero; contador++ ){
      se((contador % 2)== 1)
      somaimpar = somaimpar + contador
      senao{
        switch = falso
      }
    }
    }
``


# 📌Vetores

### ✏️O que são Vetores?
Em Portugol, um vetor é uma estrutura que permite armazenar vários valores de um mesmo tipo em uma única variável. Ele é como uma "caixa" dividida em várias posições, e cada posição pode guardar um valor.
Exemplo de um vetor:
``
 inteiro vetor[5] = {1, 2, 3, 4, 5}
``


A prática constante com os conceitos de lógica de programação e as estruturas de controle em Portugol é fundamental para o desenvolvimento de suas habilidades. A estrutura modular deste curso facilitará a assimilação do conteúdo e o preparará para desafios mais complexos na área.
