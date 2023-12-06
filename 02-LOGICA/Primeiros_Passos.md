```python
#Este sinal serve para comentar um código para que o usuário saiba o que o código faz

"""
Usando 3 aspas podemos
comentar várias linhas
assim quando o código for executado o scrip pula estas linhas
"""


print("Script executado com sucesso!")
```

    Script executado com sucesso!



```python
"""
O que é uma variável?

Uma variável é um nome que se refere a um valor armazenado na memória do computador. 
Em programação, as variáveis são usadas para armazenar dados que podem ser utilizados 
e manipulados ao longo de um programa.

Em Python, as variáveis não são declaradas com um tipo específico. 

No entanto, os tipos de dados que você pode armazenar em uma variável incluem:
"""

#Principais tipos de variaveis

#Inteiros (int): Números inteiros, sem parte decimal.
inteiro = 42
print("Inteiro:", inteiro)

#Ponto Flutuante (float): Números reais, que têm uma parte decimal.
flutuante = 42.0
print("Flutuante:", flutuante)

#Complexos (complex): Números complexos, que têm uma parte real e uma parte imaginária.
complexo = 3 + 4j
print("Complexo:", complexo)

#Strings (str): Sequências de caracteres.
texto = "Olá, Mundo!"
print("Texto:", texto)


"""
Os termos "mutável" e "imutável" referem-se à capacidade de alterar o conteúdo 
de um objeto depois que ele foi criado.

Mutável: Significa que o conteúdo do objeto pode ser alterado após a sua criação. As 
listas em Python são mutáveis, o que significa que você pode modificar seus elementos.

    
Imutável: Significa que o conteúdo do objeto não pode ser alterado após a sua criação. As 
tuplas em Python são imutáveis, o que significa que, uma vez criada, você não pode modificar 
seus elementos.

"""
#Listas (list): Uma coleção ordenada e mutável.
lista = [1, 2, 3, 3]
print("Lista:", lista)

#Tuplas (tuple): Uma coleção ordenada e imutável.
tupla = (1, 2, 3, 4, 5)
print("Tupla:", tupla)

#Conjuntos (set): Uma coleção não ordenada de itens únicos.
conjunto = {1, 2, 3, 3}
print("Conjunto:", conjunto)

#Dicionários (dict): Uma coleção não ordenada de pares chave-valor.
dicionario = {"chave": "valor"}
print("Dicionário:", dicionario)

#Booleanos (bool): Valores verdadeiro ou falso.
booleano = True
print("Booleano:", booleano)

#NoneType (None): Um tipo especial que representa a ausência de valor.
nenhum = None
print("NoneType (None):", nenhum)
```

    Inteiro: 42
    Flutuante: 42.0
    Complexo: (3+4j)
    Texto: Olá, Mundo!
    Lista: [1, 2, 3, 3]
    Tupla: (1, 2, 3, 4, 5)
    Conjunto: {1, 2, 3}
    Dicionário: {'chave': 'valor'}
    Booleano: True
    NoneType (None): None



```python

```


```python
#Variaveis

idade = 30
nome = "Nicole"

print("Nome:", nome)
print("Idade:", idade)
print("Nome:", nome, ", Idade:", idade)

"""
idade = 30: Nesta linha, estamos declarando uma variável chamada 
idade e atribuindo o valor 30 a ela. Essa variável pode ser usada posteriormente 
no código para referenciar esse valor.

nome = "Nicole": Aqui, estamos declarando uma variável chamada nome e atribuindo 
a ela a string "Nicole". Assim como a variável idade, essa variável também pode ser 
usada posteriormente no código.

print("Nome: ", nome, " Idade: ", idade): Esta linha usa a função print para 
imprimir uma string na tela. Ela começa com a string literal "Nome: ", seguida pelo valor 
da variável nome, que é "Nicole", uma string literal com espaço e " Idade: ", e finalmente 
o valor da variável idade, que é 30.
"""
```

    Nome: Nicole
    Idade: 30
    Nome: Nicole , Idade: 30



