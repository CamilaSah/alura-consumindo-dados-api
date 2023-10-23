![Front-end-JavaScript](https://github.com/CamilaSah/alura-consumindo-dados-api/assets/128820692/4d450b49-520e-4480-9480-8cecf2c1c376)
![Static Badge](https://img.shields.io/badge/Status-Conclu%C3%ADdo-%2391DCFF)


<h1>Consumindo API do ViaCEP com o fetch API</h1>
Neste projeto será consumida a API do ViaCEP para que o nome da rua, o nome da cidade e o estado sejam puxados automaticamente quando o usuário colocar o CEP no formulário de cadastro.
Os scripts serão desenvolvidos em um projeto já construído com html e css, que é o formulário de cadastro de usuários.

## :hammer: Funcionalidades do projeto
- `Preencher os campos do endereço automaticamente`: quando o usuário digitar o CEP e clicar fora, os campos de rua, bairro, cidade e estado serão preenchidos automaticamente.

## 📁 Acesso ao projeto
Você pode acessar o projeto clicando [aqui](https://alura-consumindo-dados-api.vercel.app/).

## ✔️ Técnicas e tecnologias utilizadas

Técnicas utilizadas:
- ``Método fetch``: é um método assíncrono e tem como parâmetro obrigatório a URL da API.
- ``Método then()``: foi utilizado para acessar o valor retornado do fetch API.
- ``Método json()``: foi utilizado para converter dados em JSON.
- ``Método catch()``: foi utilizado para lidar com possíveis erros.
- ``Método finally()``:  foi utilizado para enviar respostas independente do retorno.
- ``Método map()``: de instâncias de Array cria um novo array preenchido com os resultados da chamada de uma função fornecida em cada elemento do array de chamada.
- ``async/await``: construir funções assíncronas.
- ``Try/catch``: tratar erros.
- ``Promise``: promessa dizendo que algo vai acontecer no código. Neste caso, caso o CEP digitado seja válido (resolve), os campos de endereço serão preenchidos automaticamente. Caso não seja, aparecerá uma mensagem de erro (reject).
- ``Promise All``: implementar várias requisições simultaneamente.
- ``Template string (${})``: Como criar textos dinâmicos.
- ``Função getElementById()``: faz uma busca do elemento pelo ID.
- ``Função setTimeOut()``: faz acontecer algo depois de um certo tempo que definirmos.
- ``Função addEventListener()``: permite chamar funções quando ocorre alguma interação do usuário em específico.
- ``Evento focusout``: é acionado assim que o elemento perde o foco.
- ``element.innerHTML``: esta propriedade obtém ou altera qualquer elemento no HTML. Neste caso, inseriu a mensagem de erro.
- ``Propriedade value``: incluir valores em elementos.

Tecnologias e ferramentas utilizadas:
- ``Visual Studio Code``: editor de código.
- ``Chrome``: navegador utilizado para teste.
- ``HTML``: fazer a estrutura semântica da página.
- ``CSS``: fazer os estilos da página.
- ``JavaScript``: adicionar o dinamismo e as atualizações de programação, a lógica na página.
- ``DevTools``: utilizamos a aba “Console”, no qual podemos executar qualquer código JavaScript, além de nos ajudar a desenvolver, a entender o nosso código e ver como os erros são apresentados.
- ``Git``: ferramenta de controle de versão de seu arquivo, projeto ou código. 
- ``GitHub``: plataforma para gerenciar seu código e criar um ambiente de colaboração entre devs (permite compartilhamento de código através da criação de repositórios), utilizando o Git como sistema de controle.
- ``Vercel``: colocar o projeto no ar e compartilhar com o mundo.

## 📚 Mais informações do curso
Gostou do projeto e quer conhecer mais? Você pode acessar o curso que me ajudou a desenvolver o projeto desde o começo! 
Busque na plataforma da Alura o curso da escola Front-end:
- [JavaScript: consumindo e tratando dados de uma API](https://cursos.alura.com.br/course/javascript-consumindo-tratando-dados-api).

Esse curso faz parte da formação [Desenvolva aplicações Web com JavaScript](https://cursos.alura.com.br/formacao-javascript-front-end-v663575) da Alura

# Autores

| <img src="https://github.com/CamilaSah/site-pessoal/assets/128820692/bed790ab-3722-4503-8fed-c786e774661b" width="100"><br>[<sub>Camila Sayuri Tokubo</sub>](https://www.linkedin.com/in/camila-tokubo/)|
| :---: |
