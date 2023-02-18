# COMO USAR O PROGRAMA: 

USANDO GCC

<B>gcc main.c -o main -lm</B>
Para rodar --freq e saber quais as palavras que aparecem em maior quantidade no arquivo.

<B>./main --freq N ARQUIVO</B>
Para rodar --freq-word e saber o número total de ocorrências da palavra no arquivo.

<B>./main --freq-word PALAVRA ARQUIVO</B>
Para rodar --search e listar os arquivos mais expressivo para um dado termo

<B>./main --search TERMO ARQUIVO [ARQUIVO ...]</B>


# OPÇÕES

--freq N ARQUIVO
Exibe o número de ocorrência das N palavras que mais aparecem em ARQUIVO, em ordem decrescente de ocorrência.
--freq-word PALAVRA ARQUIVO
Exibe o número de ocorrências de PALAVRA em ARQUIVO.
--search TERMO ARQUIVO [ARQUIVO ...]
Exibe uma listagem dos ARQUIVOS mais relevantes encontrados pela busca por TERMO. A listagem é apresentada em ordem descrescente de relevância. TERMO pode conter mais de uma palavra. Neste caso, deve ser indicado entre àspas.


# TRABALHO PRÁTICO INDEXER

Algoritmo criado utilizando tabelas hash, as vantagens de usar tabelas hash incluem:
Tempo de acesso constante: O tempo de acesso para recuperar um elemento de uma tabela hash é geralmente constante, independentemente do tamanho da tabela.

Busca rápida: As tabelas hash permitem buscas rápidas de elementos, pois o índice da posição do elemento na tabela é calculado usando a função hash.

Fácil inserção e remoção: Inserir e remover elementos em uma tabela hash é geralmente simples e rápido.

Uso eficiente de memória: As tabelas hash são uma forma eficiente de armazenar dados, pois não requerem espaço adicional para armazenar informações de comparação, como em estruturas de dados como árvores.

