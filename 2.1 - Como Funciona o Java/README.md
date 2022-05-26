## Código Fonte, JavaC, Bytecode e JVM

- “Olá, mundo!” em Java.
    
    ```java
    public static void main (String[] args) {
       System.out.println("Olá, mundo!");
    }
    ```
    
- JavaC (Java Compiler): compilador de arquivos .java.
- Bytecode: código binário gerado após a compilação do código fonte.
- JVM (Java Virtual Machine): responsável por gerar o código executável através do Bytecode.

## WORA

- Wora (Write Once Run Anywhere)
    - Estrutura englobando o desenvolvimento do código fonte, a compilação do .java através do JVM gerando um Bytecode e a criação de um código executável para qualquer dispositivo.
        
        ![https://media.discordapp.net/attachments/964170366694076490/979484964305399849/unknown.png?width=1145&height=644](https://media.discordapp.net/attachments/964170366694076490/979484964305399849/unknown.png?width=1145&height=644)
        

## IDE, JDK e JRE

- IDE: ambiente de desenvolvimento.
- JDK (Java Development Kit)
    1. JavaLang (linguagem Java)
    2. JavaTools (conjunto de ferramentas)
        1. JavaC: compilador Java. 
        2. Debugger: permite a verificação em tempo real de como o programa está sendo executado. 
        3. APIs: bibliotecas/grupo de bibliotecas e outros.  
    3. JRE e seus componentes
- JRE (Java Runtime Enviroment) e alguns de seus componentes
    1. JVM (Java Virtual Machine)
        1. Loader: parte interna da JVM que vai carregar o Bytecode na memória da JVM. 
        2. Verificador: vai verificar se o código executável que foi aprovado pelo loader pode de fato ser executado sem problemas. 
        3. Interpretador: aquele que vai pegar o código em Bytecode e transformá-lo em um código nativa da maquina em questão.
        4. Gerenciador de memória: responsável por tratar como os códigos e variáveis vão ser gerenciadas na memória da JVM.  
        5. Compilador JIT (Just in Time): é um compilador que vai analisar as partes mais importantes do programa para que elas sejam compiladas definitivamente para ganho de performance muito grande.    
    2. Bibliotecas (APIs que podem ser usadas dentro do programa para expandir suas funcionalidades).