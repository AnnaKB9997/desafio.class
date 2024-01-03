# Desafio DIO 3 - Escrevendo as classes de um jogo

* O que deve ser utilizado *

- Variáveis
- Operadores + - 
- Laços de repetição switch
- Estuturas de decisão for/while
- Funções
- Classes e Objetos

## Objetivo:

Crie uma classe genérica que represente um heroi de uma aventura e que possua as seguintes propriedades:

- nome
- idade
- tipo (ex.: guerreiro, mago, monge, ninja)

além disso, deve ter um método chamado atacar que deve atender os seguintes requisitos:

- exibir a mensagem: ("o {tipo} atacou usando {ataque}")
- aonde o {tipo} deve ser concatenado o tipo que está a propriedade da classe
- e no {ataque} deve seguir uma descrição diferente conforme o tipo, seguindo a tabela abaixo:

se mago -> no ataque exibir (usou magia)
se guerreiro -> no ataque exibir (usou espada)
se monge -> no ataque exibir (usou artes marciais)
se ninja -> no ataque exibir (usou shuriken)

## Saída

Ao final deve se exibir uma mensagem:

- "o {tipo} atacou usando {ataque}""
ex: mago atacou usando magia
guerreiro atacou usando espada