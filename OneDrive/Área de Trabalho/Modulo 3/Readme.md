# *Fun4Study*
O Fun4Study é um sistema de estudo e cadastro de estudantes, onde é possível realizar o cadastro de cidades, cadastrar alunos, cadastrar novas senhas, exibir dados dos estudantes e exibir dados das cidades.

# *Funcionalidades*
- Cadastrar cidades
- Cadastrar alunos
- Cadastrar nova senha para estudantes
- Exibir dados dos estudantes
- Exibir dados das cidades

# *Como usar*
Faça o clone deste repositório para o seu ambiente local.
Abra o projeto em sua IDE favorita.
Compile e execute o arquivo "TesteFun4Study.java".
Siga as instruções apresentadas no console para interagir com o sistema.

# *Estrutura do projeto*

# Classe Estudante
A classe Estudante representa um estudante e possui os seguintes atributos:

- codigo: código do estudante (inteiro)
- nome: nome do estudante (String)
- dataNascimento: data de nascimento do estudante (String)
- email: email do estudante (String)
- senha: senha do estudante (String)
- cidade: objeto da classe Cidade que representa a cidade do estudante
qntEstudantes: objeto da classe Cidade que representa a quantidade de estudantes

# *A classe Estudante possui os seguintes métodos:*
- Estudante(int codigo, String nome, String dataNascimento, String email, String senha, Cidade cidade, Cidade qntEstudantes): construtor da classe Estudante
- Estudante(): construtor vazio da classe Estudante
- Métodos getters e setters para os atributos
- exibeDados(): exibe os dados do estudante

# Classe Cidade
A classe Cidade representa uma cidade e possui os seguintes atributos:

- codigo: código da cidade (inteiro)
- descricao: descrição da cidade (String)
- uf: unidade federativa da cidade (String)
- qntEstudantes: quantidade de estudantes da cidade (inteiro)

# *A classe Cidade possui os seguintes métodos:*

- Cidade(int codigo, String descricao, String uf): construtor da classe Cidade
- Cidade(): construtor vazio da classe Cidade
- Métodos getters e setters para os atributos
- adicionaNovoEstudante(int qntEstudantes): adiciona um novo estudante à quantidade de estudantes da cidade
- ExibeDados(): exibe os dados da cidade

# *Classe TesteFun4Study*
A classe TesteFun4Study é a classe principal que contém a lógica do sistema e a interação com o usuário. Ela possui os seguintes métodos:

- main(String[] args): método principal que inicia a execução do sistema
