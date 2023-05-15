# Avaliação Sprint 6 - Programa de Bolsas Compass UOL / AWS e Univesp

Avaliação da [Sprint 7][sprint7main] do Programa de Bolsas [Compass UOL][compass] para formação em *machine learning* com [AWS][aws].
***

<div align="center">
  <img src="https://github.com/Compass-pb-aws-2023-Univesp/sprint-7-pb-aws-univesp/assets/88354075/1e26160b-2a37-49ec-98f8-aab0cb457212" alt="capa github" width="450"/>
</div>


## **Objetivo**

Este projeto consiste no desenvolvolvimento de um **chatbot** utilizando o **Amazon Lex v2**, e foi criado com o objetivo de operacionalizar a orientação de triagem de pacientes na Recepção de uma unidade de saúde (postinho, UPA, hospital). O mascote do chatbot recebeu o nome de Miguel.

## **Introdução** 

A inteligência artificial tem um potencial enorme de transformar a os serviço e o atendimento no setor de saúde. As possibilidades são infinitas, abrangendo áreas como o desenvolvimento de novos medicamentos, análise preditiva, melhor alocação de recursos e a melhoria do diagnóstico e do cuidado médico como um todo.
Nesse aspecto, compreendida a necessidade de mudanças e implementações para a melhorar funcionalidades de sistemas, o uso chatbots pode por exemplo ajudar a reduzir esse tempo de espera, fornecendo informações e orientações preliminares antes que o paciente seja visto por um profissional de saúde. 
Chatbots são portanto ferramentas muito úteis para operacionalizar e dar agilidade ao atendimento ao público, e vem sendo amplamente utilizados neste sentido.


*O que são chatbots ?*

É um programa de computador que tenta simular um ser humano na conversação com as pessoas. O objetivo é que ele consiga responder as perguntas de tal forma que as pessoas tenham a impressão de estar conversando com *outra pessoa* e não lidando um programa de computador. Isto torna o suporte ou atendimento mais humanizado e natural. 

*O que seria Amazon Lex?*

É um serviço da AWS para criação de interfaces de conversa (chatbots) para aplicativos de voz e texto, podendo ainda utilizar o mecanismo de conversa da plataforma do Amazon Alexa. Através da funcionalidades de processamento de linguagem natural (NLP) e o reconhecimento automático de fala (ASR) para permitir a criação de experiências de usuário. 

Nosso chatboot foi desenvolvindo para  ajudar. 

## **Configurações inicial do chatbot** 

Nome: TriagemAtendimento
Avatar/Mascote: Chatbot Miguel
Voz de saída: Somente texto
Tempo limite da sessão: 5 minutos
Análise de sentimento: Não

## *Intents utterrances* 

*imagem*



Este bot usará quatro slots, três usando tipos integrados e um slot personalizado chamado ....
Defina os três slots iniciais da seguinte maneira:


*imagem*


*desenvolvendo*
Função do chatbot é de livre escolha do desenvolvedor

## Teste o ChatBot Miguel

1. Clone o repositório do chatbot do GitHub para o seu ambiente local.

2. Certifique-se de ter as dependências necessárias instaladas, como o AWS CLI (Command Line Interface).

3. Faça login na sua conta da AWS usando o AWS CLI, se ainda não estiver conectado. Você pode usar o comando aws configure para fornecer suas credenciais.

4. Crie um novo bot no Amazon Lex no console da AWS ou use um bot existente.
5. No diretório do seu repositório clonado, navegue até a pasta que contém os arquivos do bot (geralmente em um formato JSON).

6. Use o AWS CLI para criar ou atualizar o bot no Amazon Lex. 


Substitua "NomeDoBot" pelo nome do seu bot e "caminho/para/arquivo.json" pelo caminho correto para o arquivo JSON do seu bot no seu ambiente local.

7. Após a criação ou atualização do bot, você pode começar a testá-lo usando o console do Amazon Lex. Navegue até o console do Lex na AWS e encontre o seu bot.

8. No console do Lex, você pode iniciar uma conversa com o bot e enviar mensagens para testar suas respostas.

Quando a compilação estiver concluída, teste-a na janela do chatbot.

Você deve ver uma conversa como a abaixo.

*imagem*


