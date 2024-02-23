# Conflito em Arquivos

## Problema 01

1. Aqui o index.html foi modificado. Inicialmente foi criado um index.html apenas com a estrutura padrão do arquivo.
2. Posteriormente foi criada uma nova branch à partir da branch master (ou main) chamada `helloWorld` e foi adicionado um parágrafo com a mensagem "Hello World!".
3. Após, foi realizado commit e push da branch `helloWorld` para o repositório remoto.
   1. Os comandos executados até aqui foram
   2. ```bash
      git checkout -b helloWorld
      git add index.html
      git commit -m "Adicionando Hello World!"
      git push origin helloWorld
      ```
    3. O comando `git checkout -b helloWorld` cria uma nova branch chamada `helloWorld` e muda para ela.
    4. Então, o texto "Hello World!" foi adicionado ao arquivo index.html.
    5. Em seguida, o comando `git add index.html` adiciona o arquivo index.html ao stage. O arquivo está agora pronto para ser comitado na branch `helloWorld`.
    6. O comando `git commit -m "Adicionando Hello World!"` realiza o commit do arquivo index.html na branch `helloWorld`.
4. Posteriormente, o desenvolvedor mudou para a branch master (ou main) e criou uma nova branch a partir dela, agora chamada `introducaoProblema`.
5. Na branch `introducaoProblema` foi adicionado um parágrafo com a mensagem "Introdução do Problema"
6. Após, foi realizado commit e push da branch `introducaoProblema` para o repositório remoto.
   1. Os comandos necessários foram
   2. ```bash
      git checkout master
      git checkout -b introducaoProblema
      git add index.html
      git commit -m "Adicionando Introdução do Problema"
      git push origin introducaoProblema
      ```
    3. O comando `git checkout -b introducaoProblema` cria uma nova branch chamada `introducaoProblema` e muda para ela.
    4. Então, o texto "Introdução do Problema" foi adicionado ao arquivo index.html.
    5. Em seguida, o comando `git add index.html` adiciona o arquivo index.html ao stage. O arquivo está agora pronto para ser comitado na branch `introducaoProblema`.
    6. O comando `git commit -m "Adicionando Introdução do Problema"` realiza o commit do arquivo index.html na branch `introducaoProblema`.
 7. Agora vem o problema!
    1. 