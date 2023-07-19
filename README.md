## Exercicio 00 - Git e Gihub 

Primeiramente, faça um fork deste repositório clicando no botão "Fork" no canto superior direito da página. Isso criará uma cópia do repositório em sua conta do GitHub.

Em seguida, clone o repositório para o seu computador utilizando o seguinte comando no terminal (substitua <seu-username> pelo seu nome de usuário no GitHub):

```bash
git clone https://github.com/<seu-username>/hello-world.git
```

No diretório recém-clonado, crie um novo arquivo de texto (por exemplo, mensagem.txt) e abra-o com o visual studio code ou um editor de texto de sua preferência.
Dentro do arquivo mensagem.txt, adicione a seguinte mensagem:

Hello, World!

Após adicionar a mensagem, salve o arquivo e adicione-o ao stage do Git utilizando o seguinte comando:

```bash
git add mensagem.txt
```

Agora, faça o commit das mudanças com uma mensagem descritiva:

```bash
git commit -m "Adicionada a mensagem de Hello, World!"
```

Por fim, envie as alterações para o seu repositório remoto no GitHub:

```bash
git push origin main
```
