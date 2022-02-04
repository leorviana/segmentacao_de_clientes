# All In - Segmentação de Clientes

A empresa All In é uma empresa de franquias Delicatesses. Delicatesse é uma loja que vende comidas finas e iguarias. Especializada em comidas exóticas, raras e de difícil preparo.
Os principais produtos da All In são vinhos, carnes, certos peixes, doces e guloseimas e o diferencial, você pode comprar certas peças de ouro.
<p align="center">
  <img src="https://portaldoqueijo.com.br/site/wp-content/uploads/2018/04/combina%C3%A7%C3%A3o-perfeita-queijos-e-vinhos.jpg">
</p>

# Problema de Negócio

Em pouco mais de 2 anos a empresa adquiriu uma certa base de clientes, e por esta ser uma base de clientes dificil de se achar, seria extremamente vantajoso para a empresa conhecer melhor seus clientes afim de rete-los.

A franquia All In nos contratou para auxiliarmos a equipe de marketing em sua missão de elevar a retenção de clientes.

Uma maneira eficiente e comprovada de melhorar a retenção de clientes é agrupa-los, pois com os clientes agrupados podemos entender melhor seu comportamento, suas necessidades e o principal, melhoramos significativamente nossa comunição com eles através de um contato mais focado.

# Solução Proposta

Existem diversos métodos para se agrupar uma base de clientes e entre eles existe um método muito simples e muito poderoso, o modelo RFM. O modelo RFM consiste em usar 3 infomações para agrupar nossos clientes, a recência, a frequência e o valor monetário. Mas o que são estas informações?

**1. Recency (recência):** De modo geral, a recência indica há quanto tempo atrás o seu cliente executou uma ação desejada, no nosso caso, a ultima compra.


**2. Frequency (frequência):** A frequência, por sua vez, indica quantas vezes ele repete essa ação em um determinado período de tempo, no nosso, em toda sua vida como cliente.


**3. Monetary (Valor monetário)**: O valor monetário, por fim, indica qual é o valor agregado por esse cliente, em nosso caso, nos não iremos utilzar esta ultima informação, pois ela esta altamente relacionada com a frequência.

# Planejamento do Projeto
Utilizei o canvas abaixo para melhor organização do projeto:
<p align="center">
  <img src="https://github.com/leorviana/segmentacao_de_clientes/blob/main/images/Canvas%20DS%20RFM.png">
</p>

# Modelo RFM

Após buscarmos as recencia, a frequência e o valor monetário, é hora de atribuir uma pontuação — ou score, em inglês. A pontuação varia de 1 a 5, onde quanto maior esse número, melhor. Essa pontuação é atribuída para cada uma das letras, ou seja, R terá uma pontuação, F terá outra e M também, podendo ser iguais ou não — por exemplo, todas as letras podem receber uma pontuação 5.


Tendo as três pontuações de R, F e M do cliente, é hora de classificá-lo dentro de uma de 11 categorias chamadas de Segmento, que podem ir desde Champion — um cliente que comprou muitas vezes, há poucos dias e que já gastou muito dinheiro — até Lost — cliente que tem muito tempo que não compra, gastou pouco e que utilizou poucas vezes nosso serviço.


O cálculo para saber qual segmento do seu cliente é bem simples. Primeiro, você irá pegar o score de R do seu comprador. Em seguida, você irá tirar uma média entre o score F e de M, ou ira utilizar apenas um dele dependendo do seu problema, este é o nosso caso. Esses dois resultados juntos cairão dentro de um dos grupos abaixo. Confira:

<p align="center">
  <img src="https://miro.medium.com/max/1234/1*oUKMc3gk53hccFX4YNeu1g.png">
</p>

E o quê significa cada segmento desse?

**1. Champions:** Este grupo comprou algum produto de nossa empresa recentemente, e se considerarmos todos os outros clientes, eles são nossos principais compradores, significa que seu número de transações é o maior em comparação com nossos outros clientes.

**2. Loyal Customers:** Se algum cliente está incluído neste grupo, isso significa que ele compra algo regularmente. Sua frequência e recência são bastante boas para nós.

**3. Potential Loyalists:** Esse tipo de cliente são nossos clientes recentes com frequência média.

**4. New customers:** Compraram algo mais recentemente. Mas sua frequência é realmente pequena. Daqui podemos deduzir que são os nossos novos clientes. Eles acabaram de visitar nosso site. Podemos oferecer-lhes algumas ofertas especiais de 'Bem-vindo'.

**5. Promising:** Eles são compradores recentes, mas não compraram muito. Sua recência é um pouco maior do que novos clientes.

