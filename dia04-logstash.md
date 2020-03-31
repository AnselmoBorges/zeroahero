| [Home](https://techlipe.github.io/Workshop-Zero-To-Hero) | [Dia 01](https://techlipe.github.io/Workshop-Zero-To-Hero/dia01-configuracoes) | [Dia 02](https://techlipe.github.io/Workshop-Zero-To-Hero/dia02-observabilidade) | [Dia 03](https://techlipe.github.io/Workshop-Zero-To-Hero/dia03-elasticsearch) | [Dia 04](https://techlipe.github.io/Workshop-Zero-To-Hero/dia04-logstash) | [Dia 05](https://techlipe.github.io/Workshop-Zero-To-Hero/dia05-kibana) | 

# Workshop Elastic - Zero to Hero (Dia 4)
* **Criado por:** Felipe Queiroz e Anselmo Borges <br>
* **Última atualização:** 31.03.2020

![slide](https://github.com/AnselmoBorges/zerotohero/blob/master/Slide1.jpg)

Fala pessoal! Sejam muito bem vindos ao nosso Dia 04 de Workshop de Zero to Hero com toda a Elastic Stack. Hoje vimos como funciona o logstash e os pipelines de ingestão de dados. Antes de começar a seguir o nosso tutorial não esqueça de baixar o dataset de filmes no repositorio git do Workshop ;)


## Instalando o Logstash no Servidor local
**Instalar o Java no SO**
```
sudo yum install java -y
```

**Validar instalação do Java**
```
java -version
openjdk version "1.8.0_242"
OpenJDK Runtime Environment (build 1.8.0_242-b08)
OpenJDK 64-Bit Server VM (build 25.242-b08, mixed mode
```

**Baixar e instalar o pacote do logstash**
```
curl -L -O https://artifacts.elastic.co/downloads/logstash/logstash-7.6.2.rpm
sudo rpm -vi logstash-7.6.1-x86.64.rpm
```

### Um pouco de teoria
Logstash é uma aplicação java que faz um papel de um ETL (Extract, transform, load) na Stack. O mesmo tem um grande potencial de tratar grandes volumes de dados de diferentes origens. Cada processo dentro do logstash é chamado de _pipeline_.

Dentro de cada _pipeline_ teremos um arquivo de configuração que será associado que pode ser divido em 3 seções, sendo elas **Input, Filter e Output**, de maneira bem intuitiva carrega os dados de alguma fonte, processa (ou não) esses dados e por final "despeja" em algum datasource.

Em cada uma de suas seções temos uma grande variedade de plugins disponíveis que possibilitam conexões em bancos relacionais, brokers, aplicações REST e transformação desses dados de várias formas.


## Primeiro laboratorio, como funciona o plugin de filtro Grok Debugger!

**Criando o primeiro pipeline**
```
```

**Utilizando o Grok Debugger para processar dados não estruturados**
```
```

**Obs: Melhores práticas de uso de pipelines**
```
```

## Segundo laboratorio, consumindo um dataset de filmes json (arquivo de configuração disponivel no github)

**Primeiro Stdout de Teste**
```
```

**Implementando o Plugin Date e indexando no Elasticsearch**
```
```

**Validando via API o resultado**
```
```

