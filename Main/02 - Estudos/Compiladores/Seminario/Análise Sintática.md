tema: Verifica se a árvore de sintaxe está correta

### O que é analise sintática?
([[Parsing]]) É a segunda etapa dos processos de um compilador, onde se analisa uma sequencia que foi dada entrada   

### Qual seu papel?
O papel da analise sintática no pipeline é ser a fase que da estrutura ao código. Cada fase depende dela de um jeito diferente

Depois da primeira fase ([[Analise Léxica]]) quebrar o texto em token, a analise sintática pega essa sequencia de tokens e verifica se a ordem deles respeita a gramatica da linguagem

A analise sintática entrega para o resto do computador uma [[AST]](arvore sintática abstrata), sem ela as outras fases não conseguem trabalhar.

Analogia: O léxico é como reconhecer  palavras individuais em uma frase. A sintaxe é como verificar se a frase tem sujeito, verbo e objeto no lugar certo

O gato comeu a lua" é sintaticamente correta. "Comeu o gato lua" não é. A semântica é a próxima pergunta: "mas isso faz sentido de verdade?".