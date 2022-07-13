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