**6. Need Atention:** A caracteristica deste grupo é que eles estão acima da média de recência e frequência. Nas próximas etapas veremos uma representação visual desses grupos, lá obviamente observaremos que esse grupo está no meio quando todos os clientes são considerados em termos de valores de 'frequência' e 'recência'. Isso significa que, se for dada atenção especial a esse grupo, eles podem estar nos grupos 'Fieis', 'Potencial fiel' ou até 'campeoes', caso contrário, eles podem estar nos grupos 'em risco', 'prestes a dormir' ou 'hibernando'. As decisões de ação que tomaremos podem mover esse grupo para grupos mais valiosos.

**7. About to sleep:** Estão abaixo da recência e frequência médias. Podemos perdê-los se não forem reativados.

**8. At risk:** Sua frequência está acima da média, mas eles não estão presentes há muito tempo, o que significa que não compraram recentemente. Precisamos trazê-los de volta.

**9. Can't loose then:** Eles são nossos principais compradores, considerando todos os outros clientes, mas não visitam nosso site há muito tempo. Não devemos perder esse grupo. Porque o número de transações deles é muito alto. Temos de reconquistá-los, fazer-lhes ofertas especiais e fazê-los sentir-se valiosos. Além disso, podemos realizar uma pesquisa para esse grupo para investigar por que eles não estão presentes por muito tempo, é anormal porque a frequência deles é a maior entre todos os clientes.

**10. Hibernating:** Sua última compra foi há muito tempo e um possuem baixo número de compras. Podemos perdê-los.

# Ferramentas Utilizadas
 - Python 3.8
 - Jupyter Notebook
 - Método CRISP-DM para gerenciamento de projeto de dados.

# Relatório de Análise
Durante o processo, nós analisamos os dados de diversos angulos e levantamos algumas hipóteses a respeito dos nossos clientes. Abaixo se encontra um breve relatório constando todas as observações e insights retirados da análise:

## Atributos Pessoais

### Apenas 11% dos nossos clientes não são graduados.
<p align="center">
  <img src="https://github.com/leorviana/segmentacao_de_clientes/blob/main/images/graduados.png">
</p>

### 64% dos clientes possuem um parceiro.
<p align="center">
  <img src="https://github.com/leorviana/segmentacao_de_clientes/blob/main/images/marital_status.png">
</p>

### 70% dos clientes possuem pelo menos 1 filho.
<p align="center">
  <img src="https://github.com/leorviana/segmentacao_de_clientes/blob/main/images/filhos.png">
</p>


## Relacionamento com a Empresa

### De todos os 2240 cadastrados em nossa base, apenas 21 deles realizaram algum tipo de reclamação formal.
<p align="center">
  <img src="https://github.com/leorviana/segmentacao_de_clientes/blob/main/images/complain.png">
</p>

### Em média nossos clientes realizaram um total de 12 compras conosco em seu tempo de vida atual, mas existe um pico de clientes que realizaram apenas 5 compras.
<p align="center">
  <img src="https://github.com/leorviana/segmentacao_de_clientes/blob/main/images/total_compras.png">
</p>

## Hábitos de Consumo

### Os clientes compram em média mais pela loja fisica, depois pela internet e pouquissimas vezes compram pelo catálogo.
<p align="center">
  <img src="https://github.com/leorviana/segmentacao_de_clientes/blob/main/images/meios.png">
</p>

### Dentre os produtos oferecidos, o que mais gera receita são os vinhos.
<p align="center">
  <img src="https://github.com/leorviana/segmentacao_de_clientes/blob/main/images/vinhos.png">
</p>


## Análise Bivariada

### H1: Clientes com elevados graus de instrução ganham mais.
**Verdadeiro:** Essa diferença salarial se aplica apenas entre as pessoa que possuem algum nível de graduação e as que não possuem, mas entre pessoas graduadas e pós-graduadas não temos muita diferença.
<p align="center">
  <img src="https://github.com/leorviana/segmentacao_de_clientes/blob/main/images/grau_salario.png">
</p>

### H2: Clientes em relacionamentos gastam mais.
**Falso:** Não existe relação entre o estado civil e o total gasto. O teste ANOVA realizado logo após o gráfico nos confirma isto.
<p align="center">
  <img src="https://github.com/leorviana/segmentacao_de_clientes/blob/main/images/relacionameto_gasto.png">
</p>

