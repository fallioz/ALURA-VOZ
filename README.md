# ALURA-VOZ

A Alura Voz é uma empresa de telecomunicação que nos contratou para atuar como cientistas de dados na equipe de vendas. Logo na primeira semana, a liderança nos informa que é muito necessário realizar um estudo quanto ao Churn da empresa. É explicado que o churn indica se um cliente cancelou ou não o contrato com a empresa, e também que, nos casos de perda do cliente a empresa também perde faturamento, o que ocasiona prejuizos na receita final.

## Dados
Ao observar a Base de dados da Alura Voz, verificamos que essa é uma base disponibilizada via API em formato JSON com várias camandas de dados.

Junnto a esses dados também foi disponibilizado o dicionário dos dados que nele contém todas as informações sobre as colunas do banco de dados.

Nela, além da informação se o cliente deixou ou não a empresa, também contém:

+ Cliente:

`gender`: gênero (masculino e feminino)<br>
`SeniorCitizen`: informação sobre um cliente ter ou não idade igual ou maior que 65 anos<br>
`Partner`: se o cliente possui ou não um parceiro ou parceira<br>
`Dependents`: se o cliente possui ou não dependentes<br>

+ Serviço de telefonia

`tenure`: meses de contrato do cliente<br>
`PhoneService`: assinatura de serviço telefônico<br>
`MultipleLines`: assisnatura de mais de uma linha de telefone<br>

+ Serviço de internet

`InternetService`: assinatura de um provedor internet<br>
`OnlineSecurity`: assinatura adicional de segurança online<br>
`OnlineBackup`: assinatura adicional de backup online<br>
`DeviceProtection`: assinatura adicional de proteção no dispositivo<br>
`TechSupport`: assinatura adicional de suporte técnico, menos tempo de espera<br>
`StreamingTV`: assinatura de TV a cabo<br>
`StreamingMovies`: assinatura de streaming de filmes<br>

+ Contrato

`Contract`: tipo de contrato<br>
`PaperlessBilling`: se o cliente prefere receber online a fatura<br>
`PaymentMethod`: forma de pagamento<br>
`Charges.Monthly`: total de todos os serviços do cliente por mês<br>
`Charges.Total`: total gasto pelo cliente<br>
