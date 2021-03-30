# Desafio TRACTIAN
## Análise espectral de vibrações

Em coleta/, há 20 arquivos .csv que representam as coletas de vibrações de um compressor de uma geladeira, realizadas pelo dispositivo construído pela TRACTIAN "band-aid", com menos de 1 minuto cada coleta, de 1 em 1 hora.

O nome do arquivo possui o timestamp em EPOCH: (Epoch do Início)-(Epoch do Fim da coleta).csv, respectivamente. O arquivo possui 4 colunas, x, y, z e c. Para esse desafio você vai desconsiderar a última coluna C, que é a temperatura em celsius.

E os dados de vibração (que são coletados por um acelerômetro) são apresentados da seguinte forma:

X = aceleração no eixo x, em m/sˆ2
Y = aceleração no eixo y, em m/sˆ2
Z = aceleração no eixo z, em m/sˆ2


Desafios (em Python):

* Fazer a Análise Espectral (fft e harmônicos) da geladeira e identificar padrões entre coletas;

* Fazer um Algoritmo que calcula automaticamente quanto tempo a geladeira ficou ligada (uptime) e quanto tempo ela ficou desligada (downtime).

* Fazer sua análise sobre a condição do compressor da geladeira, está desbalanceado? Desalinhado? Que condição se encontra.