# Escrevendo as classes de um jogo

**O que deve ser utilizado**

- Variáveis;
- Operadores;
- Laços de repetição;
- Estruturas de decisões;
- Funções;
- Classes e Objetos.

## Objetivo

Crie uma classe genérica que represente um herói de uma aventura e que possua as seguintes propriedades:

- Nome;
- Idade;
- Tipo (ex: guerreiro, mago, monge, ninja).

Além disso, deve ter um método chamado atacar, que deve atender aos seguintes requisitos:

- Exibir a mensagem: "o {tipo} atacou usando {ataque}";
- Aonde o {tipo} deve ser concatenando o tipo que está na propriedade da classe;
- E, no {ataque}, deve seguir uma descrição diferente conforme o tipo, seguindo a tabela abaixo:

se mago -> no ataque, exibir (usou magia);
se guerreiro -> no ataque, exibir (usou espada);
se monge -> no ataque, exibir (usou artes marciais);
se ninja -> no ataque, exibir (usou shuriken).

## Saída

Ao final, deve exibir uma mensagem:

- "o {tipo} atacou usando {ataque}"
  <br>
  ex: mago atacou usando magia
      <br>
      guerreiro atacou usando espada