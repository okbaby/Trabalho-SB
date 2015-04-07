IDE
-----------------------------------------------------
CodeBlocks ou DeV ?


------------------------------------------------------
Critérios de correção do leitor/exibidor e da JVM – Compilação com o GCC com opções –std=c99 e execução para análise da sua corretude. Serão elaborados pequenos programas Java 7 que serão compilados com o Javac. 
ATRIBUIÇÃO DA NOTA
- Leitor de ponto class e exibidor de bytecode (100)
	Exibição das estruturas internas montadas após a leitura de um arquivo ponto class (70%) e os mnemônicos em assembly associado aos bytecodes Java 7 (30). 
- Corretude da máquina virtual (100)
	- Instruções: instruções com categorias 1 e 2, arrays (uni e multidimensionais), strings, métodos estáticos e dinâmicos e atributos de classe ou de instância, herança, polimorfismo, reescrita, objetos, simulação de impressão (80%). Não incluem debug, chamadas às API do Java ou S.O. checagem dinâmica de tipos ou coletor de lixo. 
	- Documentação gráfica do fluxo de execução das instruções bytecode  (20%)
- Defesa individual (100)
	Cada membro do grupo será argüido e avaliado em separado sobre a teoria da JVM, formato ponto class e a implementação propriamente dita. A resposta deve indicar funções e estruturas de dados no código elaborado.
- Documentação (100) 
	Páginas web descrevendo cada função implementada na JVM abrangendo um diagrama de ativação (diagrama de comunicação entre os módulos) e a descrição das principais estruturas de dados utilizadas. Para CADA FUNÇÃO deverá ser elaborada um frame contendo: nome da função, objetivo, parâmetros de entrada, parâmetros de saída, descrição do algoritmo que implementa, e links para a função chamadora e para as funções chamadas. 
- Atribuição de nota para a JVM:   ?   0,4*corretude + 0,4*defesa individual+ 0,2*documentação
