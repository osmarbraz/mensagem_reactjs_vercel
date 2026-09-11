# Programa servidor API-REST de mensagens utilizando Node.js no Vercel.

## Descrição

- O projeto foi desenvolvido no VSCode deve ser chamado "mensagem_nodejs_vercel".
- Programa cliente está no projeto "mensagem_reactjs_vercel".
- Programa servidor cria o webservice na posta 5173.
- Implementação do serviço utilizando REST e os métodos GET e POST.
- Classe Mensagem possui duas operações: setMensagem e getMensagem.
- A pasta src contêm os fontes do projeto.

## Execução

   <pre><code>npm run dev</code></pre>
   
## Atualização

   Caso o diretório "node_modules" tenha sido apagado basta executar o comando npm a seguir para recriar a pasta e os arquivos das dependências.
   <pre><code>npm update</code></pre>  

## Arquivos do projeto em src

- index.js - Programa principal com o servidor Express.
- mensagem.js - Contêm a classe da Mensagem.
- mensagemrecurso.js - Contêm os métodos de acesso aos recursos da mensagem.
- servicos.js - Contêm as rotas aos métodos de acesso a mensagem.

## Vercel

   https://mensagem-nodejs-vercel.vercel.app/