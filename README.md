# Kafka UI
Kafka UI was created to provide a very simple interface to manually produce messages onto a Kafka topic. It's sorta like <a href="https://www.getpostman.com/">Postman</a> but for Kafka. 

<div style="float: left;">
<img style="float: left;" src="https://raw.githubusercontent.com/kevincardona/kafka_ui/master/public/preview1.png" width="49%"></img>
<img style="float: left;" src="https://raw.githubusercontent.com/kevincardona/kafka_ui/master/public/preview2.png" width="49%"></img>
</div>

Kafka UI was created using <a href="https://electronjs.org/">Electron</a>.

## Dependencies
In order to setup and run Kafka UI you must have a node package manager installed

## Running
To install dependencies `yarn install`<br>
To run Kafka UI `yarn start`<br>
To build a binary `yarn dist`<br>
To push a release `yarn ship`<br>