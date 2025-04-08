# Site de Avaliação de Serviços de Empresas

Este projeto é um site desenvolvido em HTML e CSS, onde usuários podem avaliar os serviços de diversas empresas. Ele permite que os visitantes deixem feedback sobre serviços específicos, ajudando outros a tomarem decisões informadas sobre as empresas.

## Framework Escolhido

Para este projeto, optariamos por utilizar o **Bootstrap** como framework CSS. A escolha do Bootstrap foi motivada pela sua facilidade de uso, componentes prontos e design responsivo, o que facilita a criação de um layout atrativo e funcional sem a necessidade de um grande esforço de design. O Bootstrap também é amplamente utilizado, o que facilita a colaboração e a manutenção do código no futuro.

### Justificativa para o uso do Bootstrap:
- **Responsividade**: O Bootstrap oferece uma estrutura de design que se adapta automaticamente a diferentes tamanhos de tela, garantindo uma boa experiência de usuário em dispositivos móveis, tablets e desktops.
- **Componentes prontos**: O Bootstrap vem com vários componentes prontos para serem usados, como botões, formulários e alertas, o que acelera o desenvolvimento.
- **Documentação excelente**: O framework tem uma documentação muito completa, o que facilita a aprendizagem e o uso.

## Instalação e Execução

Para começar a usar o projeto localmente, siga as etapas abaixo.

### Pré-requisitos

- **Editor de código**: Recomendamos usar o [Visual Studio Code](https://code.visualstudio.com/).
- **Navegador**: Um navegador moderno, como Google Chrome ou Firefox.
  
### Passos para Instalação

1. **Clone o repositório**:

   No terminal ou prompt de comando, clone o repositório para o seu ambiente local:

   ```bash
   git clone https://github.com/seu-usuario/avaliacao-servicos.git
   ```

2. **Abra o projeto no editor de código**:

   Navegue até a pasta do projeto e abra-a no seu editor de código preferido.

3. **Instale as dependências (se necessário)**:

   O projeto utiliza o Bootstrap via CDN, portanto não há necessidade de instalar dependências adicionais. No entanto, se preferir, você pode baixar os arquivos locais do Bootstrap e incluí-los manualmente.

4. **Execute o projeto**:

   Para executar o projeto, basta abrir o arquivo `index.html` diretamente no seu navegador. Não há necessidade de servidor backend para este projeto simples.

### Dependências do Projeto

Este projeto depende apenas do **Bootstrap 5** via CDN, que é incluído diretamente nos arquivos HTML. Se você quiser adicionar outras bibliotecas ou dependências no futuro, pode instalar via [npm](https://www.npmjs.com/).

```html
<!-- Inclusão do Bootstrap via CDN -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css" rel="stylesheet">
```

## Procedimento para Deploy

O deploy do projeto em um ambiente de produção pode ser feito facilmente utilizando serviços de hospedagem estática como **GitHub Pages**, **Netlify** ou **Vercel**. Vamos demonstrar como fazer o deploy utilizando o **GitHub Pages**.

### Deploy no GitHub Pages

1. **Crie um repositório no GitHub**:
   
   - Vá até o [GitHub](https://github.com/), faça login e crie um novo repositório para o projeto.

2. **Faça o push do código para o repositório**:

   - No terminal, navegue até o diretório do seu projeto e execute os seguintes comandos:

   ```bash
   git init
   git add .
   git commit -m "Primeiro commit"
   git remote add origin https://github.com/seu-usuario/avaliacao-servicos.git
   git push -u origin master
   ```

3. **Ativar o GitHub Pages**:

   - Vá até o repositório do projeto no GitHub.
   - Clique em "Settings" no menu superior.
   - Role até a seção "GitHub Pages".
   - Em "Source", escolha a opção `main` ou `master` branch (dependendo de como você nomeou sua branch principal).
   - Após alguns minutos, o GitHub Pages disponibilizará o site na URL informada.

### Deploy no Netlify

1. **Acesse o Netlify**:

   - Vá até [Netlify](https://www.netlify.com/) e crie uma conta ou faça login.

2. **Conecte seu repositório GitHub**:

   - Após o login, clique em "New Site from Git".
   - Escolha o GitHub e autorize o Netlify a acessar seu repositório.
   - Selecione o repositório do projeto.

3. **Configure o deploy**:

   - O Netlify detectará automaticamente que se trata de um site estático e não precisará de configurações adicionais.
   - Clique em "Deploy Site" e aguarde o processo ser concluído.

4. **Acesse seu site**:

   - O Netlify fornecerá uma URL onde seu site estará disponível. Você pode personalizar o domínio, se necessário.

## Contribuição

Sinta-se à vontade para contribuir para este projeto. Caso tenha sugestões ou melhorias, basta abrir um pull request ou uma issue. Estamos abertos a feedbacks!

## Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para mais detalhes.
