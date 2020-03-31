| [Home](https://techlipe.github.io/Workshop-Zero-To-Hero) | [Dia 01](https://techlipe.github.io/Workshop-Zero-To-Hero/dia01-configuracoes) | [Dia 02](https://techlipe.github.io/Workshop-Zero-To-Hero/dia02-observabilidade) | [Dia 03](https://techlipe.github.io/Workshop-Zero-To-Hero/dia03-elasticsearch) | [Dia 04](https://techlipe.github.io/Workshop-Zero-To-Hero/dia04-logstash) | [Dia 05](https://techlipe.github.io/Workshop-Zero-To-Hero/dia05-kibana) | 

# Workshop Elastic - Zero to Hero (Dia 2)
* **Criado por:** Felipe Queiroz e Anselmo Borges <br>
* **Última atualização:** 30.03.2020

![slide](https://github.com/AnselmoBorges/zerotohero/blob/master/Slide1.jpg)

## Configurando o Metricbeat para monitorar os containeres
Baixar o pacote do metricbeat
```
curl -L -O https://artifacts.elastic.co/downloads/beats/metricbeat/metricbeat-7.6.1-darwin-x86_64.tar.gz
tar xzvf metricbeat-7.6.1-darwin-x86_64.tar.gz
cd metricbeat-7.6.1-darwin-x86_64/
```

Habilitar modulos do metricbeat
```
./metricbeat modules enable docker
```

Subir os templates de Dashboard pro Kibana e Inicializar o Serviço
```
./metricbeat setup
./metricbeat -e
```

## Instalando HTTPD e Monitorando métricas e logs do Apache

## Implementando APM na sua Aplicação!
