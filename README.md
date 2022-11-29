# Análise de Dados com Python
## Desafio:
Você trabalha em uma empresa de telecom e tem clientes de vários serviços diferentes, entre os principais: internet e telefone.

O problema é que, analisando o histórico dos clientes dos últimos anos, você percebeu que a empresa está com Churn de mais de 26% dos clientes.

Isso representa uma perda de milhões para a empresa.

O que a empresa precisa fazer para resolver isso?

Base de Dados: https://drive.google.com/drive/folders/1T7D0BlWkNuy_MDpUHuBG44kT80EmRYIs?usp=sharing
Link Original do Kaggle: https://www.kaggle.com/radmirzosimov/telecom-users-dataset


# Passo a Passo:
  ## Passo 1: Importar base de dados
  ## Passo 2: Visualizar a base de dados
    - coluna churn = foi cancelado
    - Entender quais as informações estão dísponiveis
    - Descobrir os "furos" da base de dados 
  ## Passo 3: Tratamento de dados
    - Valores que estão sendo reconhecidos de forma errada
    - Valores vazios -> VALORES QUE NÃO TE AJUDAM TE ATRAPALHA.   
  ## Passo 4: Análise inicial
  ## Passo 5: Análise mais completa
  
  
# Conclusões:

- Clientes com contrato mensal tem MUITO mais chance de cancelar:
    - podemos fazer promoções para o cliente ir para o plano anual
    
- Familias maiores tendem a cancelar menos do que familia menores
    - podemos fazer promoções pra pessoa pegar uma linha adicional de telefone

- MesesComoCliente baixos tem MUITO cancelamento, Clientes com pouco tempo como clientes tendem a cancelar MUITO
    - a primeira experiência como cliente na operadore pode ter sido ruim
    - talvez a captação de clientes que estão fazendo, pode estar trazendo clientes desqualificados
    - ideia: podemos criar incentivos para a pessoa ficar mais tempo como cliente
    
- Quanto mais serviços o cara tem, menos chance ele tem de cancelar
    - podemos fazer mais promoções com mais serviços para o cliente
    
- Tem alguma coisa no nosso serviço de Fibra que ta fazendo os clientes cancelarem
    - agir sobre a fibra
    
- Clientes no boleto tem MUITO mais chances de cancelar
    = Temos que fazer alguma ação para eles irem para outras formas de pagamento



# Bibliotecas:
  - Pandas
  - Plotly
  
# IDE:
  - Jupyter notebook