### H3: Clientes que ganham mais gastam mais.
**Verdadeiro:** O total gasto possui uma relação quase exponencial com o salario(excluindo alguns outliers). Com uma correlação de 0.79.
<p align="center">
  <img src="https://github.com/leorviana/segmentacao_de_clientes/blob/main/images/gasto_salario.png">
</p>

### H4: Clientes antigos possuem um gasto médio por compra maior.
**Falso:** Não existe nenhuma relação entre o tempo como cliente e o gasto médio.
<p align="center">
  <img src="https://github.com/leorviana/segmentacao_de_clientes/blob/main/images/tempo_gasto_medio.png">
</p>

### H5: Clientes que possuem filhos gastam mais.
**Falso:** Na realidade é bem o contrário, clientes que não possuem filhos gastam 40% a mais do que clientes sem filho.
<p align="center">
  <img src="https://github.com/leorviana/segmentacao_de_clientes/blob/main/images/gasto_filhos.png">
</p>

### H6: Clientes compram mais por promoções costumam comprar menos frequentemente.
**Falso:** Não existe relação significativa entre o numero de compras em promoções e a quantidade de compras.
<p align="center">
  <img src="https://github.com/leorviana/segmentacao_de_clientes/blob/main/images/promo_frequencia.png">
</p>


# Resultados
Após a modelagem, 2233 clientes foram separados entre os 10 grupos definidos anteriormente. Com esta abordagem a equipe de marketing será capaz de tomar decisões táticas, identificar e segmentar rapidamente os usuários em grupos homogêneos e direcioná-los com estratégias de marketing diferenciadas e personalizadas. Isso, por sua vez, melhora o engajamento e a retenção do usuário.

Após a segmentação, os nossos clientes ficaram divididos da seguinte maneira:
<p align="center">
  <img src="https://github.com/leorviana/segmentacao_de_clientes/blob/main/images/grafico_rfm.png">
</p>


    hibernando            16.30%
    em_risco              16.12%
    potenciais_fieis      15.54%
    fieis                 15.49%
    prestes_a_dormir       8.55%
    campeoes               7.52%
    n_podem_perder         7.03%
    novos_consumidores     4.97%
    promissores            4.93%
    precisam_atencao       3.54%

Com isso, a equipe terá informações suficientes para saber quais são os clientes que devem ser fidelizados e recompensados — Champions e Loyal Customers — ; quem precisa ser conquistado para continuar comprando — Potential Loyalist e New Customer — ; e até quem precisa ser resgatado antes que deixem de comprar em nossa loja — At Risk e Can’t Lose Them.

# Conclusão
Após todo o processo conseguimos separar nossos clientes devidamente entre os 10 grupos e agora somos capazes de tomar melhores decisões, se comunicar melhor com o cliente e assim rete-los, abaixo listo algumas dicas acionáveis para cada grupo:

**Champions ->** Recompensa-los. Podem ser os primeiros a adotar novos produtos. Irão promover a marca.

**Loyal Customers ->** Upselling de produtos de maior valor. Pedir avaliações. Envolve-los.

**Potential Loyalist ->** Oferecer adesão/programa de fidelidade, recomendar outros produtos.

**Recent Customers ->** Fornecer suporte, dar a eles acesso antecipado, comecar a construir relacionamentos.

**Promising ->** Criar reconhecimento da marca, oferecer avaliações gratuitas

**Need Attention ->** Fazer ofertas por tempo limitado, recomendar com base em compras anteriores. Reativa-los.

**About To Sleep ->** Compartilhar recursos valiosos, recomendar produtos populares com desconto, reconectar com eles.

**At Risk ->** Enviar e-mails personalizados para se reconectar, oferecer renovações, fornecer recursos extras.

**Can’t Lose Them ->** Conquista-los de volta por meio de renovações ou produtos mais novos, não os perder para a concorrência, conversar com eles.

**Hibernating ->** Oferecer outros produtos relevantes e descontos especiais. Recriar o valor da marca.


# Próximos Passos
Para um segundo ciclo desta solução, poderemos clusterizar usando algum método de ML, assim incluiremos outras variáveis que podem ser muito úteis na hora de agrupar os clientes, como seus hábitos de consumo.

# Referências

Vasconcellos, Paulo. "O que é RFM e como aplicá-lo ao seu time de Customer Success". **Medium**. Disponível em: <https://medium.com/maxmilhas-tech/o-que-%C3%A9-rfm-e-como-aplic%C3%A1-lo-ao-seu-time-de-customer-service-b9c35817ed01>


"RFM Analysis For Successful Customer Segmentation". **PUTLER**. Disponível em: <https://www.putler.com/rfm-analysis/>