```python

```


```python
#Podemos obter o tipo de uma variável usando a função type

"""
nome = str("Ana Paula"): A string "Ana Paula" é passada para a função str(), que 
retorna a mesma string. A função str() é desnecessária neste caso, pois "Ana Paula" já 
é uma string. A variável nome é atribuída a essa string.

idade = int(31): O número inteiro 31 é passado para a função int(), que retorna o mesmo 
número. Novamente, a função int() é desnecessária aqui, pois 31 já é um inteiro. A variável idade é 
atribuída a esse valor inteiro.

print(type(nome)): A função type() retorna o tipo da variável nome, que é <class 'str'>, já que nome 
é uma string. Esse valor é então impresso, resultando na saída:

"""

nome = str("Ana Paula")
idade = 31

print(type(nome))
print(type(idade))
```

    <class 'str'>
    <class 'int'>



```python
#As variáveis diferenciam letras maiúsculas de minúsculas

i = 30
I = "Ana"

print(i)
print(I)
```

    30
    Ana



```python
#Podemos também atribuir valores a várias variáveis em uma só linha

"""
O código está utilizando a desempacotamento de tuplas para atribuir 
várias variáveis em uma única linha e, em seguida, imprimindo essas variáveis. 

var1, var2, var3, var4 = "Texto 1", "Texto 2", "Texto 3", "Texto 4":
Nesta linha, quatro strings são atribuídas a quatro variáveis respectivas 
em uma única operação. 

A variável var1 é atribuída à string "Texto 1", 
var2 à string "Texto 2", 
var3 à string "Texto 3", 
var4 à string "Texto 4".
"""
var1, var2, var3, var4 = "Texto 1", "Texto 2", "Texto 3", "Texto 4"

print(var1)
print(var2)
print(var3)
print(var4)
```

    Texto 1
    Texto 2
    Texto 3
    Texto 4



```python

```


```python
#Podemos atribuir o mesmo valor a várias variáveis em uma única linha

var1 = var2 = var3 = var4 = "Ana Paula"

print(var1)
print(var2)
print(var3)
print(var4)
```

    Ana Paula
    Ana Paula
    Ana Paula
    Ana Paula



```python

```


```python
#Se tiver uma coleção de valores em uma lista, podemos extrair em variáveis. Isso é chamado de descompactar

exemplo = "Texto 1", "Texto 2", "Texto 3", "Texto 4"
var1, var2, var3, var4 = exemplo

print(var1)
print(var2)
print(var3)
print(var4)
```

    Texto 1
    Texto 2
    Texto 3
    Texto 4



```python

```


```python
#Para juntar textos e variáveis em Python usamos o caracter + ou ,

nome = "Ana Paula"

print("O nome dela é " + nome)
```

    O nome dela é Ana Paula



```python
numero1 = "Dez"
numero2 = "Cinco"

print(numero1 + numero2)
```

    DezCinco



```python

```


```python
#Para juntar textos e variáveis em Python usamos o caracter + ou ,

"""
Definindo duas variáveis, nome e sobrenome, que contêm strings. Em seguida, 
usamos a concatenação de strings para juntar essas variáveis e imprimi-las como um 
nome completo. 

    Vamos analisar cada parte:

    nome = "Thuane": Atribui a string "Thuane" à variável nome.

    sobrenome = "Alves": Atribui a string "Alves" à variável sobrenome.

    print("Nome completo: " + nome + " " + sobrenome)
    
        - "Nome completo: " é uma string literal que será o começo da saída.
        - nome é a variável que contém a string "Thuane", e ela é concatenada à string anterior.        
        - " " é uma string literal contendo um espaço, e ela é usada para separar o nome e o sobrenome na saída.
        - sobrenome é a variável que contém a string "Alves", e ela é concatenada ao restante da string.

    A concatenação dessas partes resulta na string "Nome completo: Thuane Alves", que é então impressa.
    
"""

nome = "Thuane"
sobrenome = "Alves"

print("Nome completo: " + nome + " " + sobrenome)
```

    Nome completo: Thuane Alves



