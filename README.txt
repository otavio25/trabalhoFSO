Trabalho Prático (01/2023)
Fundamentos de Sistemas Operacionais - Professora: Alba Melo

Integrantes do grupo:

Lucas Jr. Ribas - 160052289
Fernanda ...
Otávio Souza de Oliveira - 150143401
Bruno Helder Rodrigues Guedes - 150120338

Instruções de execução:

	- gcc escalonador.c -o escalonador
	- ./escalonador seu_diretório/seu_arquivo_de_processos.txt '-normal ou -roubo'
	
	Caso queira, no diretório deste trabalho tem uma pasta chamada testes, onde há arquivos para testes.

//////////////////////////////////////////////////////////////////////////////////////////////
	
Observações:

É importante que o arquivo de testes contenha apenas o nome do processo por linha para execução, ou seja, exatamente os nomes 'lento', 'medio', ou 'rapido', pois os compilados na pasta 'processos' possuem esses nomes. Caso queira ajustar para outros nomes, renomeie os executaveis da pasta 'processos'.

Pode haver espaços em branco ou quebras de linha(desde que tenha no máximo 1 nome por linha), mas deve se manter os nomes dos processos, sem acentos, e etc.

Os nomes dos processos não são sensiveis ao caso. Ex: Pode ter 'LenTo', 'MediO', 'LENTO', 'rAPIDo', que a execução ocorrerá normalmente.

Caso o arquivo de processos não cumpra os requisitos, o eslonador não irá executar o processo com erro de nome, irá marca-lo como '-1: Não executado' e depois prosseguir com a execução dos próximos.

>>> Os tempos de execução podem variar bastante de Computador(CPU) pra Computador(CPU).

//////////////////////////////////////////////////////////////////////////////////////////////
