# Azure - DIO - XP Inc. - Full Stack Developer

## O que é a computação em nuvem?
A computação em nuvem refere-se à virtualização de centros de dados (data centers), proporcionando a entrega de serviços de computação através da internet.

<br>

## Tipos de computação em nuvem

### Nuvem privada
Trata-se de um ambiente computacional dedicado exclusivamente a uma organização específica. A entidade em questão assume a responsabilidade pela operação dos serviços que disponibilizará, sendo a única com acesso autorizado a este ambiente de nuvem.
Nesta configuração, a organização torna-se encarregada da manutenção, do hardware e de outros aspectos relacionados à infraestrutura tecnológica da nuvem.

### Nuvem pública
Em contraste com a nuvem privada, a nuvem pública oferece um ambiente compartilhado por diversas organizações e usuários. Este modelo permite a criação e remoção de sistemas de acordo com as necessidades específicas. A estrutura de cobrança baseia-se em fatores como tempo de utilização, consumo de recursos e localização geográfica. Os usuários são tarifados exclusivamente pelos serviços efetivamente utilizados, considerando a quantidade de máquinas e a duração do uso. Diferentemente da nuvem privada, neste modelo, o usuário não assume a responsabilidade pela gestão integral da infraestrutura.

### Nuvem híbrida
Integra elementos das nuvens pública e privada, oferecendo uma solução flexível que combina os benefícios de ambas as abordagens

<br>

## Tipos de despesas

### CapEx (despesas de capital)
As despesas de capital (CapEx) compreendem os investimentos iniciais em infraestrutura física. Este tipo de despesa geralmente apresenta uma tendência decrescente ao longo do tempo, uma vez que a aquisição de equipamentos não ocorre em uma base mensal.

### OpEx (despesas operacionais)
As despesas operacionais (OpEx) referem-se aos custos mensais associados à utilização de serviços, sendo faturados de acordo com o consumo e de maneira recorrente. Tipicamente, o produto ou serviço é acessado inicialmente, seguido pela faturação correspondente ao uso efetivo.

### Modelo baseado em consumo
O modelo de faturamento baseia-se no consumo efetivo dos recursos. Ilustrando este conceito, consideremos um cenário com duas máquinas: uma utilizada por 15 dias e outra por 30 dias. A cobrança será calculada proporcionalmente à utilização de cada recurso. Consequentemente, serão faturados 15 dias de uso para a primeira máquina e 30 dias para a segunda.

<br>

## Benefícios da Computação em Nuvem

### Alta Disponibilidade

A alta disponibilidade tem como objetivo assegurar o máximo de disponibilidade de um serviço em nuvem, independentemente de interrupções ou eventos adversos. A Microsoft oferece diferentes níveis de disponibilidade em contrato para seus serviços, que são medidos em porcentagens; quanto maior a porcentagem, menor é a probabilidade de o serviço apresentar períodos prolongados de inatividade.

Por exemplo, um Acordo de Nível de Serviço (SLA) de 99% resulta em um tempo de inatividade de até 1,68 horas por semana, enquanto um SLA de 99,999% limita esse tempo a apenas 6 segundos por semana. Caso um incidente ocorra e um sistema ultrapasse o tempo de inatividade estipulado em contrato, a Microsoft proporciona compensação ao cliente na forma de um voucher no mês seguinte, buscando mitigar os impactos da indisponibilidade.

### Escalabilidade

A escalabilidade refere-se à capacidade de ajustar recursos para atender à demanda conforme necessário. Isso significa que você pode adicionar recursos facilmente para gerenciar um aumento na demanda. Um benefício adicional da escalabilidade é que, por se tratar de um modelo de pagamento baseado no consumo, você paga apenas pelos recursos utilizados. Se a demanda diminuir, é possível reduzir os recursos e, consequentemente, os custos. A escalabilidade pode ser entendida como um crescimento vertical.

### Elasticidade

O conceito de elasticidade pode ser ilustrado pela Black Friday, onde a demanda é incerta e as requisições extras são temporárias. Nesse contexto, é possível adicionar máquinas virtuais ou contêineres para expandir a capacidade e, quando a necessidade diminuir, os recursos implantados podem ser reduzidos horizontalmente. A elasticidade, portanto, se caracteriza como um crescimento horizontal.

### Confiabilidade

A descentralização dos sistemas em nuvem permite a implementação em diversas regiões ao redor do mundo, proporcionando uma infraestrutura confiável e resiliente. Mesmo que uma região específica fique fora do ar, outras regiões continuarão operando, permitindo a migração de serviços conforme necessário.

### Previsibilidade

A previsibilidade na nuvem possibilita que as organizações avancem com confiança, tanto em termos de desempenho quanto de custos.

### Segurança

A nuvem oferece diversas ferramentas de segurança que atendem às necessidades dos clientes. No entanto, é fundamental lembrar que a implementação dessas ferramentas deve ser realizada pelo próprio cliente. A responsabilidade pela configuração da segurança não recai sobre a Microsoft, que fornece apenas os recursos necessários para que os processos de segurança sejam aplicados no sistema.

### Governança

A governança na nuvem é utilizada para estabelecer padrões de gestão, assegurando que as diretrizes corporativas sejam seguidas.

### Gerenciabilidade

Um dos principais benefícios da computação em nuvem é a capacidade de gerenciamento. Existem duas abordagens para a gerenciabilidade: através do portal da Azure ou por meio de comandos de linha.
