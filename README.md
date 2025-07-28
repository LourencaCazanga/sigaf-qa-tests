# SIGAF – Repositório de Testes QA

Este repositório contém **todos os testes funcionais e de performance** realizados sobre a plataforma **SIGAF** (Sistema Integrado de Gestão Acadêmica e Filiais), usando as ferramentas **Hoppscotch**, **JMeter** e **Playwright**.

## Módulos Testados
Autentication,
Users, 
Enrollment,
School,
Course,
Academic-Years,
School management

## Como Usar os Arquivos
Hoppscotch ou Postman
Abrir Hoppscotch

Importar o arquivo .json da pasta hoppscotch-collections/

Executar os testes individualmente por endpoint

JMeter
Abrir o JMeter

Carregar o arquivo sigaf-tests.jmx

Executar o teste

Ver o relatório gráfico: sigaf-relatorio-performance.html na pasta jmeter/

## Observações
Os testes de performance simulam múltiplos usuários no endpoint de inscrição.

Tokens são gerados automaticamente para cada execução no JMeter.

Relatórios incluem tempo médio, throughput, percentis e erros detectados.

## Contato
lourencacazanga7@gmail.com

