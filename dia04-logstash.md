| [Home](https://techlipe.github.io/Workshop-Zero-To-Hero) | [Dia 01](https://techlipe.github.io/Workshop-Zero-To-Hero/dia01-configuracoes) | [Dia 02](https://techlipe.github.io/Workshop-Zero-To-Hero/dia02-observabilidade) | [Dia 03](https://techlipe.github.io/Workshop-Zero-To-Hero/dia03-elasticsearch) | [Dia 04](https://techlipe.github.io/Workshop-Zero-To-Hero/dia04-logstash) | [Dia 05](https://techlipe.github.io/Workshop-Zero-To-Hero/dia05-kibana) | 

# Workshop Elastic - Zero to Hero (Dia 4)
* **Criado por:** Felipe Queiroz e Anselmo Borges <br>
* **Última atualização:** 31.03.2020

![slide](https://github.com/AnselmoBorges/zerotohero/blob/master/Slide1.jpg)

Fala pessoal! Sejam muito bem vindos ao nosso Dia 04 de Workshop de Zero to Hero com toda a Elastic Stack. Hoje vimos como funciona o logstash e os pipelines de ingestão de dados. Antes de começar a seguir o nosso tutorial não esqueça de baixar o dataset de filmes no repositorio git do Workshop ;)


## Instalando o Logstash no Servidor local
**Baixar o pacote do logstash**
```
curl -L -O https://artifacts.elastic.co/downloads/beats/metricbeat/metricbeat-7.6.1-x86_64.rpm
sudo rpm -vi logstash-7.6.1-x86.64.rpm
```

##Primeiro laboratorio, como funciona o Grok Debugger!
**Criando o primeiro pipeline**
```
```

**Utilizando o Grok Debugger para processar dados não estruturados**
```
```

**Obs: Melhores práticas de uso de pipelines**
```
```

##Segundo laboratorio, consumindo um dataset de filmes json (arquivo de configuração disponivel no github)
```
```

**Primeiro Stdout de Teste**
```
```

**Implementando o Plugin Date e indexando no Elasticsearch**
```
```

**Validando via API o resultado**
```
```

