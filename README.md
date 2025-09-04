# Integrantes
Vitor Hugo da Silva - RM558961

## Descrição
Este repositório contém as resoluções da atividade prática proposta em sala de aula, envolvendo análise e modelagem de dados de consumo de energia elétrica domiciliar.  

O trabalho consiste em 40 exercícios, divididos em duas etapas:  
- 20 exercícios disponibilizados na aula de 20/08  
- 20 exercícios disponibilizados na aula de 27/08

# Instruções de Entrega
- A atividade pode ser feita em grupo.  
- Apenas um integrante deve submeter a entrega.  
- Não enviar arquivos diretamente, apenas o link do repositório no GitHub.  

# Informações dos Datasets

## Individual Household Electric Power Consumption

Origem e escopo: Contém 2.075.259 medições da energia elétrica consumida em uma única residência, com frequência de 1 minuto, ao longo de aproximadamente 47 meses — de dezembro de 2006 a novembro de 2010 — em Sceaux, nos arredores de Paris, França 

Tarefas associadas: ideal para regressão e clustering em séries temporais 

Número de variáveis: 9 variáveis, todas do tipo contínuo (real) 

- Date (data, dd/mm/yyyy)
- Time (horário, hh:mm:ss)
- Global_active_power (potência ativa global – kW)
- Global_reactive_power (potência reativa global – kW)
- Voltage (voltagem média – V)
- Global_intensity (corrente global média – A)
- Sub_metering_1 (Wh, cozinha)
- Sub_metering_2 (Wh, lavanderia)
- Sub_metering_3 (Wh, aquecimento ou ar-condicionado)

## Appliances Energy Prediction

Origem e escopo: Contém 19 735 instâncias, com medições a cada 10 minutos, ao longo de aproximadamente 4,5 meses. Inclui registros de sensores ZigBee de temperatura e umidade, além de dados meteorológicos do aeroporto de Chievres, Bélgica 

Tarefa associada: Regressão em séries temporais multivariadas 

Número de variáveis: 28 variáveis contínuas e inteiras 

Entre elas:
- date (timestamp)
- Appliances (consumo de aparelhos, Wh) – alvo (target)
- lights (consumo de iluminação, Wh)
- Temperatura e umidade em vários cômodos (T1 a T9, RH_1 a RH_9)
- Dados meteorológicos externos: temperatura externa (T_out), pressão, umidade externa (RH_out), velocidade do vento, visibilidade, ponto de orvalho (Tdewpoint)
- Duas variáveis aleatórias (rv1 e rv2) adicionadas para testes de modelos e filtragem de atributos não preditivos 
