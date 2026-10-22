# Diagnóstico do Alinhamento do Laser Delta CNC

Este projeto foi desenvolvido para **avaliar o desempenho e o alinhamento do sistema de corte a laser da máquina Delta CNC**, realizando testes com diferentes combinações de intensidade e velocidade de corte.

## Objetivo

O teste permite identificar quais configurações de **potência (intensidade)** e **velocidade** são capazes de produzir cortes satisfatórios no material utilizado, facilitando o diagnóstico e a calibração da máquina.

## Metodologia

O arquivo de teste utiliza diferentes combinações de parâmetros:

- **Intensidade de corte:** de 55% a 100%;
- **Velocidade de corte:** de 2 a 11;
- **Total:** 100 combinações diferentes de intensidade e velocidade.

Ao executar o teste, a máquina realiza cortes correspondentes a cada configuração. Após a execução, é possível analisar os resultados e identificar **quais combinações de intensidade e velocidade são mais adequadas para realizar o corte**.

Esse procedimento pode auxiliar na identificação de problemas de alinhamento, regulagem ou desempenho do sistema de corte a laser.

## Arquivo de teste

O arquivo [`teste.wcvr`](https://github.com/labmaker-jatai/diagnosticoalinhamentolaser/blob/main/teste.wcvr) contém o desenho e as configurações utilizadas no teste e é compatível com o software **AutoLaser**.

## Resultado esperado

Ao final do procedimento, é possível determinar a faixa de configurações em que a **Delta CNC** apresenta capacidade de realizar cortes, fornecendo uma referência para a regulagem da máquina e para a escolha dos parâmetros de corte.