```python

```


```python
# Exercício de Variáveis em Python

# 1. Declare uma variável chamada "idade" e atribua o valor 25 a ela.
idade = 25

# 2. Declare uma variável chamada "nome" e atribua o valor "João" a ela.
nome = "João"

# 3. Declare uma variável chamada "saldo" e atribua o valor 100.50 a ela.
saldo = 100.50

# 4. Crie uma variável chamada "soma" e atribua a ela a soma das variáveis "idade" e "saldo".
soma = idade + saldo

# 5. Imprima na tela o valor da variável "soma".
print("A soma é:", soma)

```

    A soma é: 125.5



```python

```


```python
# Exercício de Variáveis em Python

# 1. Crie uma variável chamada "nota1" e atribua o valor 7.5 a ela.
nota1 = 7.5

# 2. Crie uma variável chamada "nota2" e atribua o valor 8.3 a ela.
nota2 = 8.3

# 3. Crie uma variável chamada "nota3" e atribua o valor 6.9 a ela.
nota3 = 6.9

# 4. Calcule a média das três notas e atribua o resultado a uma variável chamada "media".
media = (nota1 + nota2 + nota3) / 3

# 5. Imprima na tela o valor da variável "media" formatado com duas casas decimais.
print("A média é:", format(media, ".2f"))

```

    A média é: 7.57



```python

```


```python
nome = input("Digite seu nome: \n")

print("\nO seu nome é: " + nome)
```

    Digite seu nome: 
    Rodrigo Silva
    
    O seu nome é: Rodrigo Silva



```python

```


```python
"""
Solicita ao usuário que insira seu nome e duas notas, calcula a média dessas notas e, 
em seguida, imprime uma mensagem contendo o nome do aluno e a média calculada. 

Vamos analisar cada parte do código:

    nome = input("Digite seu nome"): Solicita ao usuário que digite seu nome e 
    armazena o valor inserido na variável nome.

    nota1 = float(input("Digite a nota 1")): Solicita ao usuário que digite a 
    primeira nota, converte o valor inserido para um número de ponto flutuante usando 
    float(), e armazena o resultado na variável nota1.

    nota2 = float(input("Digite a nota 2")): Semelhante à linha anterior, solicita ao 
    usuário que digite a segunda nota, converte o valor inserido para um número de ponto 
    flutuante e armazena o resultado na variável nota2.

    media = (nota1 + nota2) / 2: Calcula a média das duas notas somando nota1 e nota2, e dividindo 
    o resultado por 2. A média é armazenada na variável media.

    print("Aluno ", nome, " Média: ", media): Imprime uma mensagem formatada contendo o nome do 
    aluno e a média calculada. A função print() pode receber vários argumentos separados 
    por vírgulas, e imprimirá cada um deles sequencialmente, separados por um espaço. 
    
    O resultado final combina os valores das variáveis nome e media com as strings 
    literais para criar a saída completa.

"""

nome = input("Digite seu nome: \n")
nota1 = float(input("Digite a nota 1: "))
nota2 = float(input("Digite a nota 2: "))

media = (nota1 + nota2) / 2

print("\nAluno:", nome, " Média:", media)
```

    Digite seu nome: 
    Roberta
    Digite a nota 1: 6
    Digite a nota 2: 7
    
    Aluno: Roberta  Média: 6.5



```python

```


