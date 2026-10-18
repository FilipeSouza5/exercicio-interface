# Exercício de interface - programação orientada a objetos

## Discente: Filipe Souza Da Cruz Santos


1. **SuperClasse abstrata Automovel:**

Essa classe possui a variável e o construtor que serão herdadas pelas subclasses.

![](1%20int.png)

2. **Interface:**

Esse é o método/contrato que será implementada pelas subclasses, esse método irá verificar 
se o veículo é estacionável ou não.

![](4%20int.png)

3. **SubClasses Carro e Caminhao:**

Essas são as classes filhas, onde esta implementada a interface de forma diferente para cada uma das subclasses. Se o numero de registro tiver 4 dígitos, refere-se a um caminhão, se tiver 3 dígitos, refere-se a um carro.

![Subclasse Caminhao](2%20int.png)

![Subclasse Carro](3%20int.png)

4. **Programa:**

E por fim, a classe Programa. Ela ira instanciar os objetos, armazenando em um array do tipo Estacionavel e será acessado cada objeto por meio de um loop for, verificando se eles são estacionáveis naquela vaga ou não, além de contar os objetos estacionáveis. 

![](int%205.png) 

5. **Resultado no terminal**

![](int%206.png)
   
Este é um exemplo de polimorfismo porque é possível armazenar diferentes objetos em um array do tipo Estacionavel, além disso, no loop for, é executado a implementação do método correspondente à classe real do objeto.

A vantagem principal é permitir que seja possível trabalhar com diferentes tipos de objetos usando uma interface comum, sem precisar escrever um código completamente separado para cada classe.
