📘 Desafio Controle de Fluxo
📌 Descrição

Este projeto foi desenvolvido como parte do desafio de Controle de Fluxo em Java.
O programa recebe dois números inteiros via terminal e realiza uma contagem com base na diferença entre eles.

Se o primeiro número for menor que o segundo, o programa imprime no console uma sequência de números até a diferença entre eles.

Se o primeiro número for maior que o segundo, é lançada uma exceção personalizada (ParametrosInvalidosException).

🛠️ Estrutura do Projeto
DesafioContador/
 ├── Contador.java
 └── ParametrosInvalidosException.java


Contador.java → Classe principal que contém a lógica do programa.

ParametrosInvalidosException.java → Classe que representa uma exceção personalizada.

▶️ Como Executar

Acesse a pasta do projeto:

cd DesafioContador


Compile os arquivos:

javac Contador.java ParametrosInvalidosException.java


Execute o programa:

java Contador

💻 Exemplo de Execução
Caso válido

Entrada:

Digite o primeiro parâmetro
12
Digite o segundo parâmetro
30


Saída:

Imprimindo o número 1
Imprimindo o número 2
...
Imprimindo o número 18

Caso inválido

Entrada:

Digite o primeiro parâmetro
30
Digite o segundo parâmetro
12


Saída:

O segundo parâmetro deve ser maior que o primeiro

✅ Tecnologias Utilizadas

Java 17+

VS Code (ou IDE de sua preferência)