```python
"""

Exercício: Tabuada Personalizada

Escreva um programa que solicite ao usuário um número inteiro e exiba a tabuada desse número, do 1 ao 10.

Entrada:

    Um número inteiro n, representando o número do qual você deseja ver a tabuada.

Saída:

    O programa deve imprimir dez linhas, mostrando o resultado da multiplicação do 
    número digitado com os números de 1 a 10, no formato n * i = resultado, onde n é o número 
    digitado pelo usuário e i varia de 1 a 10.

Exemplo de Entrada:

A tabuada de qual número deseja ver 5


Exemplo de Saída:

5  * 1 =  5
5  * 2 =  10
5  * 3 =  15
5  * 4 =  20
5  * 5 =  25
5  * 6 =  30
5  * 7 =  35
5  * 8 =  40
5  * 9 =  45
5  * 10 =  50


"""

#Tabuada

nDigitado = int(input("A tabuada de qual número você deseja ver? "))

print(nDigitado, "* 1  =", nDigitado * 1)
print(nDigitado, "* 2  =", nDigitado * 2)
print(nDigitado, "* 3  =", nDigitado * 3)
print(nDigitado, "* 4  =", nDigitado * 4)
print(nDigitado, "* 5  =", nDigitado * 5)
print(nDigitado, "* 6  =", nDigitado * 6)
print(nDigitado, "* 7  =", nDigitado * 7)
print(nDigitado, "* 8  =", nDigitado * 8)
print(nDigitado, "* 9  =", nDigitado * 9)
print(nDigitado, "* 10 =", nDigitado * 10)
```

    A tabuada de qual número você deseja ver? 8
    8 * 1  = 8
    8 * 2  = 16
    8 * 3  = 24
    8 * 4  = 32
    8 * 5  = 40
    8 * 6  = 48
    8 * 7  = 56
    8 * 8  = 64
    8 * 9  = 72
    8 * 10 = 80



```python

```


```python
"""

Exercício

Crie um algoritmo que solicite o ano de nascimento do usuário e 
com base no ano corrente imprima a idade

"""

ano_atual = 2023
ano_nascimento = int(input("Digite o ano de nascimento: "))

idade = ano_atual - ano_nascimento

print("Sua idade é:", idade)
```

    Digite o ano de nascimento: 1950
    Sua idade é: 73



```python

```


```python
#Números randomicos - Números aleatórios
import random

print(random.randrange(1, 1000))


#Gerar um número de ponto flutuante aleatório entre 0 e 1:
print(random.random())

#Gerar um número inteiro aleatório entre dois valores (inclusive):
print(random.randint(10, 20)) # Gera um número entre 10 e 20, inclusive.

#Escolher aleatoriamente um elemento de uma lista:
frutas = ["maçã", "banana", "cereja"]
print(random.choice(frutas)) # Escolhe uma fruta aleatoriamente da lista.

#Embaralhar aleatoriamente uma lista:
numeros = [1, 2, 3, 4, 5]
random.shuffle(numeros)
print(numeros) # A lista 'numeros' agora está embaralhada.

#Gerar um número de ponto flutuante aleatório em um intervalo específico:
print(random.uniform(5.5, 9.5)) # Gera um número de ponto flutuante entre 5.5 e 9.5.
```

    605
    0.03984174916931016
    13
    maçã
    [4, 1, 5, 2, 3]
    9.01634429453945



```python

```


```python
#Imprimindo a posição das letras

posicaoLetra = "Python"
print(posicaoLetra[0])
print(posicaoLetra[1])
print(posicaoLetra[2])
print(posicaoLetra[3])
print(posicaoLetra[4])
print(posicaoLetra[5])
```

    P
    y
    t
    h
    o
    n



```python

```


