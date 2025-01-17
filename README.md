# TADS 2022 - Senac

## Descrição do Projeto
O projeto "TADS 2022 - Senac" é um site desenvolvido em React que oferece a oportunidade para alunos das turmas de Analise e Desenvolvimento de Sistemas construírem suas próprias páginas sobre os temas de sua escolha. A ideia principal é criar um ambiente colaborativo onde os alunos possam trabalhar em um único repositório, simulando um ambiente de produção semelhante ao de uma empresa real. Isso visa preparar os alunos para o mercado de trabalho, proporcionando experiência prática em desenvolvimento web e colaboração em equipe.

## Funcionalidades Principais
- **Criação de Páginas:** Cada aluno pode criar sua própria página com conteúdo relacionado ao assunto de sua escolha.
- **Edição Colaborativa:** Os alunos podem convidar outros para editar suas páginas, permitindo colaboração em equipe.
- **Controle de Versões:** O sistema utiliza um sistema de controle de versões para rastrear todas as alterações feitas nas páginas.

## Tecnologias Utilizadas
- **Front-end:** React
- **Controle de Versão:** Git e GitHub

## Instruções de Uso
1. Faça um fork deste repositório. 
   1. Faça o Fork: No canto superior direito da página do repositório, você verá o botão "Fork". Clique nele.
   2. Escolha a Conta para o Fork: Uma janela pop-up será exibida, pedindo que você escolha onde deseja fazer o fork. Escolha sua própria conta do GitHub (ou a organização, se aplicável).
   3. Aguarde o Fork: O GitHub agora criará uma cópia do repositório na sua conta. Isso pode levar alguns segundos.
   4. Você Fez o Fork!: Após a conclusão, você será redirecionado para a página do repositório forkado em sua conta.
      
3. Criar e Trabalhar em uma Branch: Cada aluno clona seu próprio fork para suas máquinas locais e cria uma nova branch para trabalhar em suas alterações:
   1. Faça o clone deste repositório para sua máquina local usando o comando:
      ```bash
      git clone https://github.com/AliePonzani/tads2022.git
      ```
   3. Navegue até o diretório do projeto:
      ```bash
      cd tads2022
      ```
   5. Crie uma nova branch com seu nome, assim fica fácil de lembra, para subir suas alterações:
      ```bash
      git checkout -b SEU_NOME
      ```
   7. Instale as dependências do projeto:
      ```bash
      npm install
      ```
   8. Inicie o servidor de desenvolvimento:
      ```bash
      npm start
      ```
   9. Abra seu navegador e acesse o site em `http://localhost:3000`.

3. Faça suas alterações:
   
   1. Dentro de src/Paginas crie um New File do tipo .jsx com o nome da sua pagina, dentro deste arquivo você irá montar toda a estrutura de sua página, use a PaginaExemplo.jsx como exemplo para iniciar.
   2. Depois de criar sua página vá em src/Paginas/pagesDatas.jsx e crie uma nova rota para sua página seguindo o exemplo que consta lá.
      
4. Faça um commit adicione mensagens de commit significativas:

```bash
git commit -m "SUA MENSSAGEM"
```

5. Envie suas alterações de volta para o repositório forkado:

```bash
git push origin SEU_NOME
```

6. Abra o Pull Request:
   1. Vá para a página do seu fork no GitHub e clique na guia "Pull requests".
   2. Clique no botão verde "New pull request".
   3. Selecione a branch que você acabou de criar no repositório original como destino (geralmente a branch "main" ou "master").
   4. Revise as alterações que você está propondo. Se estiver tudo certo, clique em "Create pull request".
  
7. Descreva o Pull Request:
   1. Dê um título e uma descrição informativa para o seu pull request. Explique o que você fez e por que.
  
8. Envie o Pull Request:
   1. Finalmente, clique em "Create pull request" para enviar o pull request ao repositório original.
  
9. A partir desse ponto, os colaboradores do repositório original terão a oportunidade de analisar suas alterações, oferecer comentários e, se estiverem em conformidade, integrá-las ao repositório principal. Lembre-se de monitorar o pull request para prontamente responder a qualquer feedback que possa ser fornecido.


## Equipe
Este projeto é mantido por uma equipe de alunos dedicados. Sinta-se à vontade para entrar em contato conosco se tiver alguma dúvida ou sugestão.

- [Aline Fernanda Ponzani](https://github.com/AliePonzani) - Desenvolvedor Front-end - Idealizadora deste repositório

## Licença
Este projeto é licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para obter detalhes.

---
