# LOO_1_Anhanguera
# 🐾 Classe Animal em Java

Este projeto implementa uma **classe `Animal` em Java** para representar características e comportamentos básicos de um animal, utilizando conceitos fundamentais de programação orientada a objetos (POO).

---
🔍 Significado dos Tipos de Dados
String → Representa uma sequência de caracteres (texto).

Usa aspas duplas "texto".

int → Número inteiro, positivo ou negativo, sem casas decimais.

Não usa aspas.

boolean → Armazena valores lógicos true (verdadeiro) ou false (falso).

Não usa aspas.

double → Número decimal (ponto flutuante) com casas decimais.

Não usa aspas.

char → Um único caractere, armazenado entre aspas simples 'c'.

--------------------------------------------------------------------------------------
📌 Tipos de Aspas no Java

| Tipo de Dado              | Aspas Utilizadas  | Exemplo         |

| ------------------------- | ----------------- | --------------- |

| **String**                | Aspas duplas `"`  | `"Euclides"`    |

| **char**                  | Aspas simples `'` | `'M'`           |

| Números (`int`, `double`) | Sem aspas         | `4`, `3.5`      |

| Booleanos (`boolean`)     | Sem aspas         | `true`, `false` |

---------------------------------------------------------------------------------------------

📌 Finalidade de Cada Comando e Estrutura
public class Animal { ... }
Define uma classe chamada Animal.

Em Java, classe é um molde que define atributos (dados) e métodos (ações) que um objeto poderá ter.

Atributos da classe
String nomeAnimal; → Nome do animal.

int numeroDePatas; → Quantidade de patas.

boolean temRabo; → Informa se tem rabo (true ou false).

String cor; → Cor do animal.

int idade; → Idade em anos.

double peso; → Peso (não usado no exemplo, mas está pronto para uso).

String tipoAlimentacao; → Tipo de comida que consome.

char genero; → Gênero ('M' ou 'F').

public void printStatus()


Método que não retorna valor (void).

Imprime todos os atributos do animal usando System.out.println().

System.out.println()
Comando para exibir informações no console.

Ex.: System.out.println("Nome: " + nomeAnimal); imprime Nome: Euclides.

public static void main(String[] args)
Método principal, ponto de entrada do programa.

public → Pode ser acessado de qualquer lugar.

static → Pertence à classe, não a um objeto específico.

void → Não retorna valor.

String[] args → Argumentos de linha de comando (não usados aqui).

Criação de Objeto

Animal cachorro = new Animal();

Cria uma instância (objeto) da classe Animal.

Atribuição de valores

cachorro.nomeAnimal = "Euclides";

Define valores para os atributos do objeto criado.

Chamada de método

cachorro.printStatus();

Executa o método que imprime os atributos.

🧠 Por que o código foi estruturado assim?
Separação de responsabilidades:

Os atributos armazenam as informações do animal.

O método printStatus() é responsável apenas por exibir essas informações.

Orientação a Objetos:

Facilita a criação de múltiplos animais sem duplicar código.

Cada animal pode ter seus próprios valores.

Clareza e manutenção:

Caso seja necessário mudar a forma de exibir as informações, basta alterar o método printStatus().

📊 Tabela de Atributos no Exemplo

| Atributo          | Tipo    | Aspas Usadas | Valor Atribuído   |

| ----------------- | ------- | ------------ | ----------------- |

| `nomeAnimal`      | String  | Duplas `"`   | Euclides          |

| `numeroDePatas`   | int     | Nenhuma      | 4                 |

| `temRabo`         | boolean | Nenhuma      | true              |

| `cor`             | String  | Duplas `"`   | Tigrado           |

| `idade`           | int     | Nenhuma      | 4                 |

| `peso`            | double  | Nenhuma      | *(não atribuído)* |

| `tipoAlimentacao` | String  | Duplas `"`   | Ração             |

| `genero`          | char    | Simples `'`  | M                 |

💻 Como Executar
Salvar o código como Animal.java.

Compilar:

javac Animal.java

Executar:

java Animal

📌 Exemplo de Saída

Nome: Euclides
Número de patas: 4
Tem rabo? true
Cor: Tigrado
Idade: 4
Tipo de alimentação: Ração
Genero: M
------------------------------------------------

