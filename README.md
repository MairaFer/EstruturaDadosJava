*******ESTRUTURA DO PROJETO*******

    O projeto consiste em um pacote de entrada, que integra os arquivos de entrada de dados,
como o arquivo exec.txt, que contém os comandos a serem executados pelas estruturas de dados.
    Em seguida, temos um pacote para cada estrutura de dados solicitada na atividade:

1. ListaEncadeadaDupla
2. PilhaDinamica
3. FilaDinamica
4. ArvoreBinaria

    Cada um dos pacotes contem uma classe de mesmo nome onde estão representados os métodos relacionados as operações da estrutura
e uma classe Main, onde será de fato executado as operações com base nos comandos lidos do arquivo exec.txt.

*****ARQUIVO DE ENTRADA("exec.txt")*****

    O arquivo exec.txt contém os comandos a serem executados na Estrutura de Dados. Cada linha representa uma operação
e segue o seguinte formato:

COMANDO(obrigatório);ARGUMENTO1(opcional);ARGUMENTO2(opcional)

COMANDO: Pode ser "INSERIR", "REMOVER", "IMPRIMIR" ou "BUSCAR".
ARGUMENTO1: Depende do comando. Pode ser uma chave (número inteiro) ou um valor.
ARGUMENTO2: Depende do comando. Pode ser uma chave (número inteiro) ou um valor.

Obs: Nem todos os comandos requerem argumentos e o número de argumentos depende da estrutura que está sendo usada
     Para saber mais, leia a seção “Manual de Instruções” de cada estrutura abaixo:

*******MANUAL DE INSTRUÇÃO******
    Este manual fornece instruções básicas para usar os comandos relacionados a cada estrutura de dados. Para informações mais detalhadas
sobre o funcionamento interno do código, consulte o código-fonte e os comentários relevantes.

-LISTA ENCADEADA DUPLA

    Comandos disponíveis:
INSERIR: Insere um novo nó na lista com a chave e o valor fornecidos.
ex: INSERIR;Maçã (1 argumento necessário)

REMOVER: Remove o nó com o valor fornecido da lista, se existir.
ex: REMOVER;Bola  (1 argumento necessário)

IMPRIMIR: Imprime os nós da lista.
ex: IMPRIMIR (0 argumentos necessário)

BUSCAR: Procura um nó com o valor fornecido na lista.
ex: BUSCAR;Casa (1 argumento necessário)

-PILHA DINÂMICA

    Comandos disponíveis:
INSERIR: Insere um novo elemento altomaticamente no topo na pilha com o valor fornecido.
ex: INSERIR;Casa (1 argumento necessário)

REMOVER: Remove o elemento do topo da pilha, se existir.
ex: REMOVER (0 argumentos necessário)

IMPRIMIR: Imprime os elementos da pilha.
ex: IMPRIMIR (0 argumentos necessário)

BUSCAR: Procura pelo valor fornecido na pilha e exibe uma mensagem indicando se o valor foi encontrado ou não.
ex: BUSCAR;Bola (1 argumento necessário)

-FILA DINAMICA

    Comandos disponíveis:
INSERIR: Insere um novo elemento na fila com o valor fornecido.
ex: INSERIR;Casa (1 argumento necessário)

REMOVER: Remove o elemento da frente da fila, se existir.
ex: REMOVER (0 argumentos necessário)

IMPRIMIR: Imprime os elementos da fila.
ex: IMPRIMIR (0 argumentos necessário)

BUSCAR: Procura pelo valor fornecido na fila e exibe uma mensagem indicando se o valor foi encontrado ou não.
ex: BUSCAR;Bola (1 argumento necessário)

-ARVORE BINARIA

    Comandos disponíveis:
INSERIR: Insere um novo nó na árvore com a chave e o valor fornecidos.
ex: INSERIR;10;Maçã (2 argumentos necessários)

REMOVER: Remove o nó com a chave fornecida da árvore, se existir.
ex: REMOVER;5 (1 argumento necessário)

IMPRIMIR: Imprime os nós da árvore em ordem.
ex: IMPRIMIR (0 argumentos necessário)

BUSCAR: Procura um nó com a chave fornecida na árvore e exibe o valor correspondente, se encontrado.
ex: BUSCAR;10 (0 argumentos necessário)

**********OBSERVAÇÕES**********
1. Não é necessario escrever o nome da estrutura de dados utilizada, basta rodar a Main da estrutura escolhida.
2. Certifique-se de modificar o arquivo exec.txt conforme solicitado por cada estrutura (leia o manual de instruções).
3. Se ocorrerem erros durante a execução, verifique as mensagens de erro fornecidas para identificar e corrigir o problema.
4. Certifique-se de ter o JDK 21 (Java Development Kit) instalado em seu sistema.
5. Não esqueça do ';' separando os item no arquivo exec.txt.
