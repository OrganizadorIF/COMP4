---
layout: default
title: Linguagens de Programação II
parent: Disciplinas
nav_order: 4
---

<h1 align="center"><span style='font-weight: bold;'>Linguagens de Programação II</span></h1>

<h2 style="color: black;" align="center"><span style='font-weight: bold;'>Professor(a):</span> Fernanda Maria Ribeiro</h2>

<h2 style="color: black; margin-bottom: 20px;" align="center"><span style='font-weight: bold;'>Mapa Conceitual</span></h2>

![](../../assets/images/mapalp2.png)

<h2 style="color: black; margin-bottom: 20px;" align="center"><span style='font-weight: bold;'>Resumo</span></h2>

<div style="text-align: justify; margin-bottom: 20px;">"Linguagens de Programação II", com foco em Java, aprofunda-se nos conceitos avançados dessa linguagem amplamente utilizada. Explora tópicos como herança, polimorfismo, interfaces, manipulação de exceções, programação concorrente com threads e coleções avançadas. Além disso, abrange a implementação de padrões de design orientados a objetos e o uso de ferramentas para otimização de código e desenvolvimento ágil. Este curso capacita os alunos a utilizar de forma avançada e eficiente os recursos oferecidos pela linguagem Java para solucionar problemas complexos na prática da programação.</div>

<h2 style="color: black; margin-bottom: 20px;" align="center"><span style='font-weight: bold;'>Conceitos Importantes</span></h2>

<div style="text-align: justify; margin-bottom: 20px;"><b>Herança:</b> Conceito que permite que uma classe (chamada de classe derivada ou subclasse) herde atributos e métodos de outra classe (chamada de classe base ou superclasse). Isso permite a criação de hierarquias e reutilização de código, onde a classe derivada pode estender ou modificar o comportamento da classe base, promovendo uma relação de especialização e generalização entre as classes.</div>

Exemplo de Herança (Java):

```java
// Class pai
public class Veiculo { 
   public String modelo; 
   public String marca;
}

// Classe filho 1
public class Carro extends Veiculo {
   public String porta;
}

// Classe filho 2
public class Moto extends Veiculo {
   public int bau_carga;
}
```

<div style="text-align: justify; margin-bottom: 20px;"><b>Interface:</b> São como contratos, definindo um conjunto de métodos que uma classe deve implementar se prometer seguir essa interface. Elas não contêm implementações de métodos, apenas suas assinaturas, oferecendo um padrão para comportamentos. Classes podem implementar múltiplas interfaces, permitindo a aplicação de comportamentos diferentes sem herança múltipla.</div>

Exemplo de Interface (Java):

```java
// Definição da interface
interface Animal {
    void fazerSom();
}

// Implementação da interface em uma classe
class Cachorro implements Animal {
    public void fazerSom() {
        System.out.println("Au au!");
    }
}

// Usando a interface
public class ExemploInterface {
    public static void main(String[] args) {
        Animal meuAnimal = new Cachorro();
        meuAnimal.fazerSom(); // Saída: "Au au!"
    }
}
```

<h2 style="color: black; margin-bottom: 20px;" align="center"><span style='font-weight: bold;'>Materiais de Estudo</span></h2>

- PDFs/Slides:
  - [Aula 1.0 - Apresentação](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=386342)
  - [Aula 2.0 - POO](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=391983)
  - [Aula 3.0 - Herança](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=391984)
  - [Aula 3.1- Herança/UML](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=391985)
  - [Aula 3.2 - JAVA](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=393705)
  - [Aula 3.3 - Python](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=394855)
  - [Aula 4.0 - Composição](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=394856)
  - [Aula 5.0 - Polimorfismo](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=397733)
  - [Aula 6.0 - Classes Abstratas](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=398220)
  - [Aula 7.0 - Interfaces](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=398683)
  - [Aula 8.0 - Tratamento Exceções](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=398682)

- Vídeos:
  - N/D.

- Complementares:
  - N/D.

<h2 style="color: black; margin-bottom: 20px;" align="center"><span style='font-weight: bold;'>Atividades</span></h2>

- Questionários:
  - [Primeiro Questionário](https://presencial.muz.ifsuldeminas.edu.br/mod/quiz/view.php?id=394750)
  - [Questionário Final](https://presencial.muz.ifsuldeminas.edu.br/mod/quiz/view.php?id=398661)

- Lista de Exercícios:
  - [Códigos em Sala 3 - Herança](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=398221)  -  [Link para envio](https://presencial.muz.ifsuldeminas.edu.br/mod/assign/view.php?id=395408)
  - [Códigos em Sala 4 - Polimorfismo](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=398511)  -  [Link para envio](https://presencial.muz.ifsuldeminas.edu.br/mod/assign/view.php?id=395408)
  - [Códigos em Sala 5 - Exceções](https://presencial.muz.ifsuldeminas.edu.br/mod/resource/view.php?id=398684)  -  [Link para envio](https://presencial.muz.ifsuldeminas.edu.br/mod/assign/view.php?id=395408)

<h2 style="color: black;  margin-bottom: 20px;" align="center"><span style='font-weight: bold;'>Colab</span></h2>

Seção voltada para a colaboração entre os alunos.

Links abertos com resumos, anotações e materiais de revisão.