*desenvolver*
- Conexões: O chatbot deve ser disponibilizado em uma das seguintes plataformas:  
  - Slack - [Conexão Slack](https://docs.aws.amazon.com/pt_br/lex/latest/dg/slack-bot-association.html);  
  - Web - [Web](https://github.com/aws-samples/aws-lex-web-ui);



- Construção:   
  - Intents:    
    - O chatbot deve possuir ao menos 4 intents distintas;  
  - Slots:    
    - Captação de informações presentes no texto;    
    - Solicitação de informações quando o slot não for reconhecido;    
    - Confirmação de informações;    
    - O chatbot deve captar ao menos 3 slots no decorrer do fluxo;
- O chatbot deve utilizar-se de menu com botões (Response Cards);
- Tratamento de erros (fallback);
- (Opcional) Uso de conditional branching para controle de fluxos ([Doc Conditional Branching](https://docs.aws.amazon.com/pt_br/lexv2/latest/dg/paths-branching.html));

***



- Projeto em produção na AWS; 

## Entendimento do chatbot e o que ele soluciona

![Diagram - Account ownership diagram](https://github.com/Compass-pb-aws-2023-Univesp/sprint-7-pb-aws-univesp/assets/88354075/debdccc8-8c43-49d2-9538-10b934f1ef48)

- Criatividade em relação ao tema escolhido para o desenvolvimento do chatbot;

![imagem_chatbotMiguel](https://github.com/Compass-pb-aws-2023-Univesp/sprint-7-pb-aws-univesp/assets/88354075/3711d3df-f6d3-434f-b305-98f22cb987e8)

O Chatbot Miguel foi criado através de imagens geradas pela Intengencia Artifical do aplicativo Canva e nome doi dado pela equipe. 

- Intents e slots criados e informações que eles se dispõem a obter;


- Organização:  
  - Estrutura de intenções;  

  - Estrutura da lógica de negócio;  

  - Divisão de responsabilidades da equipe;  

 


- Objetividade do README.md.

***


- Subir o trabalho na branch com um README.md;

  - Documentar detalhes sobre como a avaliação foi desenvolvida;

  - Dificuldades conhecidas;

  Entender a sequencia nas mensagens 




  - Como utilizar o sistema;

  

  - Export do bot Lex em formato .zip;

*Em análise pelo grupo*

  Funcionalidade do chatbot:

  O chatbot Miguel para um pronto socorro, aqui estão algumas habilidades que podemos considerar incluir no chatbot para pronto socorro:

Triagem de Emergências: O chatbot pode fazer perguntas para avaliar a gravidade da situação, determinar a urgência do caso e fornecer as orientações apropriadas.

Direcionamento de Pacientes: Com base nas informações fornecidas pelo usuário, o chatbot pode direcionar os pacientes para a área correta do pronto socorro, como trauma, pediatria ou sala de espera.

Primeiros Socorros: O chatbot pode fornecer instruções básicas de primeiros socorros para ajudar os usuários a lidar com lesões ou condições de emergência enquanto esperam por ajuda profissional.

Informações sobre Condições Comuns: O chatbot pode fornecer informações sobre sintomas, causas e tratamentos de condições médicas comuns, como resfriados, gripes, cortes, entre outros.

Localização e Contato: O chatbot pode fornecer informações sobre a localização do pronto socorro, horários de funcionamento e números de telefone de contato para emergências ou dúvidas não urgentes.

Perguntas Frequentes: O chatbot pode responder a perguntas frequentes sobre os serviços disponíveis no pronto socorro, exames, procedimentos, cobertura de seguro e outras informações relevantes.

Acompanhamento de Pacientes: O chatbot pode ajudar a acompanhar o progresso dos pacientes, fornecer lembretes de medicação ou agendamento de consultas de acompanhamento.

Feedback e Avaliações: O chatbot pode coletar feedback dos usuários sobre a experiência no pronto socorro, ajudando a identificar áreas de melhoria e fornecendo informações para a gestão do hospital.

É importante adaptar as habilidades do chatbot às necessidades específicas do seu pronto socorro, levando em consideração os recursos disponíveis e as prioridades de atendimento.

------------- 
## Intents e Slots
O chatbot possui 4 intents distintas:

Intent de Boas-Vindas: Apresenta um menu de opções para o usuário.
Intent de Marcar Consulta: Solicita informações sobre a consulta e confirma os dados para finalizar o agendamento.
Intent de Informações Sobre o Hospital: Fornecer informações úteis sobre o hospital.
Intent de Atendimento de Emergência: Solicita informações sobre a emergência e pode direcionar o usuário para a equipe de atendimento.
O chatbot utiliza slots para capturar informações, como especialidade médica, nome do paciente, data e horário da consulta e tipo de emergência.

## Organização
O projeto foi desenvolvido em equipe, com a divisão de responsabilidades entre os integrantes. A estrutura de intenções e a lógica de negócio foram pensadas de forma a garantir uma boa experiência do usuário. O README.md foi escrito de forma objetiva e clara para facilitar a compreensão do projeto.

## Dificuldades Conhecidas
Durante o desenvolvimento do projeto, a equipe enfrentou algumas dificuldades em relação à integração do chatbot com o canal de comunicação. Além disso, foi necessário estudar e entender as funcionalidades do Amazon Lex V2 para a criação das intents e slots.

## Ferramentas utilizadas
- Amazon Lex

- Lucid.app

- VSCode

*Verificar essa informação*
Export do Bot Lex
O bot Lex pode ser exportado em formato .zip e se encontra na pasta 'exported-bot' deste repositório.
----------


## Desenvolvedores do projeto
| [<img src="https://avatars.githubusercontent.com/u/25699466?v=4" width=115><br><sub>Bruno Monserrat Perillo</sub>](https://github.com/brunoperillo)  |  [<img src="https://avatars.githubusercontent.com/u/78061851?v=4" width=115><br><sub>BCarlos Roberto de Souza Camilo</sub>](https://github.com/crobertocamilo) | [<img src="https://avatars.githubusercontent.com/u/88354075?v=4" width=115><br><sub>Kelly Patricia Lopes Silva</sub>](https://github.com/KellyPLSilva)  | [<img src="https://avatars.githubusercontent.com/u/87142990?v=4" width=115><br><sub>Luciene Godoy</sub>](https://github.com/LucieneGodoy) | [<img src="https://avatars.githubusercontent.com/u/72028902?v=4" width=115><br><sub>Luiz Renato Sassi</sub>](https://github.com/luizrsassi) |
| :---: | :---: | :---: |:---: |:---: |

***
   [compass]: <https://compass.uol/en/home/>
   [aws]: <https://aws.amazon.com/pt/>
   [sprint7main]: https://github.com/Compass-pb-aws-2023-Univesp/sprint-7-pb-aws-univesp>
