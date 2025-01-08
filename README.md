# Flutter_banco_douro

## Esse aplicativo foi desenvolvido durante um curso em que participei. No curso foram ensinados:

- O uso do TextEditingController para capturar dados inseridos em campos de texto no Flutter;
- A criação de um objeto Account com os dados capturados e um identificador único;
- A utilização do AccountService para enviar o objeto Account criado para o servidor;
- A implementação de um indicador de carregamento (CircularProgressIndicator) para melhorar a experiência do usuário durante operações assíncronas;
- A desativação de botões usando operadores ternários e a lógica de controle de estado para evitar múltiplos envios.


## Como utilizar o código:

1- Clone o repositório em uma máquina local.
2- Crie um Gist no GitHub com as informações das contas que irão aparecer na lista ou, se preferir, apenas crie o Gist e cadastre as informações diretamente dentro da aplicação.
3- Após criar o Gist, copie o link dele, por exemplo:
    https://gist.github.com/{Nome_do_usuário}/58aae4feaeaeba567f8d46cea82b61f7.
    Em seguida, altere-o para:
    https://api.github.com/gists/58aae4feaeaeba567f8d46cea82b61f7
    (modificando o início do domínio para "api" e removendo o nome do usuário).
4- Copie o link alterado e cole no campo determinado para account_service e transaction_service. Esse Gist será usado como servidor da aplicação.
5- Gere uma API Key (token) no GitHub e adicione-a no código para possibilitar as operações de inserção e atualização no servidor.
6- Rode o comando (flutter pub get) para baixar as dependências do projeto.
7- Certifique-se de ter um emulador Android configurado e rodando.