```python
"""
"slicing" (fatiamento) em Python para extrair partes de uma string. 


    frase = "Olá, mundo!": Essa linha atribui a string "Olá, mundo!" à variável frase.

    parte = frase[4:8]: Isso fatia a string da posição 4 até a posição 8 (exclusiva). Em 
    Python, a indexação começa em 0, então a posição 4 é o quinto caractere da string, que é um 
    espaço, e a posição 8 é o nono caractere, que é a letra 'd'. Então, essa fatia inclui os 
    caracteres nas posições 4, 5, 6 e 7, que são " mun". O valor de parte será a string " mun".

    print(parte): Imprime o valor de parte, que é " mun".

    primeiros = frase[:5]: Isso fatia a string da posição inicial (inclusa) até a 
    posição 5 (exclusiva). Como não há um valor antes dos dois pontos, ele assume o 
    início da string. Portanto, essa fatia inclui os caracteres nas posições 0, 1, 2, 3 e 4, que 
    são "Olá,". O valor de primeiros será a string "Olá,".

    print(primeiros): Imprime o valor de primeiros, que é "Olá,".

    ultimos = frase[-6:]: Isso fatia a string da posição -6 até o final da string. Em 
    Python, índices negativos contam a partir do final da string, então a posição -6 é o sexto 
    caractere a partir do final, que é a letra 'm'. Como não há valor depois dos dois pontos, ele assume 
    o final da string. Portanto, essa fatia inclui os caracteres 'mundo!'. O valor de ultimos será a string "mundo!".

    print(ultimos): Imprime o valor de ultimos, que é "mundo!".


"""

# Slice
frase = "Olá, mundo!"

# Obtendo uma parte da string usando slice
parte = frase[4:8]
print(parte)  # Saida:  mun

# Obtendo os primeiros 5 caracteres da string
primeiros = frase[:5]
print(primeiros)  # Saida: Olá,

# Obtendo os últimos 6 caracteres da string
ultimos = frase[-6:]
print(ultimos)  # Saida: mundo!
```

     mun
    Olá, 
    mundo!



```python

```


```python
#Verifica se a palavra python está na frase


frase = "O módulo de python é muito legal"

print("python" in frase)

"""
O operador in é usado em Python para verificar a presença de um valor dentro 
de uma sequência (como uma string, lista, ou tupla). Neste caso, está sendo 
usado para verificar se uma determinada substring está contida em uma string maior.
"""

```

    True





    '\nO operador in é usado em Python para verificar a presença de um valor dentro \nde uma sequência (como uma string, lista, ou tupla). Neste caso, está sendo \nusado para verificar se uma determinada substring está contida em uma string maior.\n'




```python

```


```python
#verifica se a palavra python está na frase
frase = "O módulo de python é muito legal"

#if - se
if "python" in frase:
    print("Sim, a palavra python está presente na frase.")
```

    Sim, a palavra python está presente na frase.



```python

```


```python
#strip - Usamos para remover espaços em branco do inicio e do final da frase

frase = "        O módulo de python é muito legal       "

print(frase.strip())
```

    O módulo de python é muito legal



```python

```


```python
"""
O uso do método split em uma string, que é uma maneira útil de dividir uma string em uma 
lista de substrings com base em um determinado separador.

    frase = "Olá, como vai você?": Essa linha atribui a string "Olá, como vai você?" à variável frase.

    palavras = frase.split(): O método split é chamado na string frase sem qualquer argumento, o que 
    significa que ele usará espaços em branco como o separador padrão. A string original é dividida onde 
    quer que haja um espaço, e as partes resultantes são retornadas como uma lista de strings. Neste caso, 
    a lista resultante será ['Olá,', 'como', 'vai', 'você?'].

    print(palavras): Esta linha imprime a lista de palavras que foi criada, resultando na saída:

     ['Olá,', 'como', 'vai', 'você?']

O método split é frequentemente usado para dividir uma string em palavras ou em partes menores 
com base em um delimitador específico.

"""


#split, join e strip são métodos muito úteis da str
frase = "Olá, como vai você?"
palavras = frase.split()  # Dividindo a frase em palavras usando o espaço em branco como separador
print(palavras)
# Saída: ['Olá,', 'como', 'vai', 'você?']
```

    ['Olá,', 'como', 'vai', 'você?']



```python

```


