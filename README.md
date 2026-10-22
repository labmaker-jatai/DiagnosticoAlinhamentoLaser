# Diagnóstico do Corte a Laser

## Descrição do projeto

Este projeto tem como objetivo avaliar a capacidade de corte de máquinas a laser Delta CNC, identificando as combinações de **potência (intensidade do laser) e velocidade de corte** mais adequadas para o processamento de materiais.

O arquivo de teste contém **100 configurações diferentes**, combinando intensidades de corte entre 55% e 100% e velocidades entre 2 e 11. A execução do teste permite verificar quais combinações de potência e velocidade são capazes de realizar o corte completo do material, auxiliando na identificação dos parâmetros de operação mais eficientes para a máquina.

## Arquivos disponíveis

- **[`teste.wcvr`](https://github.com/labmaker-jatai/diagnosticoalinhamentolaser/blob/main/teste.wcvr)** – Arquivo compatível com o software AutoLaser, utilizado no controle das máquinas de corte a laser Delta CNC.
- **[`teste.dxf`](https://github.com/labmaker-jatai/diagnosticoalinhamentolaser/blob/main/teste.dxf)** – Arquivo vetorial em formato DXF, que pode ser utilizado em máquinas de corte a laser compatíveis com esse formato e que utilizem outros softwares de controle.

## Como utilizar

1. Abra o arquivo correspondente ao software controlador da máquina.
2. Prepare o material que será utilizado no teste, garantindo que esteja adequadamente posicionado na área de corte.
3. Execute o teste e observe os resultados de cada combinação de intensidade e velocidade.
4. Identifique quais configurações produziram cortes completos e quais não foram suficientes para atravessar o material.

## Resultados esperados

Ao final do procedimento, será possível identificar as combinações de intensidade e velocidade que permitem realizar cortes completos no material testado. Esses resultados servem como referência para a configuração dos parâmetros de corte da máquina.

**Observação:** os resultados podem variar conforme o material, sua espessura, o estado de conservação e o alinhamento óptico da máquina. Este teste avalia principalmente a capacidade de corte para diferentes parâmetros de operação, não substituindo procedimentos específicos de verificação do alinhamento óptico do laser.
