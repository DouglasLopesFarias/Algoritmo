Trabalho 2 Bim:
utilize um vetor de 100 posições de uma struc para fazer um cadastro qualquer, escolha se vai ser cliente, fornecedor, produto, aluno etc. O cadastro deve conter:
um menu para realizar o cadastro, este meno deve estar rodando dentro de um lação de repetição ou while ou do while:

"01 - Cadastrar"
"02 - Consultar"
"03 - Listar"
"04 - Remover"
"05 - Sair do Sistema"
"Digite uma opção"

Ao escolher a opção cadastrar pela primeira vez, o sistema deve pedir os dados do cadastro e armazenar os dados na primeira posição do vetor, ao terminar volta para o menu. Ao chamar a função novamente o cadastro deve preencher os dados na segunda posição do vetor e assim sucessivamente, crie uma variável para gerenciar a posição do próximo a ser cadastrado.

Ao escolher a opção consultar o sistema deve percorrer o vetor e imprimir os dados do registro encontrado, caso nao encontrar imprime a mensagem cadastro nao localizado:

Ao escolher a opção listar o sistema deve imprimir os dados de todos registros cadastrados

Ao escolher a opção remover, o sistema deve procurar o registro no vetor, caso encontre copie os dados do ultimo cadastrado na posição do registro a ser excluido, depois decrementa a variável que gerencia a posição do próximo a ser cadastrado para ignorar este registro.

Ao escolher a opção sair do sistema o sistema deve parar a execução.
