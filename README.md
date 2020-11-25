# Teste para candidatos à vaga de desenvolvedor Front-end


Este é um teste utilizado pela Jogga para avaliação técnica dos candidatos 
as nossas vagas de Front-end. Este modelo de teste é aplicado para todos os níveis de candidatos a Front-end, mudando o nosso critério de avaliação do resultado do teste de acordo com a vaga que você esteja se candidatando.

Portanto não precisa se preocupar caso esteja se candidatando para uma vaga mais iniciante, pois o seu projeto será avaliado baseado no nível da vaga a qual você está concorrendo, basta fazer o seu melhor!


## Instruções

Você deverá criar um repositório público para o projeto no Github. Use o README principal do seu repositório para nos contar como você desenvolveu o seu teste e nele você deverá contar as suas decisões tomadas, o porque de cada tecnologia escolhida por você e como organizou e separou o seu código. As instruções de como rodar seu projeto também devem estar presentes no README.

Não existe uma resposta correta para o teste. Você pode alcançar o objetivo de várias maneiras possíveis e o que será avaliado será a maneira, métodos e tecnologias que você escolheu para finalizar o desafio.

Não há um tempo definido para a conclusão do teste, porém estimamos que este desafio possa ser resolvido em cerca de 16 horas de codificação. Ao concluir o teste você deve responder este e-mail com o link do repositório para que possamos dar uma conferida.

## Desafio

Você será responsável por construir a próxima Landing Page que será utilizada na Jogga, para isso disponibilizamos um arquivo do Adobe XD com o projeto para que você possa seguir e utilizar os seus elementos. É uma landing page simples, onde iremos possuir as informações referente a Jogga, um formulário para envio do lead e um carrosel com imagens da empresa.

* *Situação fícticia, criada apenas para elucidar o desafio, o conteúdo desenvolvido nesse teste será utilizado apenas para fins da avaliação do candidato.*

## O que nós esperamos do seu teste

* Utilize a tecnologia ou framework da melhor forma possível (metodologia/estrutura). 

* Validação dos dados inseridos no formulário.

* Tambér ver a utilização de dependency managers (npm, yarn) para instalação de bibliotecas utilizadas no projeto (Exemplo: Owl Carousel, Tiny Slider).

* Automação de tasks com **gulp**, **grunt** ou outra ferramenta de sua escolha (não possuímos exigência por qual utilizar, porém utilizamos o **gulp** na Jogga).

* Um HTML escrito da maneira mais semântica possível (HTML5/5.1).

* CSS - Com um pré processador de CSS (fica sua escolha, porém utilizamos  o **SASS** na Jogga).

* Layout responsivo.

* Utilização do **Bootstrap** para montagem do GRID ou outra solução de sua preferência (exemplo **Foundation**, **Tailwind**, **Materialize**).

* O formulário deve possuir como campos obrigatórios Nome(*name*), E-mail(*email*), Telefone(*phone*) e o campo Negócio(*observation*) como opcional.

* Desenvolver método para submissão do formulário, este deverá ser uma requisção do tipo **POST**, enviando os parâmetros *name*, *phone*, *email*, *observation* e um parâmetro *code* que não será visivel para o usuário da página mas que será enviado na requisição.


## Breakpoints sugeridos para responsividade

| Nome do breakpoint     | Largura mínima  | Descrição                         |
|------------------------|-----------------|-----------------------------------|
| phone                  | 320px           | Breakpoint para smartphones       |   
| tablet                 | 768px           | Breakpoint para tablets           |   
| desktop                | 1024px          | Breakpoint para desktops comuns   |   
| monitor                | 1280px          | Breakpoints para desktops grandes |   


## Material

* [Link](https://s3-sa-east-1.amazonaws.com/jogga.com.br/talentos/frontend.xd) para download do arquivo do Adobe XD do projeto.  
* [Responsividade](https://developer.mozilla.org/pt-BR/docs/desenvolvimento_web/Responsive_Web_design)

## Pontos extras

* [BEM naming convention](http://getbem.com/naming/).
* Deploy da aplicação (Heroku, Bucket estático S3, etc).
* Se durante a implementação você identificar alguma funcionalidade que torne o resultado mais interessante, funcional ou seguro pode ficar a vontade em acrescentar e depois explicar sua ideia. 

## O que nós não gostaríamos

* Descobrir que não foi você quem fez seu teste
* Ver commits grandes, sem muita explicação nas mensagens em seu repositório
* Encontrar um commit com as dependências de NPM, Bower ou Yarn

## O que avaliaremos de seu teste

* Histórico de commits do git
* As instruções de como rodar o projeto
* Organização, semântica, estrutura, legibilidade, manutenibilidade do seu código
* Alcance dos objetivos propostos
* Adaptação mobile (layout responsivo)
* Componentização e extensibilidade dos componentes Javascript

**Importante**: *Usamos o mesmo teste para todos os níveis de front-end: junior, pleno ou senior, mas procuramos adequar nossa exigência na avaliação com cada um desses níveis sem, por exemplo, exigir excelência de quem está começando.*

