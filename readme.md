# DATASURANCE
👩‍🚒 Esse é o repositório do **Datasurance**, solução desenvolvida pelo time 20 no [FF Hacka](https://ffhacka.com.br/), que nos desafiou a **criar ferramentas que permitam a leitura e captação de dados de documentos para o preenchimento automatizado de apólices**. 

O **Datasurance** é uma plataforma online para subscritores e seguradoras.
Nela, o subscritor **converte documentos**, como PDF, planilhas **e armazena todos os dados na nuvem**. **Conectada com API’s, a plataforma também traz outras informações importantes para o cálculo de risco**, que o subscritor tinha que buscar manualmente na internet, como Score de crédito, processos criminais etc.

A partir dos dados coletados, **o sistema gera um Score de Risco** para a empresa segurada, que pode ser **customizado de acordo com o tipo de risco de cada seguradora**.

Com todos os dados de propostas aceitas e não aceitas armazenados, a Pipesurance apresenta **uma ferramenta para criar Dashboards personalizados**. Possibilitando detalhar quais motivos levaram a recusa/aceitação de cada proposta de seguro.
Dessa forma, a Seguradora consegue ter uma visão ampla do que está acontecendo no tático e pode **tomar decisões estratégicas para atingir outros mercados**.

**Capture, centralize, gerencie. Todos os dados de seguros em um só lugar!**

[![Watch the video](https://i.imgur.com/32dz1ii.png)](https://youtu.be/FNIZ3fMl23o)

## Tecnologias Utilizadas na Codificação

* [Xcode](https://developer.apple.com/xcode/) - IDE para programar em Swift
* [API da Plataforma Digital da Getnet](https://developers.getnet.com.br) - Soluções para facilitar pagamentos  

## Integração com a Plataforma Digital da Getnet
* **Baseada na [documentação da API](https://developers.getnet.com.br/api)**
* **Autenticação** /auth/oauth/v2/token
* **Geração de token para cartão** /v1/tokens/card
* **Pagamento com cartão de crédito** /v1/payments/credit
* **Testes** foram feitos utilizando a **Sandbox da [Plataforma Digital](https://developers.getnet.com.br/login)**

![log de chamadas feitas para a API da Plataforma Digital](https://i.imgur.com/Ba38ZnX.png)

## Ferramentas de Design utilizadas

* [Miro](https://miro.com/) - Ideação e Canvas (Mais voltado para o usuário)
* [Notion](https://www.notion.so/) - Documentação do projeto e Gestão das atividades
* [Figma](https://www.figma.com/) - Prototipação de telas
* [VideoScribe](https://www.videoscribe.co/en) - Editor de vídeo
* [iMovie](https://www.apple.com/imovie/) - Editor de vídeo
* [Keynote](https://www.apple.com/keynote/) - Criação de Slides


## Link com os protótipos

* Protótipo da página web - [Figma](https://www.figma.com/file/SD21QtDxswYP4WcuVbXWLt/Hackathon-FF?node-id=0%3A1)
* Vídeo demo da plataforma - [Youtube](https://youtu.be/xxu2wzYShTU)

## Um pouco sobre a nossa equipe

### Vinicius Schroeder | Business [(Linkedin)](https://www.linkedin.com/in/vinicius-schroeder/)
Alterar bio
### Carlos Schwabe | Development [(Linkedin)](https://www.linkedin.com/in/carlos-schwabe/) [(GitHub)](https://github.com/carlos-schwabe)
Graduado em Engenharia Aeronáutica pela USP, e um apaixonado por tecnologia e empreendedorismo. Desde pequeno é apaixonado por inovação e pretende deixar o mundo um melhor lugar para se viver!
### Flavio Akira Tsukamoto | Design UI/UX [(Linkedin)](https://www.linkedin.com/in/akiratsu/) [(GitHub)](https://github.com/akirapresident)
Envolvido no mundo das startups, busca sempre contribuir com projetos que ajudem a impactar positivamente a sociedade. Com conhecimentos nas áreas de business e design, ajuda a alinhar as necessidades dos usuários com soluções inteligentes. 
### Guilherme Ninov | Development [(Linkedin)](https://www.linkedin.com/in/guilherme-ninov/) [(Github)](https://github.com/GuiNinov)
Alterar Bio
### Vitor Soares | Marketing [(Linkedin)](https://www.linkedin.com/in/vitorsoaresdasilva/)
Alterar Bio
