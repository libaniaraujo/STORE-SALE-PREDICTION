# STORE SALE PREDICTION
  
<img src = "https://user-images.githubusercontent.com/94937578/178171956-dd6dd7ec-07b5-4430-aa2b-0c395a555999.PNG" width="1000px" />
</div>

## 1. Resumo:

- <b>Código no Jupyter Notebook</b>
- <b>Dashboard no Streamlit</b>

## 2. Contexto:

O CFO da empresa Rossman fez uma reunião com todos os gerentes de loja e pediu para que cada um deles trouxesse uma previsão diária das próximas 6 semanas de vendas. Depois dessa reunião, todos os gerentes entraram em contato com você, requisitando uma previsão de vendas de sua loja.

## 3. Problema de negócio:

Previsão de vendas das lojas da empresa Rossman nas próximas 6 semanas.

## 4. Planejamento da solução:

### 4.0. Implementação do método de gerenciamento CRISP-DM (Cross-Industry Process – Data Science):

<img src = "https://user-images.githubusercontent.com/94937578/178171624-823275d2-6368-463b-a2fd-358a0d059b79.png" width="1000px" />

### 4.1. Entendimento do problema de negócio:

#### o Entender a motivação:
- Qual o contexto?
  O CFO requisitou essa solução durante uma reunião de resultados mensais.

#### o	Entender a causa raiz do problema:
- Por que fazer uma previsão de vendas?
  Investimento em reforma das lojas
#### o	Entender quem é o dono do problema:
- Quem é o steakholder?
  CFO ou pessoas próximas a ele.

#### o	Entender o formato da solução:
- Qual o formato de entrega da solução?
   * Granularidade: Vendas diárias em R$ nas próximas 6 semanas.
   * Tipo de problema: Problema de predição.
   * Principais métodos: Time Series, Regressão e Redes Neurais.
   * Formato da entrega:

### 4.2. Construção das hipóteses:

<img src = "https://user-images.githubusercontent.com/94937578/178730870-6b257e8c-0603-4f93-8d04-12adaf35b9c0.png" width="1000px" />

- Hipóteses que serão validadas pela análise exploratória dos dados:

  - Lojas com maior sortimento deveriam vender mais.
  - Lojas com competidores mais próximos deveriam vender menos.
  - Lojas com competidores à mais tempo deveriam vender mais.
  - Lojas com promoções ativas por mais tempo deveriam vender mais.
  - Lojas com mais dias de promoção deveriam vender mais.
  - Lojas com mais promoções consecutivas deveriam vender mais.
  - Lojas abertas no feriado de natal deveriam vender mais.
  - Lojas deveriam vender mais ao longo dos anos.
  - Lojas deveriam vender mais no segundo semestre do ano.
  - Lojas deveriam vender menos aos finais de semana.
  - Lojas deveriam vender mais depois do dia 10 de cada mês.
  - Lojas deveriam vender menos aos finais de semana.
  - Lojas deveriam vender menos durante os feriados escolares.

### 4.3. Coleta, descrição e limpeza dos dados

### 4.4. Feature Engineering

### 4.5. Análise exploratória dos dados

### 4.6. Preparação dos dados e seleção de atributos

### 4.7. Treinamento algoritmos de Machine Learning

### 4.8. Deploy do modelo em produção

## 5. Dados:

- Será utilizado o conjundo de dados disponibilizado na plataforma Kaggle (https://www.kaggle.com/competitions/rossmann-store-sales/).
- Os atributos apresentados no conjunto de dados são descritos na tabela abaixo:

**Atributo** | **Descrição**
--- | --- 
`Id` | Um ID que representa uma duplicata (Loja, Data) no conjunto de teste
`Store`  | ID único para cada loja
`Sales` | Número de vendas no dia
`Customers` | O número de clientes no dia
`Open` | Indica se a loja está fechada ou aberta na data: 0 = fechada, 1 = aberta
`StateHoliday` | Indica feriado estadual. Normalmente todas as lojas, com poucas exceções, estão fechadas nos feriados estaduais. Observe que todas as escolas estão fechadas nos feriados e fins de semana. a = feriado, b = feriado da páscoa, c = natal, 0 = nenhum
`SchoolHoliday` |  indica se a (Loja, Data) foi afetada pelo fechamento de escolas públicas
`StoreType` | diferencia entre 4 modelos de loja diferentes: a, b, c, d
`Assortment` | descreve um nível de sortimento: a = básico, b = extra, c = estendido
`CompetitionDistance` | Distância em metros até a loja concorrente mais próxima
`CompetitionOpenSince[Month/Year]` | Fornece o ano e o mês aproximados em que o concorrente mais próximo foi aberto
`Promo` | Indica se uma loja está realizando uma promoção naquele dia
`Promo2` | É uma promoção contínua e consecutiva para algumas lojas: 0 = a loja não está participando, 1 = a loja está participando
`Promo2Since[Year/Week]` | Descreve o ano e a semana do calendário em que a loja começou a participar da Promo2
`PromoInterval` | Descreve os intervalos consecutivos em que a Promo2 é iniciada, nomeando os meses em que a promoção é iniciada novamente. Por exemplo. "Fevereiro, maio, agosto, novembro" significa que cada rodada começa em fevereiro, maio, agosto, novembro de qualquer ano para essa loja

## 6. Principais resultados:

## 7. Produto final (dashboard):

## 8. Referências:

- [<b>Comunidade DS</b>](https://www.comunidadedatascience.com/)

