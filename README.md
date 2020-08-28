# java-exeption-personal
### Pacote model
Neste projeto foi usado o pacote model e seus subpacotes(entities, enums, exception, services).

### Problema
Fazer um programa para ler os dados de uma reserva de hotel(número do quarto, data de entarada e data de saída) e mostrar os dados de reserva, inclusive sua duração em dias. Em seguida, ler novas datas de entrada e saída, atualizar a reserva, e mostrar novamente a reserva com os dados atualizados. O programa não deve aceitar dados inválidos para a reserva, conforme as seguintes regras:  
* Alterações de reserva só podem ocorrer para datas futuras.  
* A data de saída deve ser maior que a data de entrada.  
### Soluções
* Solução 1(muito ruim): lógica de validação no programa principal.  
* Solução 2(ruim): método retornando string.  
* Solução 3(boa): tratamento de exceções.
