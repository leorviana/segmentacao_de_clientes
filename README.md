# Segmentação de clientes
Projeto de data science(clusterização) - Segmentando clientes para um hipermercado.

**Problema de négocio:** A empresa de hipermercados "Santa Teresa", que é uma empresa que vende dos mais diversos itens, além de um supermercado normal você pode comprar até ouro, deseja segmentar seus clientes e entender seus hábitos, para dessa forma aumentar as vendas, conquistar novos clientes e não perder os atuais. Foi disponibilizado pela empresa um dataset sobre 2240 clientes e algumas de suas características, cabe a nós cientistas de dados, analisar, entender e aplicar ferramentas sobre esses dados afim de gerar informações úteis e agregar ao negócio.

![alt text](https://media.jornaljurid.com.br/cache/77/49/7749a1e3bef366aa856eb9a862862743.jpg)

## Resumo  e conclusões

### Informações sobre os clientes em geral:
    
- Média de ganho: Entre 30.600 e 73.400 (Em dólares por ano).
- Ultima compra: Entre 20 e 78 dias.
- Idade média: Entre 33 e 57 anos.
- Média de filhos: 1.
- Média de gasto: \$600.00
- Média de tempo como cliente: Entre 280 e 744 dias.
- A maioria massante é de pessoas graduadas.
- Mais da metade dos clientes esta em um relacionamento.
- A maior parte dos clientes tem entre 30 e 60 anos.

### Hábitos de consumo dos grupos criados

**Grupo 1 - Poder aquisitivo**

Habitos de consumo dos grupos por poder aquisitivo:
    
    - Baixo:
        Vinho: 33%
        Frutas: 6%
        Carne: 27%
        Frutos do mar: 9%
        Doces: 6%
        Ouro: 19%
        
        Compras pela internet: 37%
        Compras pelo catálogo: 9%
        Compras na loja: 53%
        Compras com desconto: 37%
        
     - Médio:
        Vinho: 58%
        Frutas: 4%
        Carne: 20%
        Frutos do mar: 5%
        Doces: 4%
        Ouro: 10%
        
        Compras pela internet: 36%
        Compras pelo catálogo: 17%
        Compras na loja: 47%
        Compras com desconto: 25%
        
     - Alto:
        Vinho: 49%
        Frutas: 4%
        Carne: 30%
        Frutos do mar: 6%
        Doces: 5%
        Ouro: 6%
        
        Compras pela internet: 29%
        Compras pelo catálogo: 28%
        Compras na loja: 44%
        Compras com desconto: 9%
        
**Grupo 2 - Tempo como cliente**

Habitos de consumo dos grupos por tempo como cliente:
    
    - Clientes novos:
        Vinho: 49%
        Frutas: 5%
        Carne: 29%
        Frutos do mar: 6%
        Doces: 5%
        Ouro: 7%
        
        Compras pela internet: 31%
        Compras pelo catálogo: 21%
        Compras na loja: 48%
        Compras com desconto: 17%
        
     - Clientes frequentes:
        Vinho: 50%
        Frutas: 4%
        Carne: 28%
        Frutos do mar: 6%
        Doces: 5%
        Ouro: 8%
        
        Compras pela internet: 33%
        Compras pelo catálogo: 21%
        Compras na loja: 46%
        Compras com desconto: 18%
        
     - Clientes experientes:
        Vinho: 51%
        Frutas: 4%
        Carne: 26%
        Frutos do mar: 6%
        Doces: 4%
        Ouro: 7%
        
        Compras pela internet: 34%
        Compras pelo catálogo: 21%
        Compras na loja: 45%
        Compras com desconto: 20%
        
**Grupo 3 - Total gasto**

Habitos de consumo dos grupos por gasto:
    
    - Clientes que gastam pouco:
        Vinho: 35%
        Frutas: 6%
        Carne: 24%
        Frutos do mar: 9%
        Doces: 7%
        Ouro: 19%
        
        Compras pela internet: 34%
        Compras pelo catálogo: 6%
        Compras na loja: 60%
        Compras com desconto: 38%
        
     - Clientes que gastam um valor médio:
        Vinho: 54%
        Frutas: 4%
        Carne: 21%
        Frutos do mar: 6%
        Doces: 4%
        Ouro: 11%
        
        Compras pela internet: 39%	
        Compras pelo catálogo: 16%
        Compras na loja: 46%
        Compras com desconto: 25%
        
     - Clientes que gastam muito:
        Vinho: 50%
        Frutas: 4%
        Carne: 30%
        Frutos do mar: 6%
        Doces: 4%
        Ouro: 6%
        
        Compras pela internet: 28%
        Compras pelo catálogo: 28%
        Compras na loja: 43%
        Compras com desconto: 10%
        
### Clusters

Pelo observado podemos separar os nossos clusters da seguinte maneira:

**Precisam de atenção:** Base de clientes simples mas que não compram há muito tempo, clientes que precisam de atenção!

- Tempo como cliente: A um tempo médio.
- Gasto: Baixo.
- Ultima compra: Há bastante tempo.
- Poder aquisitivo: Baixo.

**Clientes mais simples:**  Clientes mais simples e fieis, clientes base que precisam apenas serem mantidos!
    
- Tempo como cliente: A um tempo médio.
- Gasto: Baixo.
- Ultima compra: Recentemente.
- Poder aquisitivo: Baixo.

**Melhores Clientes:** Melhores clientes, mas não compram a um tempo, clientes importantes que precisam ser mantidos e tragos de volta!

- Tempo como cliente: A bastante tempo.
- Gasto: Alto.
- Ultima compra: Há bastante tempo.
- Poder aquisitivo: Alto.

**Clientes com potêncial:** Potenciais futuros grandes clientes, possuem as mesmas caracteristicas dos melhores clientes, mas são recentes.

- Tempo como cliente: Recente.
- Gasto: Alto.
- Ultima compra: Recente.
- Poder aquisitivo: Alto.

**Alguns insights:**

Com as informações acima a respeito dos clusters, podemos gerar alguns insights para atigir algumas metas:

    - Para trazer os clientes do grupo "need_atention" de volta a compras, podemos focar em promoções por compras na loja ou pela internet, visto que este grupo tende a aceitar mais promoções, e compras pela loja e internet são os meios de compras mais comuns nesse grupo.
    
    - Podemos usar da mesma idéia para manter ou aumentar as vendas do grupo de "basic_clients", visto que as caracteristicas do grupo em relação ao local da venda e também aos produtos mais comprados são muito semelhantes.
    
    - Visto que os cliente em potencial e os melhores clientes compram bastante por catálogo, podemos utilizar desse meio para conquistar de vez os clientes em potencial além de aumentar as vendas dos clientes mais fiéis.
    
    - Vemos que por algum motivo, quem compra frutas tende a comprar carnes também, desta maneira podemos pensar em um jeito de fazer uma compra alavancada.
    
    
## Conclusão

Após toda nossa análise a respeitos dos clientes em geral, e as subdivisões criadas, extraímos algumas informações muito úteis a respeito dos nossos clientes e seus hábitos, podendo assim junto com o time de negócios ou de markenting da empresa buscar soluções e melhorias, assim como as sugeridas.

Lembrando que a análise e divisão dos dados é tão profunda quanto podemos querer, desta forma cabe ao time em conjunto decidir a melhor maneira de dividir e analisar os dados pensando no problema em questão ou em questão as melhorias buscadas.
