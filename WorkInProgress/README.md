# 246_IntegrandoChatGPTNodeReact
Integrando o ChatGPT com Node e React

###### DESCRIÇÃO

Crie uma aplicação completa utilizando o recurso oficial da OpenAI, a inteligência por trás do chatGPT e crie um front-end clone da ferramenta mais popular do mercado para integrar com um back-end funcional.

**Node.js****React**

------

###### Full-Stack

###### Intermediário

------

###### ESPECIALISTA

![author](https://hermes.dio.me/users/author/photos/e0aa7c57-89e3-41ff-a60b-09dc7a9bc6e9.png)

###### Felipe Aguiar

Tech Educator, DIO[**](https://www.linkedin.com/in/felipe-aguiar-047/) [**](https://github.com/felipeAguiarCode)



# Entendendo o Desafio

 

**Agora é a sua hora de brilhar e construir um perfil de destaque na DIO! Explore todos os conceitos explorados até aqui e replique (ou melhore, porque não?) este projeto prático. Para isso, crie seu próprio repositório e aumente ainda mais seu portfólio de projetos no GitHub, o qual pode fazer toda diferença em suas entrevistas técnicas** 😎

 

**Neste repositório, insira todos os links e arquivos necessários para seu projeto, seja um arquivo de banco de dados ou um link para o template no Figma.**

 

*Dica: Se o expert forneceu um repositório Github, você pode dar um "fork" no repositório dele para organizar suas alterações e evoluções mantendo uma referência direta ao código-fonte original.*

 

 

**COMO ENTREGAR SEU PROJETO:**

\- Recrie o projeto do ChatGPT como apresentado no laboratório, tanto a parte do back-end quanto do front-end;
\- Salve seu projeto no GitHub e envie para gente.

###  

### **Repositório Git**

O Git é um conceito essencial no mercado de trabalho atualmente, por isso sempre reforçamos sua importância em nossa metodologia educacional. Por isso, todo código-fonte desenvolvido durante este conteúdo foi versionado no seguinte endereço para que você possa consultá-lo a qualquer momento:

 

https://github.com/felipeAguiarCode/node-react-chatgpt-clone

###  

### **Links Úteis** 

**Link da plataforma da API para pesquisar documentação:** https://openai.com/blog/chatgpt

 

Replique os ensiamentos do Expert Felipe Aguiar e personalize o seu projeto com a sua identidade. 

 

Bons estudos 😉



[**](https://web.dio.me/play)

##### Integrando o ChatGPT com Node e React

**

[**](https://web.dio.me/lab/integrando-o-chatgpt-com-node-e-react/learning/1305e5c6-a692-4a30-ad70-d62274c1bace)[**](https://web.dio.me/lab/integrando-o-chatgpt-com-node-e-react/learning/4fa92bfc-5782-4082-b5b1-aa0030243f9c)

<iframe id="ytc20" frameborder="0" allowfullscreen="1" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" title="Explicando a Arquitetura" width="100%" height="100%" src="https://www.youtube.com/embed/YQalTSdENKA?controls=0&amp;disablekb=1&amp;enablejsapi=1&amp;fs=0&amp;iv_load_policy=3&amp;modestbranding=1&amp;showinfo=0&amp;rel=0&amp;html5=1&amp;cc_load_policy=0&amp;origin=https%3A%2F%2Fweb.dio.me&amp;widgetid=1" data-gtm-yt-inspected-9="true" style="box-sizing: inherit; max-width: none; float: none; margin: 0px; padding: 0px; border: 0px; font-style: inherit; font-variant: inherit; font-weight: inherit; font-stretch: inherit; line-height: inherit; font-family: inherit; font-optical-sizing: inherit; font-kerning: inherit; font-feature-settings: inherit; font-variation-settings: inherit; font-size: 14px; vertical-align: baseline;"></iframe>



00:07

 

07:33









normal

auto

- CONTEÚDOS
- INFORMAÇÕES

[Introdução a solução integrada](https://web.dio.me/lab/integrando-o-chatgpt-com-node-e-react/learning/1305e5c6-a692-4a30-ad70-d62274c1bace)[Explicando a Arquitetura](https://web.dio.me/lab/integrando-o-chatgpt-com-node-e-react/learning/72ebb7af-c6a8-4caa-be6a-c80de3d28a83)[Criando o server](https://web.dio.me/lab/integrando-o-chatgpt-com-node-e-react/learning/4fa92bfc-5782-4082-b5b1-aa0030243f9c)[Pré requisitos](https://web.dio.me/lab/integrando-o-chatgpt-com-node-e-react/learning/ba749c99-3f30-41c8-9b7d-49fbf0e1cc39)[Instalando dependências do projeto](https://web.dio.me/lab/integrando-o-chatgpt-com-node-e-react/learning/6e1cd35d-b64b-4858-9b1e-568ab0e1f997)[Criando nosso servidor](https://web.dio.me/lab/integrando-o-chatgpt-com-node-e-react/learning/7a2ae0aa-0fb3-4df2-83ce-d9adde9a0af3)[Configurações do ChatGpt](https://web.dio.me/lab/integrando-o-chatgpt-com-node-e-react/learning/029e46f8-973f-4559-8d69-f6eb742cea80)[Criando a controller](https://web.dio.me/lab/integrando-o-chatgpt-com-node-e-react/learning/654345fe-4846-4894-a0a7-85e29a90996a)[Configurando as rotas da sua aplicação](https://web.dio.me/lab/integrando-o-chatgpt-com-node-e-react/learning/0911b9dc-e2f5-41d7-b0ee-bf9448c26d27)[Bora criar o nosso frontend](https://web.dio.me/lab/integrando-o-chatgpt-com-node-e-react/learning/a1ee7650-7a69-481e-8fad-91a950ec740d)[Criando um projeto React](https://web.dio.me/lab/integrando-o-chatgpt-com-node-e-react/learning/82a231a1-488d-45a9-bacf-77a079d23502)[Estruturando seu projeto](https://web.dio.me/lab/integrando-o-chatgpt-com-node-e-react/learning/c3e471f2-8132-4ed4-aafc-a20228e6c175)[Estrutura de codificação](https://web.dio.me/lab/integrando-o-chatgpt-com-node-e-react/learning/075461f9-de3e-4b14-b1de-f31cf5f6992d)[Consumindo nossa API](https://web.dio.me/lab/integrando-o-chatgpt-com-node-e-react/learning/e3db64c2-44d0-4292-82f9-65f959b1ede5)[CSS padronizado](https://web.dio.me/lab/integrando-o-chatgpt-com-node-e-react/learning/79cafb56-b7fd-4edf-88ee-5dcd8bcce27d)[Limpando o App js](https://web.dio.me/lab/integrando-o-chatgpt-com-node-e-react/learning/aa58564e-7312-470e-8477-1f15d38bd74a)[Aside menu](https://web.dio.me/lab/integrando-o-chatgpt-com-node-e-react/learning/5407bed7-b619-40d7-904e-1e09c9a17398)[Criando a base do CSS do APP](https://web.dio.me/lab/integrando-o-chatgpt-com-node-e-react/learning/4e2bdee2-1cb4-4f62-843c-d22a52a2bd51)[Criando componente de mensagem](https://web.dio.me/lab/integrando-o-chatgpt-com-node-e-react/learning/53ab909b-f7da-42ea-9b9c-b39adee396d0)[Usando o SVG Real do ChatGPT](https://web.dio.me/lab/integrando-o-chatgpt-com-node-e-react/learning/783188a4-b09e-4199-8e53-728ffbe0e67f)[Definindo os hooks dos estados que vamos utilizar](https://web.dio.me/lab/integrando-o-chatgpt-com-node-e-react/learning/e386ec9c-1e82-4c08-aa9e-72c25ba1e809)[Implementando o log de chat](https://web.dio.me/lab/integrando-o-chatgpt-com-node-e-react/learning/80f5e125-530b-4a34-a80f-c0917ac27684)[Trabalhando com formulário e prevenção de eventos](https://web.dio.me/lab/integrando-o-chatgpt-com-node-e-react/learning/8e9aaf9d-b6d2-4f83-a876-47c7ebc1846e)[Estilizando a app principal](https://web.dio.me/lab/integrando-o-chatgpt-com-node-e-react/learning/b91e6a6a-8115-4149-bcca-0b899837d231)[Node Watch](https://web.dio.me/lab/integrando-o-chatgpt-com-node-e-react/learning/912c7855-4e7f-4dfb-8ca9-411388dc880e)[Dica de Dev tools e rodando aplicação](https://web.dio.me/lab/integrando-o-chatgpt-com-node-e-react/learning/67fbd373-dffd-49eb-9a93-8f304122f9e0)[Como destacar meu projeto e criar algo totalmente original](https://web.dio.me/lab/integrando-o-chatgpt-com-node-e-react/learning/0c99c3fa-704b-44ce-a540-8a26a89ae268)[Entendendo o Desafio](https://web.dio.me/lab/integrando-o-chatgpt-com-node-e-react/learning/cd4de281-620c-4be6-b84b-0dce2bab2593)



