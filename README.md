## Exercicio 00 - Git e Gihub 

Primeiramente, faça um fork deste repositório clicando no botão "Fork" no canto superior direito da página. Isso criará uma cópia do repositório em sua conta do GitHub.

Em seguida, clone o repositório para o seu computador utilizando o seguinte comando no terminal (substitua <seu-username> pelo seu nome de usuário no GitHub):

```bash
git clone https://github.com/<seu-username>/hello-world.git
```

No diretório recém-clonado, crie um novo arquivo de texto com o seu nome completo separando por _ underline (por exemplo, Ygor_Guilherme.txt) e abra-o com o visual studio code ou um editor de texto de sua preferência.
Dentro do arquivo Ygor_Guilherme.txt, adicione a seguinte mensagem:

Hello, World!

Após adicionar a mensagem, salve o arquivo e adicione-o ao stage do Git utilizando o seguinte comando:

```bash
git add Ygor_Guilherme.txt
```

Agora, faça o commit das mudanças com uma mensagem descritiva:

```bash
git commit -m "Criado o arquivo Ygor_Guilherme.txt e adicionada a mensagem de Hello, World!"
```

Por fim, envie as alterações para o seu repositório remoto no GitHub:

```bash
git push origin main
```

Ao realizar o push, vá até a página do repositório no GitHub e clique no botão "Compare & pull request". Preencha o formulário de pull request, descrevendo as alterações feitas e clique em "Create pull request" para enviar a sua contribuição.

Parabéns! Você concluiu o processo de contribuição utilizando o Git. 
