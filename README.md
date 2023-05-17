# **Projeto Escola API - POS - Jeciane Araújo**

## Descrição do sistema:
### D.BASE:

- Escola – Deve fazer cadastro de alunos, professores e turmas. A Escola deve interagir com a Biblioteca para indicar quais usuários são alunos ou professores, de maneira que eles possam pegar uma quantidade maior de livros emprestados.

- Biblioteca – Sua principal função é realizar empréstimos de livros a usuários. Para isto, são necessários cadastros de livros e usuários. A Biblioteca é um serviço independente da Escola, de maneira que qualquer pessoa pode pedir livros emprestados. No entanto, professores e alunos podem pegar uma quantidade maior de livros emprestados. Assim, a Biblioteca deve pedir informações sobre os usuários à Escola para saber se são professores, alunos ou usuários comuns.

- Autenticação – Serviço de autenticação de usuários da Escola e da Biblioteca. Este é o único serviço responsável por armazenar credenciais (login, senha, chaves de acesso…) e fazer autenticação dos usuários (log in, log out). Será usado pela Escola e pela Biblioteca para autenticar seus usuários.

### D.1:
> Dependências:
O projeto foi criado com os seguintes auxiliadores:
- PHP;
- Laravel;
- Composer.

### D.2:
> Como rodar ?:
##### Para poder executar o projeto Escola_POS é necessário seguir as instruções abaixo:
- Faça o download dos arquivos do projeto
- Abra o CMD do seu PC e inclua o diretório onde a pasta do projeto está localizada.
- Após isso, insira o comando __php artisan serve__
##### Com o comando dado, irá ser retornado um link. Abra ele no navegador de sua prefrência e note que ele ainda não está completo, mas já possui algumas funcões como:
> "/"
#### string JSON contendo __{“hello_url” : “/hello”}__.
> "/hello"
#### string __Hello, World!__
