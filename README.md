# Raspagem de dados de aluguel social no estado do Rio de Janeiro
Os dados históricos de aluguel social por mês e comunidade no estado do Rio de Janeiro são disponibilizados no portal: http://www.portalaluguelsocial.rj.gov.br/Default.asp

Porém, os dados estão disponíveis apenas para consulta de uma tabela por vez para cada combinação de data e comunidade. Para possibilitar análise da série histórica, foi desenvolvido um script em Python, utilizando a lib Selenium, para acessar dinamicamente todas as possíveis combinações de data e comunidade, armazenando o valor total de aluguéis pagos em uma tabela. Os dados raspados estão disponibilizados nesse repositório em formato .csv e .xlsx, bem como o script utilizado. Futuramente análises dos dados serão publicadas.  
