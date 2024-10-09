## Desafio Hands On: **Página de Receita Simples**

## 📋 Descrição do Projeto
Você foi contratado(a) para criar uma página web simples de uma receita de cozinha. O objetivo é praticar `HTML` e `CSS`, criando uma estrutura básica de página com estilos básicos aplicados.

![Receita 3](https://github.com/user-attachments/assets/cbf8fd5c-0bbe-4078-8c45-3c97868c05d9)

## ✅ Critérios de Aceitação

**Estrutura HTML:**

   - Crie uma página chamada `receita.html`.
   - Insira um título para a página: "Receita: Bolo de Chocolate".
   - Insira um cabeçalho principal (`h1`) com o nome da receita: "Bolo de Chocolate".
   - Crie uma seção para os **ingredientes**, utilizando uma lista não ordenada (`ul`), com pelo menos 5 ingredientes.
   - Crie uma seção para o **modo de preparo**, utilizando uma lista ordenada (`ol`), com pelo menos 5 etapas.
   - Adicione um parágrafo final com uma dica extra para a receita: "Dica: Para deixar o bolo mais fofinho, bata bem os ovos antes de adicionar à massa."
  
**Estilização com CSS:**
   - Crie um arquivo CSS chamado `styles.css` e vincule-o à página HTML.
   - Aplique uma cor de fundo clara na página inteira.
   - Centralize o texto do cabeçalho principal (`h1`).
   - Deixe a fonte do texto da lista de ingredientes em negrito.
   - Aplique um espaçamento maior entre as etapas do modo de preparo.
   - A dica extra deve estar em itálico e de uma cor diferente do restante do texto.

 **Bônus:**
   - Adicione uma imagem relacionada à receita (por exemplo, uma foto de um bolo de chocolate) logo abaixo do cabeçalho principal.
   - A imagem deve ter um tamanho fixo de 300px de largura e estar centralizada na página.



### Git e GitHub:
- Uso de comandos do Git: `git add`, `git commit`, `git pull`, `git push`.
- Gerenciamento de repositórios no GitHub (clone e fork).


## 🛠 Instruções para Trabalhar 

### 1. Fork do Repositório
   - Um "fork" é uma cópia de um repositório que fica no seu perfil GitHub. Você faz um fork para ter uma versão própria do projeto na qual você pode trabalhar. Isso permite que você modifique e experimente o código sem afetar o repositório original.
 
#### Como forkar?

[Como fazer um fork](https://github.com/campinho-digital/Como-fazer-um-Fork)  


### 2. Após o Fork

- Clonar o Repositório Forkado
  
Abra o terminal ou o Git Bash em seu computador.


### Clone o repositório forkado para o seu computador com o seguinte comando:

~~~javascript
git clone seu_repositorio
~~~


### Navegue até a pasta do repositório clonado:

~~~javascript
cd seu_repositorio
~~~

#### ⚠️ Atenção 

Quando você clona um repositório, o Git cria uma nova pasta no seu sistema contendo todos os arquivos e a estrutura do projeto. Para trabalhar com esse projeto (editar arquivos, rodar scripts, instalar dependências, etc.), você precisa estar dentro dessa pasta. Se não navegar para essa pasta, você estará em uma localização diferente no seu sistema e os comandos que tentar rodar (como npm install ou git) não funcionarão corretamente, pois eles precisam ser executados no diretório correto.


### 3. Instalar Dependências
Se o projeto utiliza npm, você deve instalar as dependências:

~~~javascript
npm install

~~~

#### ⚠️ Atenção 
Se o projeto utiliza o Node.js e tem um arquivo `package.json`, você precisa rodar `npm install` para instalar todas as bibliotecas e dependências que o projeto necessita para funcionar. Sem isso, o projeto pode não rodar corretamente.


### 4. Rodando o projeto

- Vá até a pasta do projeto no terminal ou prompt de comando.
- Digite o seguinte comando no terminal
  
~~~javascript
npm start
~~~

- Isso irá rodar o comando `"start": "lite-server"` que está configurado no package.json. O `lite-server` vai automaticamente:

- Criar um servidor local.
- Abrir o seu navegador padrão.
- Carregar o arquivo index.html do seu projeto.



### 5. Versionamento com Git
Depois de implementada a solução e adicionar comentários ao código, você precisa versionar essas alterações usando o Git.

Quando você estiver trabalhando em dupla, é fundamental usar o Git para controlar as versões do projeto de forma organizada e eficiente. Isso ajuda a evitar conflitos de código e facilita a colaboração. 


## **Boa sorte e bom código!** 🚀📘

