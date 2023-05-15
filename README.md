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

## *Intents* 

Num chatbot, uma *Intent* é uma representação de uma ação que um usuário deseja executar ou de uma informação que o usuário deseja obter. É um componente chave na construção de chatbots baseados em linguagem natural, pois ajuda a identificar o que o usuário está tentando dizer ou solicitar,  e assim fornercer a resposta adequada. A imagem acima mostra a lista de *intents* do chatbot Miguel e uma descrição do serviço que ela trata.

<div align="center">
  <img src="https://github.com/Compass-pb-aws-2023-Univesp/sprint-7-pb-aws-univesp/blob/grupo-2/asset/Lista_intents_decricao.png" alt="Lista de Intents" width="90%"/>
</div>


## *Utterrances*

Uma *intent* processa o diálogo com o usuário a partir de *utterances*, que são palavras ou frases pré-programadas de como o usuário poderá interagir com o chatbot.

<div align="center">
  <img src="https://github.com/Compass-pb-aws-2023-Univesp/sprint-7-pb-aws-univesp/blob/grupo-2/asset/Exemplo_utterances.png" alt="Exemplos de Utterances width="70%"/>
</div>

## *Slots*

A captação/leitura de informações e dados fornecidos pelo usuário é feita a partir de *slots*, que podem ter tipo pré-definidos (nome, número, email) ou podem ser criados pelo desenvolvedor definindo os valores possíveis para seu tipo de *slot*.

<div align="center">
  <img src="https://github.com/Compass-pb-aws-2023-Univesp/sprint-7-pb-aws-univesp/blob/grupo-2/asset/Tela_bot5.png" alt="Exemplo slots width="80%"/>
</div>

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

<div align="center">
  <video src="[seu_video.mp4](https://github.com/Compass-pb-aws-2023-Univesp/sprint-7-pb-aws-univesp/blob/grupo-2/asset/Video_bot.mp4)" controls width="240" height="360"></video>
</div>




## Diagrama de funcionamento do Chatbot Miguel

![Diagrama - final](https://github.com/Compass-pb-aws-2023-Univesp/sprint-7-pb-aws-univesp/assets/88354075/b1893533-9f4e-4c09-ad7f-0a8ea42209b1)

## Deploy do chatbot na *slack*



## Organização
O projeto foi desenvolvido em equipe, com a divisão de responsabilidades entre os integrantes. A estrutura de intenções e a lógica de negócio foram pensadas de forma a garantir uma boa experiência do usuário. O README.md foi escrito de forma objetiva e clara para facilitar a compreensão do projeto.

## Dificuldades Conhecidas
Durante o desenvolvimento do projeto, a equipe enfrentou algumas dificuldades em relação à integração do chatbot com o canal de comunicação. Além disso, foi necessário estudar e entender as funcionalidades do Amazon Lex V2 para a criação das intents e slots.

## Ferramentas utilizadas
- Amazon Lex
- Lucid.app
- VSCode
- Slack


## Export do Bot Lex
O bot Lex pode ser exportado em formato .zip e se encontra na pasta 'exported-bot' deste repositório.

----------


## Desenvolvedores do projeto
| [<img src="https://avatars.githubusercontent.com/u/25699466?v=4" width=115><br><sub>Bruno Monserrat Perillo</sub>](https://github.com/brunoperillo)  |  [<img src="https://avatars.githubusercontent.com/u/78061851?v=4" width=115><br><sub>Carlos Roberto Camilo</sub>](https://github.com/crobertocamilo) | [<img src="https://avatars.githubusercontent.com/u/88354075?v=4" width=115><br><sub>Kelly Patricia Lopes Silva</sub>](https://github.com/KellyPLSilva)  | [<img src="https://avatars.githubusercontent.com/u/87142990?v=4" width=115><br><sub>Luciene Godoy</sub>](https://github.com/LucieneGodoy) | [<img src="https://avatars.githubusercontent.com/u/72028902?v=4" width=115><br><sub>Luiz Renato Sassi</sub>](https://github.com/luizrsassi) |
| :---: | :---: | :---: |:---: |:---: |

***
   [compass]: <https://compass.uol/en/home/>
   [aws]: <https://aws.amazon.com/pt/>
   [sprint7main]: https://github.com/Compass-pb-aws-2023-Univesp/sprint-7-pb-aws-univesp>
  
