# Desafio técnico Axion

## API para o teste de pessoas desenvolvedoras!

Este projeto foi criado com o objetivo de testar as habilidade técnicas, capacidades de aprendizado e como um candidato(a) a desenvolvedor(a) lida com os desafios propostos!

Queremos que você clone este projeto, rode ele localmente e se comunique com a API para coletar os dados e compor as páginas.

> Tá, mas como usar a API? Como ela foi feita? E o banco de dados?

Como citamos no arquivo que mandamos com o teste, a API foi desenvolvida em Node.Js utilizando Strapi, por isso a tarefa de criar um usuário e realizar login ficará mais fácil! 

Dê uma olhada na documentação do Strapi e no que dizem nos fórums de dúvida por ai. Já que utilizamos **NodeJs (>=14)**, você vai precisar tê-lo instalado em sua máquina também!

Para executar o servidor você vai precisar:
- abrir o terminal na pasta onde você clonou a API;
- rodar o comando `npm install` para instalar as dependências do projeto;
- rodar o comando `npm run build` para gerar a build do projeto;
- rodar o comando  `npm run develop` para executar a aplicação em modo de **desenvolvimento**;

Se tudo deu certo, você deve ver no console as informações do servidor headless.

E ai boa, a API está rodando na sua máquina!

Na API deverá configurar as Collections para que sejam a representação dos dados de Pessoas, Comidas e Locais. Que deverão ser retornados em arrays em json, sendo que cada objeto representa um item que deve aparecer na lista.

Os objetos estarão no formato:
```json
{
  "name": "",
  "link": ""
}
```

O campo 'name' é o dado a ser colocado sobre a imagem nos itens das listas. O campo 'link" é uma url para a imagem que deve ficar no background do card daquele item na lista. Estes links só funcionarão caso o servidor esteja rodando.

Estes dados estão todos salvos em um banco local SQLite que já se comunica com a API, portanto você não precisa se preocupar com essa parte.

O banco já possui também um usuário cadastrado com as seguintes credenciais:

    user: axioner@axion.company
    senha: Axioner123

Se você travar, lembre-se que outras pessoas já passaram pelo mesmo problema que você, deve ter algo lá nos fóruns/stackoverflow que te ajude a resolver a treta, não desista! You can do this!

## ESPECIFICAÇÕES DE LAYOUT:

Layout do protótipo para o teste: https://marvelapp.com/35gh79g
  
No link a seguir https://bit.ly/3oIQyCC dentro da pasta "imgs" você encontra todos os arquivos que servirão de imagem de fundo para os cards das páginas de lista. Encontra também uma pasta nomeada "assets" e essa você deve copiar para o seu projeto do front para ter a imagem de fundo que usamos no layout e alguns ícones também.

Seria interessante a ordenação crescente e decrescente dos dados de cada Collection no Front-end. Mas isto fica a seu encargo.

Os códigos em hexa das cores que usamos no layout:

        #4A4A4A
        #AE23A9
        #DC4E1B
        #9B9B9B
        #FFFFFF
        #F9F9F9

A fonte usada no layout (repare que existem textos usando a versão Light, Semibold e Bold): https://fonts.google.com/specimen/Open+Sans
