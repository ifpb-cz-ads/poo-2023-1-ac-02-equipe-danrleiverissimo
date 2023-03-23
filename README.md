# 1 Explique qual a função da Máquina Virtual Java (JVM).
A JVM é uma máquina imaginária que emula a execução de uma aplicação em uma máquina real. Ela é fundamental para o desenvolvimento de aplicações Java, pois, ela permite a portabilidade do código Java, garantindo que as aplicações sejam executadas em diferentes sistemas operacionais sem a necessidade de adaptações específicas para cada plataforma. Para cada tipo de sistema operacional, como Windows, Linux e Mac, existe uma JVM correspondente. Dessa forma, podemos desenvolver aplicações em Java sem nos preocuparmos com onde elas serão executadas, pois, uma vez instalada a JVM correspondente, a aplicação será executada independentemente do sistema operacional.
# 2 Qual a diferença entre JRE e JDK?
JRE é o ambiente de execução Java. É o mínimo necessário para execução de um programa java. Contem uma JVM, o núcleo da Api java e bibliotecas básicas. Está inclusa no JDK.
JDK é o kit de desenvolvimento Java. Contém o compilador javac, um depurador e o JRE para execução do programa.

# 4 Compile o programa desenvolvido no exercício anterior. A seguir apague o arquivo .class gerado e tente executar o programa. O que aconteceu?
Depois que apaguei o arquivo .class e tentei executar de novo o programa deu um erro com a seguinte mensagem: "Error: Could not find or load main class MeuPrimeiroProgramaJava."

# 5 Mude o nome do método “main” para “start”, compile e execute. O que aconteceu?
Depois que eu mudei o nome do método o programa compilou, mas quando executei apareceu o seguinte erro: "Error: Main method not found in class MeuprimeiroProgramaJava, please define the main method as: public static void main(String[] args).

# 7 Experimente escrever todo o programa anterior em maiúsculo, compile e execute. O que aconteceu?
Com todas as palavras escritas em maiúsculo, o compilador não reconhece as palavras-chave, e não é possível gerar o programa executável.

# 8 Experimente salvar o arquivo com um nome diferente do nome da classe,compile e execute. O que aconteceu?
A compilação ocorre sem problemas, desde que a classe não seja explicitamente public. O arquivo .class gerado continua tendo o nome da classe, e não do arquivo fonte .java.
