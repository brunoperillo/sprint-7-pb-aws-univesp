# Avaliação Sprint 7 - Programa de Bolsas Compass UOL / AWS e Univesp

Avaliação da sétima sprint do programa de bolsas Compass UOL para formação em machine learning para AWS.


***

*Capa em desenvolvimento*

## Introdução 

Nessa Sprint, vimos o curso Alexa Skill Builder para inciantes com conceitos, ferramentas e práticas para criar Skills e o Amazon Conect que é uma solução da AWS.

## Objetivo 

Criar um chatbot utilizando o Amazon Lex V2 e conectar a uma plataforma de mensageria. (apos o grupo escolher mencionar aqui)

*O que são Chatbots ?*

É um programa de computador que tenta simular um ser humano na conversação com as pessoas. Objetivo é responder as perguntas de tal forma que as pessoas tenha a impressão de estar conversando com *outra pessoa* e não com um progama de computador. Tornar o suporte ou atendimento mais humanizado. 

*O que seria Amazon Lex?*

É um serviço da AWS para criação de interfaces de conversa (chatbots) para aplicativos de voz e texto utilizando o mecanismo de conversa da plataforma do Amazon Alexa. Através da funcionalidades de compreensão de linguagem natural (NLU) e o reconhecimento automático de fala (ASR) para permitir a criação de experiências de usuário. 

Nosso chatboot foi desenvolvindo para  ajudar 

## Configurações inicial do chatbot 

Nome: ChatBot Miguel

Voz de saída : Cristiano

Tempo limite da sessão: 5 minutos

Análise de sentimento: Não

Opções avançadas : Não

# Sample utterrances 

*imagem*



Este bot usará quatro slots, três usando tipos integrados e um slot personalizado chamado ....
Defina os três slots iniciais da seguinte maneira:


*imagem*


*desenvolvendo*
Função do chatbot é de livre escolha do desenvolvedor

## Crie e teste o ChatBot Miguel
Nesta seção, você testará seu ChatBot.

Para construir seu bot, clique no crie bot no canto superior direito.
Quando a compilação estiver concluída, teste-a na janela do chatbot.
Você deve ver uma conversa como a abaixo.


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

- Entendimento do chatbot e o que ele soluciona;


- Criatividade em relação ao tema escolhido para o desenvolvimento do chatbot;


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


