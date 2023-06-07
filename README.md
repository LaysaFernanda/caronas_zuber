# caronas_zuber
Análise de padrões de uma empresa de compartilhamento de caronas

Neste projeto analisei padrões das informações diponíveis da empresa Zuber, de compartilhamento de caronas, para entender as preferências dos passageiros e o impacto de fatores externos nas corridas.

### Descrição dos dados

A tabela neighborhoods: dados sobre os bairros da cidade
- name: nome do bairro
- neighborhood_id: código do bairro

A tabela cabs: dados sobre os táxis
- cab_id: código do veículo
- vehicle_id: a identificação técnica do veículo
- company_name: a empresa proprietária do veículo

A tabela trips: dados sobre corridas
- trip_id: código da corrida
- cab_id: código do veículo que opera a corrida
- start_ts: data e hora do início da corrida (tempo arredondado para a hora)
- end_ts: data e hora do final da corrida (tempo arredondado para a hora)
- duration_seconds: duração da corrida em segundos
- distance_miles: distância percorrida em milhas
- pickup_location_id: código do bairro de retirada
- dropoff_location_id: código do bairro de entrega

A tabela weather_records: dados sobre o clima
- record_id: código de registro meteorológico
- ts: grava data e hora (tempo arredondado para a hora)
- temperature: temperatura quando o registro foi feito
- description: breve descrição das condições meteorológicas, ex. "chuva leve" ou "nuvens esparsas"

### Bibliotecas usadas
- pandas
- requests
- BeautifulSoup
- scipy
