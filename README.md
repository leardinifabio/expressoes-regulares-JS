# Expressoes-regulares-JS
Estudo da Alura sobre expressões regulares.

# Quantifier
- {n} - exatamente n vezes.
- {n, } - no mínimo n vezes.
- {n,m} - no mínimo n, no máximo m vezes.
- ? - zero ou uma vez.
- \+ - uma ou mais vezes.
- \* - zero ou mais vezes.

# Classes de char - [ ]
- [A-Z] - letras de A até Z.
- [123] - 1, 2 ou 3.
- \d - todos os dígitos [0-9]
- \s - whitespace [\t\r\n\f]
- \w - wordchar [A-Za-z0-9_]

# Âncoras
Servem para marcar uma posição específica no alvo.

Âncoras mais comuns: 
- ^ servem para marcar uma posição no início de uma string (nada deve vir antes).
- $ servem para marcar uma posição no final de uma string (nada deve vir depois).
- \b é uma âncora que seleciona um word boundary, isso é o início ou fim da palavra.
- \B (non-word-boundary) 
