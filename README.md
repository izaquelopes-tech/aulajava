# aulajava
Assuntos abordados durante as aulas de java:
- fundamentos da linguagem java;
- programação orientada a objetos(POO);
- estrutura de dados;
- Collections Freamworks;
- tratamento de excessões;
- JDBC e banco de dados
- swing e JavaFX;
- Threads e concorrência;
- APIs REST com Spring Boot;
- JPA/Hibernate;
- arquitetura de Software;
- clean code e boas praticas;
- testes unitários com JUnit;
- Padrões de projetos (Design Patterns).

- O que e java?
- Java e uma linguagem de programação criada para funcionar em diferentes sistemas operacionais.
  A ideia principal do Java é: " Escreva uma vez e execute em qualquer lugar".
  preparando o ambiente: Para podermos rodar codigos em Java, são necessarios algumas instlações, como: Oracle Java e Visual Studio code.
  com o ambiente preparado, os próximos passos são instalar as extensões necessariás e testar se o java está funcionando.
  A extensão é: Extension Pack for java. Essa extensão instala junto o suporte java, o debugger e o autocomplete.
  para testar se o Java está funcionando precisamos: abrir o terminal do windows (tecla windows + R -> digitar CMD na caixa que abrir) com o terminal aberto digite:
  Java --version. Se aparecer o número da versão (20, 21, 25 etc) o java está funcionando corretamente.
  criando um programa em java: abrir o VSCode, abrir uma pasta (AulaJava, por exemplo), criar um novo arquivo com extensão. java (Main.java, por exemplo).
  ao criar o arquivo, se a extensão estiver instalada corretamente, aparecerá o codigo: public class Main {

  }
  na sequencia precisamos inserir a parte do codigo onde o Java de Fato funciona: public Class Main {
  public static void main (String[] args) {

  }
  Por fim, para finalizar esse programa, precisamos colocar o codigo que faz mostrar uma mensagem na tela: public class main {
  public static void main(String[]args) {}
  system.out.println("Olá, mundo")
  }
  }
  para execuatr esse programa há duas alternativas:
  1- aparecera um botão Run abixo de public class Main, basta apertar e o resultado aparece no terminal do VScode.
  2- Abrir o prompt de comando do windos (cmd)-> navegar até a pasta omd o projeto está salvo  (cd nome-da-pasta)-> digitar primeiro: javacMain.java (se o projeto tiver outro nome e preciso
  digitar esse outro nome)-> pressione enter -> na proximá linha digite java main (ou o nome do programa se for diferente)

  variavéis:
  variaveis guardam informçoes na memoria
  exemplo:
  string nome = "izaque";
  int idade = 16;
  double altura = 1,83
  boolean aluno = true;

  System.out.println(nome);
  System.out.println(idade);
  System.out.println(altura);
  System.out.println(aluno);
