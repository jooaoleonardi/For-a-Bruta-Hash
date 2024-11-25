# Implementação de Busca por Força Bruta de uma String a partir de uma Hash SHA-256
## Descrição do Codigo 
### Implementar uma busca por força bruta para encontrar uma string de exatamente 7 caracteres, composta por letras minúsculas de a a z, que gere uma hash SHA-256 específica. O problema consiste em iterar sobre diferentes combinações possíveis de strings desse comprimento, para descobrir qual combinação produz a hash alvo fornecida.
## Problema Base
### Considere o código de exemplo abaixo, que gera a hash SHA-256 de uma string fixa:
### 
string_busca_facil = "aaaaaaa"
hash_busca_facil = "e46240714b5db3a23eee60479a623efba4d633d27fe4f03c904b9e219a7fbe60"

No exemplo acima, a string "aaaaaaa" gera uma hash específica. Seu objetivo é estender esse código para testar todas as combinações de 7 caracteres, começando de "aaaaaaa" até "zzzzzzz", e encontrar a string que produza a hash alvo definida a seguir:

## Hash Target (Hash Alvo)
### A hash alvo que você deve encontrar é:

70502ff6bb85356055ea52ff0a657afd09a52324a33734ccfb7bdedf05634925
