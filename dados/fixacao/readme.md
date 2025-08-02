`performance_campanhas.csv`: **dicionário de dados**

| Feature           | Descrição                                   |
|-------------------|---------------------------------------------|
| objetivo_campanha | objetivo da campanha de marketing           |
| visualizacoes     | total de visualizações obtidas nos anúncios |
| investimento_brl  | investimento em tráfego pago (em R$)        |
| cliques           | total de cliques obtidos nos anúncios       |

<br>

`credit_risk.csv`: **dicionário de dados**

|        Coluna     |                          Descrição                          |
|-------------------|----------------------------------------------------------------------|
|      rev_util     | Utilização da linha de crédito em relação ao total disponível (0 a 1). |
|        age        | A idade do tomador em anos.                                  |
|    late_30_59     | Número de Vezes em Atraso de 30-59 Dias. Ajuda a avaliar o comportamento de inadimplência de curto prazo. |
|     debt_ratio    | Proporção dos pagamentos mensais de dívida (incluindo empréstimos, pensão alimentícia, etc.) sobre o rendimento bruto mensal. Reflete a carga total de dívida do tomador. |
|    monthly_inc    | A renda bruta mensal do tomador.                      |
|    open_credit    | Número de Linhas de Crédito e Empréstimos Abertos. |
|      late_90      | Número de Vezes em Atraso de 90 Dias. Indica problemas graves de inadimplência. |
|    real_estate    | Número de Empréstimos ou Linhas Imobiliárias. |
|    late_60_89     | Número de Vezes em Atraso de 60-89 Dias. Ajuda a avaliar o comportamento de inadimplência de médio prazo. |
|    dependents     | Número de Dependentes. |
|      dlq_2yrs     | Inadimplência Grave em 2 Anos – Variável alvo que indica se o tomador enfrentou uma inadimplência grave no período de dois anos. Valor 1 indica inadimplência; 0 indica ausência. |
 

<br>

`mall_customers.csv`: **dicionário de dados**

|          Feature |                    Description |
|------------------|--------------------------------|
|      id          | ID do cliente                  |
|      age         | idade de cliente               |
|      income      | renda anual                    |
|      score       | potencial de compra (score)    |

<br>

`kidney_disease_dataset.csv`: **dicionário de dados**

| Nome da Coluna     | Descrição                                                                                          |
|--------------------|----------------------------------------------------------------------------------------------------|
| Age                | Idade do paciente em anos. Idade avançada aumenta o risco de DRC.                                  |
| Creatinine_Level   | Nível de creatinina no sangue (mg/dL), um marcador chave da função renal.                          |
| BUN                | Nível de nitrogênio ureico no sangue (mg/dL). Níveis elevados podem indicar DRC.                   |
| Diabetes           | 1 se o paciente tem diabetes, caso contrário 0. Diabetes é um importante fator de risco.           |
| Hypertension       | 1 se o paciente tem pressão alta, caso contrário 0. Frequentemente associado a problemas renais.   |
| GFR                | Taxa de filtração glomerular (mL/min/1,73m²), a melhor medida da função renal.                     |
| Urine_Output       | Urina produzida em mL/dia. Baixo débito pode indicar disfunção renal.                              |
| CKD_Status         | 1 se o paciente tiver doença renal crônica, caso contrário 0.                                      |