
<h1 align="left">Linguagens e Ferramentas</h1>
<p align="left"> <a href="https://pandas.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/2ae2a900d2f041da66e950e4d48052658d850630/icons/pandas/pandas-original.svg" alt="pandas" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://scikit-learn.org/" target="_blank" rel="noreferrer"> <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="scikit_learn" width="40" height="40"/> </a> <a href="https://seaborn.pydata.org/" target="_blank" rel="noreferrer"> <img src="https://seaborn.pydata.org/_images/logo-mark-lightbg.svg" alt="seaborn" width="40" height="40"/> </a> <a href="https://www.tensorflow.org" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/tensorflow/tensorflow-icon.svg" alt="tensorflow" width="40" height="40"/> </a> </p>

# Segmentação de Clientes para Marketing através de Clusterização

Este conjunto de dados de amostra resume o comportamento de uso de cerca de 9.000 titulares de cartão de crédito ativos durante os últimos 6 meses. O arquivo está no nível do cliente com 18 variáveis ​​comportamentais.

## Sobre o Dataset

O dataset utilizado contém as seguintes colunas:

- `CUST_ID`: ID do cliente
- `BALANCE`: Saldo atual do cliente
- `BALANCE_FREQUENCY`: Frequência de atualização do saldo
- `PURCHASES`: Total de compras
- `ONEOFF_PURCHASES`: Compras únicas (sem parcelamento)
- `INSTALLMENTS_PURCHASES`: Compras parceladas
- `CASH_ADVANCE`: Antecipação de dinheiro 
- `PURCHASES_FREQUENCY`: Frequência de compras
- `ONEOFF_PURCHASES_FREQUENCY`: Frequência de compras únicas
- `PURCHASES_INSTALLMENTS_FREQUENCY`: Frequência de compras parceladas
- `CASH_ADVANCE_FREQUENCY`: Frequência de antecipação de dinheiro
- `CASH_ADVANCE_TRX`: Transações de antecipação de dinheiro
- `PURCHASES_TRX`: Transações de compras
- `CREDIT_LIMIT`: Limite de crédito
- `PAYMENTS`: Pagamentos
- `MINIMUM_PAYMENTS`: Pagamentos mínimos.
- `PRC_FULL_PAYMENT`: Porcentagem de pagamento total
- `TENURE`: Tenência 

## Objetivo

O principal objetivo deste projeto é identificar padrões e obter insights sobre os diferentes grupos de clientes, possibilitando estratégias de marketing e campanhas mais eficazes.

## Bibliotecas Utilizadas

- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn (para pré-processamento e KMeans)
- PCA (para redução de dimensionalidade)
- TensorFlow (para construção de modelo)
- warnings (para controle de avisos)

```python
import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt
from sklearn.preprocessing import StandardScaler
from sklearn.cluster import KMeans
from sklearn.decomposition import PCA
import warnings
from tensorflow.keras.layers import Input, Dense
from tensorflow.keras.models import Model
warnings.filterwarnings('ignore')
```

## Instruções de Uso

-Clone o repositório.
-Instale as dependências utilizando pip.
-Execute o script principal para obter os resultados da clusterização.

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE.md](LICENSE.md) para detalhes.

### Resumo da Licença MIT

- **Permissões**: 
  - Uso comercial 
  - Modificação 
  - Distribuição 
  - Uso privado
  
- **Limitações**:
  - O software é fornecido "como está", sem qualquer tipo de garantia.

- **Condições**:
  - A licença e o aviso de direitos autorais devem ser incluídos em todas as cópias ou partes substanciais do software.

Para mais informações sobre a Licença MIT, [clique aqui](https://opensource.org/licenses/MIT).