```python
"""
método join, que é o oposto do método split que você viu anteriormente. Ele é usado para juntar 
uma lista de strings em uma única string, usando um delimitador específico. 


    palavras = ['Olá,', 'como', 'vai', 'você?']: Essa linha cria uma lista chamada palavras 
    contendo quatro strings.

    frase = ' '.join(palavras): Esta linha usa o método join, chamando-o na 
    string ' ' (um espaço em branco). O método join pega a lista palavras como argumento e 
    concatena seus elementos em uma única string, colocando um espaço em branco entre cada 
    elemento. O resultado é a string "Olá, como vai você?", que é então atribuído à variável frase.

    print(frase): Esta linha imprime o valor da variável frase, resultando na saída:

    Olá, como vai você?

Em resumo, o método join é uma maneira eficiente de combinar uma lista de strings em uma única 
string, usando um delimitador específico (neste caso, um espaço em branco).
"""


#Método join(): O método join() junta os elementos de uma lista em uma única string, utilizando um separador especificado entre cada elemento.

palavras = ['Olá,', 'como', 'vai', 'você?']
frase = ' '.join(palavras)  # Juntando as palavras com um espaço em branco entre elas
print(frase)
# Saída: "Olá, como vai você?"
```

    Olá, como vai você?



```python

```


```python
texto = "   Olá!    "
texto_strip = texto.strip()  # Removendo espaços em branco do início e do final
print(texto_strip)
# Saída: "Olá!"

"""
Nessa parte do código, a função strip() é chamada sem argumentos, e ela remove 
todos os espaços em branco no início e no final da string armazenada na variável texto. 

Espaços em branco incluem espaços, tabulações e caracteres de nova linha. No exemplo 
dado, a string " Olá! " tem três espaços antes e quatro espaços depois do texto "Olá!". Após a 
chamada strip(), a variável texto_strip contém a string "Olá!" sem espaços extras, e essa 
string é impressa.
"""

texto = "********Olá!*********"
texto_strip = texto.strip('*')  # Removendo os caracteres '*' do início e do final
print(texto_strip)
# Saída: "Olá!"

"""
Nesta parte do código, a função strip() é chamada com o argumento "*", o que significa 
que ela vai remover todas as ocorrências do caractere "*" no início e no final da string. A 
string "********Olá!*********" tem oito asteriscos antes e nove asteriscos depois do 
texto "Olá!". A chamada strip('*') remove todos esses asteriscos, resultando na 
string "Olá!", que é armazenada na variável texto_strip e impressa.

Em resumo, a função strip() sem argumentos remove espaços em branco do início e do 
final de uma string, e com um argumento, remove todas as ocorrências desse caractere 
específico do início e do final da string.
"""
```

    Olá!
    Olá!



```python

```


```python
#Utilizando Formated Strings

nome = "Alice"
idade = 25
altura = 1.65

# Criando uma mensagem formatada usando f-string
mensagem = f"Olá, meu nome é {nome}. Tenho {idade} anos e minha altura é {altura:.2f} metros."

print(mensagem)


"""
Explicação:

    Definindo Variáveis: Três variáveis são definidas: nome, que é uma 
    string com o valor "Alice"; idade, que é um inteiro com o valor 25; e 
    altura, que é um número de ponto flutuante com o valor 1.65.

    Criando a Mensagem Formatada (f-string): Uma f-string é uma forma de formatar 
    strings em Python 3.6 ou superior, onde você pode incorporar expressões entre 
    chaves {} que serão avaliadas em tempo de execução.
    
        {nome}: Substituído pelo valor da variável nome, que é "Alice".
        {idade}: Substituído pelo valor da variável idade, que é 25.
        {altura:.2f}: Substituído pelo valor da variável altura, que é 1.65, formatado 
        com duas casas decimais. O .2f dentro das chaves significa que o número deve ser formatado 
        como um número de ponto flutuante com duas casas decimais.
"""
```

    Olá, meu nome é Alice. Tenho 25 anos e minha altura é 1.65 metros.



```python

```


