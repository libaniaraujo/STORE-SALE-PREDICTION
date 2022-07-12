# STORE SALE PREDICTION
  
<img src = "https://user-images.githubusercontent.com/94937578/178171956-dd6dd7ec-07b5-4430-aa2b-0c395a555999.PNG" width="1000px" />
</div>

## 1. Resumo:

- <b>Código no Jupyter Notebook</b>
- <b>Dashboard no Streamlit</b>

## 2. Contexto:

O CFO da empresa fez uma reunião com todos os gerentes de loja e pediu para que cada um deles trouxesse uma previsão diária das próximas 6 semanas de vendas. Depois dessa reunião, todos os gerentes entraram em contato com você, requisitando uma previsão de vendas de sua loja.

## 3. Problema de negócio:


## 4. Planejamento da solução:

<b>4.0. Implementação do método de gerenciamento CRISP-DM (Cross-Industry Process – Data Science):</b>

<img src = "https://user-images.githubusercontent.com/94937578/178171624-823275d2-6368-463b-a2fd-358a0d059b79.png" width="1000px" />


<b>4.1. Entendimento do negócio:</b>

<b>4.2. Construção das hipóteses:</b>

<b>4.3. Coleta e limpeza dos dados</b>

<b>4.4. Seleção de atributos</b>

## 5. Dados:

- Será utilizado o conjundo de dados disponibilizado na plataforma Kaggle (https://www.kaggle.com/competitions/rossmann-store-sales/)
- Os atributos apresentados no conjunto de dados são descritos na tabela abaixo:

**Atributo** | **Descrição**
--- | --- 
`Id` - an Id that represents a (Store, Date) duple within the test set
`Store` - ID único para cada loja
`Sales` - Número de vendas no dia
`Customers` - O número de clientes no dia
`Open` - Indica se a loja está fechada ou aberta na data: 0 = fechada, 1 = aberta
`StateHoliday` - indicates a state holiday. Normally all stores, with few exceptions, are closed on state holidays. Note that all schools are closed on public holidays and weekends. a = public holiday, b = Easter holiday, c = Christmas, 0 = None
`SchoolHoliday` - indicates if the (Store, Date) was affected by the closure of public schools
`StoreType` - differentiates between 4 different store models: a, b, c, d
`Assortment` - describes an assortment level: a = basic, b = extra, c = extended
`CompetitionDistance` - distance in meters to the nearest competitor store
`CompetitionOpenSince[Month/Year]` - gives the approximate year and month of the time the nearest competitor was opened
`Promo` - indicates whether a store is running a promo on that day
`Promo2` - Promo2 is a continuing and consecutive promotion for some stores: 0 = store is not participating, 1 = store is participating
`Promo2Since[Year/Week]` - describes the year and calendar week when the store started participating in Promo2
`PromoInterval` - describes the consecutive intervals Promo2 is started, naming the months the promotion is started anew. E.g. "Feb,May,Aug,Nov" means each round starts in February, May, August, November of any given year for that store

## 6. Principais resultados:

## 7. Produto final (dashboard):

## 8. Referências:

- [<b>Comunidade DS</b>](https://www.comunidadedatascience.com/)

