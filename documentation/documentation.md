# Documentation

## Variables

| Column | Description | Type | Changes | 
|-|-|-|-|
| UF | Unidade da Federação | categorical | int -> string |
| CAPITAL | Capital | categorical | float -> string |
| RM_RIDE | Região Metropolitana e Região Administrativa Integrada de Desenvolvimento | categorical | float -> string |
| V1008 | Número de seleção do domicílio | discrete ||
| V1012 | Semana no mês | categorical | int -> string |
| V1013 | Mês da pesquisa | categorical | int -> string |
| V1016 | Número da entrevista no domicílio | discrete ||
| Estrato | Subdivisão da população em grupos homogêneos com base em características específicas. | categorical | int -> string |
| UPA | Unidade primária de amostragem | categorical | int -> string |
| V1022 | Situação do domicílio: 1-Ubana; 2-Rural | categorical | int -> string |
| V1023 | Tipo de área | categorical | int -> string |
| V1030 | Projeção da população | discrete||
| V1031 | Peso mensal com correção de não entrevista sem pós estratificação pela projeção de população | continuous ||
| V1032 | Peso mensal com correção de não entrevista com pós estratificação pela projeção de população | continuous ||
| posest | Domínios de projeção - As 2 primeiras posições representam o código da Unidade da Federação, a terceira, o sexo do morador e a última, a faixa etária do morador. UF(2) + A003(1) + Faixa Etária com base na A002(1) | discrete |  int -> string |
| A001 | Número de ordem | discrete ||
| A001A | Condição no domicílio - cônjuge, filho, genro, etc.| categorical | int -> string |
| A001B1 | Dia de nascimento | discrete ||
| A001B2 | Mês de nascimento | discrete ||
| A001B3 | Ano de nascimento | discrete ||
| A002 | Idade do morador | discrete ||
| A003 | Sexo: 1-Homem; 2-Mulher | categorical | int -> string |
| A004 | Cor ou raça:<br> 1-Branca; 2-Preta; 3-Amarela; 4-Parda; 5-Indígena; 6-Ignorado | categorical | int -> string |
| A005 | Escolaridade: <br> 1-Sem instrução; 2-Fundamental incompleto; 3-Fundamental completa; 4-Médio incompleto; 5-Médio completo; 6-Superior incompleto; 7-Superior completo; 8-Pós-graduação, mestrado ou doutorado | categorical | int -> string |
| A006 | Frequenta escola: 1-Sim; 2-Não | categorical | float -> string |
| A007 |Na semana passada, ____ foram disponibilizadas atividades escolares para realizar em casa? | categorical | float -> string |
| B0011 | Na semana passada teve febre? | categorical | int -> string |
| B0012 | Na semana passada teve tosse? | categorical | int -> string |
| B0013 | Na semana passada teve dor de garganta? | categorical | int -> string |
| B0014 | Na semana passada teve dificuldade para respirar? | categorical | int -> string |
| B0015 | Na semana passada teve dor de cabeça? | categorical | int -> string |
| B0016 | Na semana passada teve dor no peito? | categorical | int -> string |
| B0017 | Na semana passada teve náusea? | categorical | int -> string |
| B0018 | Na semana passada teve nariz entupido ou escorrendo? | categorical | int -> string |
| B0019 | Na semana passada teve fadiga? | categorical | int -> string |
| B00110 | Na semana passada teve dor nos olhos? | categorical | int -> string |
| B00111 | Na semana passada teve perda de cheiro ou sabor? | categorical | int -> string |
| B00112 | Na semana passada teve dor muscular? | categorical | int -> string |
| B00113 | Na semana passada teve diarreia? | categorical | int -> string |
| B002 | Por causa disso, foi a algum estabelecimento de saúde? | categorical | float -> string |
| B0031 | Providência tomada para recuperar dos sintomas foi ficar em casa | categorical | float -> string |
| B0032 | Providência tomada para recuperar dos sintomas foi ligar para algum profissional de saúde | categorical | float -> string |
| B0033 | Providência tomada  para recuperar dos sintomas foi comprar e/ou tomar  remédio por conta própria | categorical | float -> string |
| B0034 | Providência tomada para recuperar dos sintomas foi comprar e/ou tomar remédio por orientação médica | categorical | float -> string |
| B0035 | Providência tomada para recuperar dos sintomas foi receber visita de algum profissional de saúde do SUS (equipe de saúde da família, agente comunitário, etc.) | categorical | float -> string |
| B0036 | Providência tomada para recuperar dos sintomas foi receber visita de profissional de saúde particular  | categorical | float -> string |
| B0037 | Providência tomada para recuperar dos sintomas foi outra | categorical | float -> string |
| B0041 | Local que buscou atendimento foi posto de saúde/Unidade básica de saúde /Equipe de Saúde da Família (médico, enfermeiro, técnico de enfermagem ou agente comunitário de saúde) | categorical | float -> string |
| B0042 | Local que buscou atendimento foi pronto socorro do SUS/UPA | categorical | float -> string |
| B0043 | Local que buscou atendimento foi hospital do SUS | categorical | float -> string |
| B0044 | Local que buscou atendimento foi ambulatório ou consultório privado ou ligado às forças armadas | categorical | float -> string |
| B0045 | Local que buscou atendimento foi pronto socorro privado ou ligado às forças armadas | categorical | float -> string |
| B0046 | Local que buscou atendimento foi hospital privado ou ligado às forças armadas | categorical | float -> string |
| B005 | Ao procurar o hospital, teve que ficar internado por um dia ou mais | categorical | float -> string |
| B006 | Durante a internação, foi sedado, entubado e colocado em respiração artificial com ventilador | categorical | float -> string |
| B007 | Tem algum plano de saúde médico, seja particular, de empresa ou de órgão público | categorical | int -> string |
| B008 | O(A) Sr(a) fez algum teste para saber se estava infectado(a) pelo coronavírus?  | categorical | int -> string |
| B009A | Fez o exame coletado com cotonete na boca e/ou nariz (SWAB)? | categorical | float -> string |
| B009B | Qual o resultado? | categorical | float -> string |
| B009C | Fez o exame de coleta de sangue através de furo no dedo? | categorical | float -> string |
| B009D | Qual o resultado? | categorical | float -> string |
| B009E | Fez o exame de coleta de sangue através da veia da braço? | categorical | float -> string |
| B009F | Qual o resultado? | categorical | float -> string |
| B0101 | Algum médico já lhe deu o diagnóstico de diabetes? | categorical | int -> string |
| B0102 | Algum médico já lhe deu o diagnóstico de hipertensão? | categorical | int -> string |
| B0103 | Algum médico já lhe deu o diagnóstico de asma/bronquite/enfisema/doenças respiratória crônica ou doença de pulmão? | categorical | int -> string |
| B0104 | Algum médico já lhe deu o diagnóstico de doenças do coração (infarto, angina, insuficiência cardíaca, arritmia)? | categorical | int -> string |
| B0105 | Algum médico já lhe deu o diagnóstico de depressão? | categorical | int -> string |
| B0106 | Algum médico já lhe deu o diagnóstico de câncer? | categorical | int -> string |
| B011 | Qual foi o resultado do teste?  Na semana passada, devido à pandemia do Coronavírus, em que medida o(a) Sr(a) restringiu o contato com as pessoas? | categorical | int -> string |
| C001 | Na semana passada, por pelo menos uma hora, trabalhou ou fez algum bico? | categorical | float -> string |
| C002 | Na semana passada, estava temporariamente afastado de algum trabalho? | categorical | float -> string |
| C006 | Tem mais de um trabalho | categorical | float -> string |
| C007 | No trabalho (único ou principal) que tinha nessa semana, era: | categorical | float -> string |
| C007B | Tem carteira de trabalho assinada ou é funcionário público estatutário? | categorical | float -> string |
| C007C | Que tipo de trabalho, cargo ou função você realiza no seu trabalho (único ou principal)? | categorical | float -> string|
| C007D | Qual é a principal atividade do local ou empresa em que você trabalha? | categorical | float -> string|
| C008 | Quantas horas, por semana, normalmente trabalhava? | continuous ||
| C009 | Quantas horas, na semana passada, de fato trabalhou? | continuous ||
| C01011 | Número da faixa do rendimento/retirada em dinheiro | categorical | float -> string |
| C01012 | Valor em dinheiro | continuous ||
| C011A11 | Número da faixa do rendimento/retirada em dinheiro | categorical | float -> string |
| C011A12 | Valor em dinheiro | continuous ||
| C012 | Na maior parte do tempo, na semana passada, esse trabalho (único ou principal) foi exercido no mesmo local em que costuma trabalhar? | categorical | float -> string |
| C014 | O(A) Sr(a) contribui para o INSS?  | categorical | float -> string |
| C015 | Na semana passada ___ tomou alguma providência efetiva para conseguir trabalho? | categorical | float -> string |
| C016 | Qual o principal motivo de não ter procurado trabalho na semana passada? | categorical | float -> string |
| C017A | Embora você não tenha procurado trabalho, gostaria de ter trabalhado na semana passada? | categorical | float -> string |
| D0011 | Rendimento recebido de aposentadoria e pensão por todos os moradores | categorical | int -> string |
| D0013 | Somatório dos valores recebidos | continuous ||
| D0021 | Rendimento de pensão alimentícia, doação ou mesada em dinheiro de pessoa que não morava no domicílio | categorical | int -> string |
| D0031 | Rendimentos de Programa Bolsa Família | categorical | int -> string |
| D0041 | No mês de ... (mês de referência), ... recebeu rendimentos de Benefício Assistencial de Prestação Continuada – BPC-LOAS? | categorical | int -> string |
| D0051 | Auxílios emergenciais relacionados ao coronavirus | categorical | int -> string |
| D0053 | Somatório dos valores recebidos | continuous ||
| D0061 | Seguro desemprego | categorical | int -> string |
| D0071 | Outros rendimentos, como aluguel, arrendamento, previdência privada, bolsa de estudos, rendimentos de aplicação financeira etc. | categorical | int -> string |
| E001 | Durante o período da pandemia alguém deste domicílio solicitou algum empréstimo? | categorical | int -> string |
| F001 | Este domicílio é: | categorical | int -> string |
| F002A1 | No seu domicílio há os seguintes itens básicos de limpeza e proteção: sabão ou detergente | categorical | int -> string |
| F002A2 | No seu domicílio há os seguintes itens básicos de limpeza e proteção: álcool 70% ou superior (gel ou líquido) | categorical | int -> string |
| F002A3 | No seu domicílio há os seguintes itens básicos de limpeza e proteção: máscaras | categorical | int -> string |
| F002A4 | No seu domicílio há os seguintes itens básicos de limpeza e proteção: luvas descartáveis | categorical | int -> string |
| F002A5 | No seu domicílio há os seguintes itens básicos de limpeza e proteção: água sanitária ou desinfetante | categorical | int -> string |
| F0061 | Quem respondeu ao questionário? | categorical | int -> string|
| F006 | Número de ordem do morador que prestou as informações | discrete | float -> int|
| region | Brazilian federal regions | categorical | |
| had_symptom | Each respondent had 1 or more symptoms | bolean ||
| positive_test | Tested positive for COVID-19 in at least 1 type of test | bolean ||
