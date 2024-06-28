# Projeto de Circuitos Eletrônicos
Este repositório contém o código-fonte e a documentação para um Sistema de Estufa de Hortaliça com sensor de temperatura. O projeto foi proposto pela DIO através da conclusão do módulo de Circuitos Elétricos, na formação Especialista em IoT. Foi simulado pelo TinkerCad e todo o processo foi programado na linguagem C.

# Componentes 
* Protoboard mini;
* Sensor de temperatura TMP36;
* Buzina;
* Resistor;
* Diodo emissor de luz (LED) vermelho;
* Arduíno uno R3.

# Funcionalidade
O sistema fornece a leitura da temperatura a cada segundo, com isso, caso a temperatura seja igual ou maior a 35 ºC, um LED vermelho e uma buzina acionem avisando a situação de emergência.

# Configurando o sistema
Para configurar o sistema, siga este passo a passo:

1. No simulador, busque pelo arduíno, protoboard, sensor de temperatura, LED, resistor e a buzina;
2. Conecte a pontência 5V, o GND e o A0 nos pinos apropriados na protoboard para fazer a ligação com as três portas do sensor;
3. Conecte a porta 10 com qualquer pino na protoboard para fazer a ligação no resistor e no lado positivo do LED;
4. Conecte um cabo GND no lado negativo do LED;
5. O lado positivo da buzina se conectará com qualquer porta digital e o lado negativo com o GND.

![Circuito Eletrônico](https://github.com/eusaruca/projeto_de_circuitos_eletronicos/assets/144628825/f02603df-1b6f-492e-8cce-3dc7b16a2dde)
                              *Figura*: Simulação do sensor de temperatura e uma buzina para alarme.

Após configurar o sistema, faça a programação na linguagem C para que, caso a temperatura seja igual ou maior a 35 ºC, um LED vermelho e uma buzina acionem avisando a situação de emergência.

# Uso
Para usar o sistema, siga este passo a passo:

1. Assim que programar, clique em: Iniciar Simulação;
2. Para verificar se está funcionando corretamente, clique em cima do sensor de temperatura e mude-a para maior que 35 ºC;
3. Se o LED vermelho acender e a buzina começar a tocar, o sistema estará funcionando corretamente.

# Contribuindo
Contribuições são sempre bem-vindas. Se encontrar algum problema ou tiver alguma sugestão de melhorias, faça uma solicitação pull.

# Agradecimentos
Obrigado a DIO por permitir que seus alunos explorem e adquirem conhecimentos através do conteúdo enriquecedor.

# Contato
Para quaisquer dúvidas ou perguntas, entre em contato com: sarahreis.contato@gmail.com





