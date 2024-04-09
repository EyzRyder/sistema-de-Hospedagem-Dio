
# Sistema de Hospedagem
Este projeto foi desenvolvido como parte do desafio proposto no módulo "Explorando a Linguagem C#" da trilha .NET da [DIO](http://www.dio.me/) (Digital Innovation One).

## Descrição
O sistema de hospedagem permite realizar reservas em um hotel, utilizando as classes Pessoa, Suíte e Reserva para gerenciar o relacionamento entre os hóspedes e as suítes. O programa calcula corretamente os valores dos métodos da classe Reserva, incluindo a quantidade de hóspedes e o valor da diária. Além disso, concede um desconto de 10% para reservas com duração igual ou superior a 10 dias.

## Conhecimento Utilizado
- Lógica de Programação e Programação Orientada a Objetos (POO)
- Conhecimentos Básicos em .NET, C#, Git e GitHub

## Regras e Validações
- Não é possível realizar uma reserva em uma suíte com capacidade menor do que a quantidade de hóspedes. Caso contrário, uma exceção será lançada.
- O método ObterQuantidadeHospedes da classe Reserva retorna a quantidade total de hóspedes.
- O método CalcularValorDiaria da classe Reserva retorna o valor da diária, calculado como dias reservados multiplicado pelo valor da diária, com um desconto de 10% para reservas iguais ou superiores a 10 dias.

## Implementação
O código-fonte deste projeto está disponível na pasta sysHospedagem. Ele inclui as classes Pessoa, Suíte e Reserva, juntamente com a implementação das regras e funcionalidades descritas.
