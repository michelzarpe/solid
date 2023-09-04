# Solid


### Coesão
Classe deve ter uma única responsabilidade. Isso é o que tem a ver com a coesão, você ter classes que fazem apenas uma única coisa. "Classes não coesas tendem a crescer indefinidamente, o que as tornam difíceis de manter".  

### Encapsulamento  
O encapsulamento nada mais é do que você proteger, blindar uma classe contra influências externas, contra manipulações externas que podem prejudicar a consistência das informações.  

### Acoplamento
A ideia de você acoplar é quando você tem dois componentes que estão interligados entre si causando uma dependência entre eles. Então, por exemplo, quando eu tenho uma classe que faz a utilização de uma outra classe. Uma classe A que chama uma classe B. 




# Single responsability principle  
1. Uma classe (ou módulo, função, etc) deve ter apenas um motivo para mudar  
# Open closed principle    
1. Estar aberto para extender e fechado para modificação. O extender é ampliar com novas regras de negocio sem quebrar/modificar o que ja está feito  
# Liskov Substitution pinciple  
1. Se parece com pato, se faz 'quack' igual um pato, mas precisa de baterias, então não é um pato, você está usando uma abstração errada.
2. Ou seja classes não podem herdar comportamentos nos quais não faz sentido.
3. troque por composição
# Dependency inversion principle  
1. Abstração não deve depender de implementação
2. Implementação deve depender de abstração
# Interface Segregation Principle  
1. Esse princípio diz que às vezes nós vamos ser obrigados a implementar uma interface que não faz sentido para nós
2. Uma classe não deveria ser forçada a depender de métodos que não utilizará
3. Segregar é a melhor solução, utilize de herança entre interfaces para resolver o item 2.