```python
# Métodos para Strings
texto = "OLá, mundo!"

# Método upper() - Converte a string para maiúsculas
texto_upper = texto.upper()
print(texto_upper)  # Output: OLÁ, MUNDO!

# Método lower() - Converte a string para minúsculas
texto_lower = texto.lower()
print(texto_lower)  # Output: olá, mundo!

# Método capitalize() - Capitaliza a primeira letra da string
#a primeira letra "o" é convertida em maiúscula, resultando em "Olá, mundo!". As demais letras permanecem em minúsculas.
texto_capitalize = texto.capitalize()
print(texto_capitalize)  # Output: Olá, mundo!

# Método count() - Conta o número de ocorrências de um determinado caractere ou substring na string
ocorrencias = texto.count("o")
print(ocorrencias)  # Output: 2

# Método replace() - Substitui todas as ocorrências de uma substring por outra
texto_substituido = texto.replace("mundo", "amigo")
print(texto_substituido)  # Output: Olá, amigo!

# Método split() - Divide a string em uma lista de substrings com base em um caractere delimitador
palavras = texto.split(",")
print(palavras)  # Output: ['Olá', ' mundo!']

# Método join() - Junta uma lista de strings em uma única string, separadas por um caractere específico
lista_palavras = ['Olá', 'mundo!']
texto_junto = ",".join(lista_palavras)
print(texto_junto)  # Output: Olá,mundo!
```

    OLÁ, MUNDO!
    olá, mundo!
    Olá, mundo!
    1
    OLá, amigo!
    ['OLá', ' mundo!']
    Olá,mundo!



```python

```


```python
# Exercício de Manipulação de Strings em Python

# 1. Crie uma variável chamada "nome" e atribua a ela o valor "Maria".
nome = "Maria"

# 2. Crie uma variável chamada "sobrenome" e atribua a ela o valor "Silva".
sobrenome = "Silva"

# 3. Crie uma variável chamada "idade" e atribua a ela o valor 30.
idade = 30

# 4. Concatene as variáveis "nome" e "sobrenome" em uma nova variável chamada "nome_completo".
nome_completo = nome + " " + sobrenome

# 5. Imprima na tela o valor da variável "nome_completo".
print(nome_completo)

# 6. Crie uma variável chamada "mensagem" que utilize a função format para criar uma frase 
#personalizada com as variáveis "nome_completo" e "idade".
mensagem = "Olá, meu nome é {} e tenho {} anos.".format(nome_completo, idade)

# 7. Imprima na tela o valor da variável "mensagem".
print(mensagem)
```

    Maria Silva
    Olá, meu nome é Maria Silva e tenho 30 anos.



```python

```


```python
# Exercício de Manipulação de Strings em Python

# 1. Crie uma variável chamada "frase" e atribua a ela a seguinte 
#frase: "Python é uma linguagem de programação poderosa e versátil."

frase = "Python é uma linguagem de programação poderosa e versátil."

# 2. Imprima na tela o tamanho da frase, ou seja, a quantidade de 
#caracteres presentes nela.

tamanho_frase = len(frase)
print("Tamanho da frase:", tamanho_frase)

# 3. Crie uma variável chamada "palavra" e atribua a ela a primeira 
#palavra da frase.

palavra = frase.split()[0]
print("Primeira palavra da frase:", palavra)

# 4. Converta a variável "frase" para letras maiúsculas e atribua o 
#resultado a uma nova variável chamada "frase_maiuscula".

frase_maiuscula = frase.upper()
print("Frase em maiúsculas:", frase_maiuscula)

# 5. Substitua a palavra "poderosa" por "incrível" na variável 
#"frase" e atribua o resultado a uma nova variável chamada "frase_substituida".

frase_substituida = frase.replace("poderosa", "incrível")
print("Frase com substituição:", frase_substituida)
```

    Tamanho da frase: 58
    Primeira palavra da frase: Python
    Frase em maiúsculas: PYTHON É UMA LINGUAGEM DE PROGRAMAÇÃO PODEROSA E VERSÁTIL.
    Frase com substituição: Python é uma linguagem de programação incrível e versátil.



