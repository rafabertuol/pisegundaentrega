# Projeto Integrador: Desenvolvimento de Sistemas Orientado a Objetos - 2ª Entrega
Repositório destinado ao trabalho Projeto Integrador do SENAC. O grupo contém 7 integrantes:

- Guilherme Pires Maruiti
- Naara Nunes de Melo Marinheiro 
- Paola Akemi Silva
- Rafaela Acácia Gonçalves
- Rafaela Bertuol
- Samara de Paiva Lacerda
- Thiago Diego Duarte de Sousa de Pieri

## Objetivo
O projeto consiste em apresentar protótipos de interface de um sistema de gestão escolar, de acordo com diagramas de caso de uso desenvolvidos na primeira etapa do projeto. 

## Caso de uso 1: fazer login no sistema
- O ator "Pessoa Física" (professor, aluno ou funcionário) acessa a página de login do sistema, insere as credenciais (matrícula e senha) e o sistema valida as credenciais. Se forem válidas, o ator é autenticado e tem acesso a página inicial do sistema. Caso contrário, uma mensagem de erro é exibida.
- Ao tentar inserir as credenciais, caso não se lembre destas, o ator pode selecionar a opção de recuperação de senha. O sistema envia um e-mail com um link de redefinição de senha. O ator acessa o link, define uma nova senha e é redirecionado para a página de login.
  
![Login aluno](https://github.com/rafabertuol/pisegundaentrega/blob/780889a08dda2583c0bbc7f37dff949c7a15395c/Caso%20de%20uso%201%20-%20Fazer%20login.png)

## Caso de uso 2: cadastrar fornecedor
- O ator "Fornecedor" assina o contrato com a faculdade através do sistema, após isso o funcionário inicia o cadastro do fornecedor. O sistema registra as informações e atribui uma matrícula ao fornecedor. O sistema registra o novo cadastro no banco de dados. O sistema exibe uma mensagem de sucesso. 
- No momento do preenchimento do cadastro, se o serviço prestado ou o produto vendido não estiverem previamente cadastrados, o sistema exibe uma opção de cadastrar objeto do contrato. Para que seja efetuado cadastro antes de prosseguir com o cadastro do fornecedor.  
- Durante o processo, o funcionário decide cancelar o cadastro. O sistema descarta as alterações e limpa o formulário. 

![Fornecedor 1](https://github.com/rafabertuol/pisegundaentrega/blob/943384806dc7b862d5fb48d5c0e45d2205f7104d/Caso%20de%20uso%202%20-%20Cadastro%20de%20fornecedor%20produto%20ou%20servico%20nao%20encontrado.png)
![Fornecedor 2](https://github.com/rafabertuol/pisegundaentrega/blob/d7ea340240409332cdfd42f4a14b978ee5473f76/Caso%20de%20uso%202%20-%20Cadastro%20de%20fornecedor%20cancelado.png)
  
## Caso de uso 3: cadastrar aluno
- O ator "Candidato" assina o contrato com a faculdade através do sistema, após confirmação da matrícula pelo servidor, o “Funcionário” inicia o cadastro do candidato como “Aluno” no sistema.
- O sistema registra as informações e atribui uma matrícula ao aluno.
- O sistema registra o novo usuário no banco de dados e exibe uma mensagem de sucesso. 
- Caso a matrícula não tenha sido confirmada pelo sistema, o candidato receberá um e-mail informado o motivo da não confirmação, para que possa tomar as medidas cabíveis. 
- Durante o processo, o funcionário decide cancelar o cadastro. O sistema descarta as alterações e limpa o formulário. 

![Cadastro aluno 1](https://github.com/rafabertuol/pisegundaentrega/blob/c9b407058ce9ade12af68c009718ac3f522ccfe4/Caso%20de%20Uso%203%20-%20Cadastrar%20Aluno.png)
![Cadastro aluno 2](https://github.com/rafabertuol/pisegundaentrega/blob/80a12a00d6bf555fec21a3d8a2bc743ef4d5e52f/Caso%20de%20Uso%203%20-%20Matr%C3%ADcula%20n%C3%A3o%20confirmada.png)
![Cadastro aluno 3](https://github.com/rafabertuol/pisegundaentrega/blob/2927027e006192b4ec3044e4c43ce8b707e6a9df/Caso%20de%20Uso%203%20-%20Cadastrar%20Aluno%20Cancelada.png)

## Caso de uso 4: cadastrar notas
- O ator "Professor" acessa a interface de lançamento de notas e insere as notas dos alunos.
- O sistema valida as notas e as armazena no banco de dados.
- O sistema exibe uma mensagem de confirmação.
- No momento de validar as notas, se o sistema identificar uma nota inválida (fora da faixa permitida), exibe uma mensagem de erro. O professor corrige a nota e reenvia o dado correto.
- Durante o processo, o professor decide cancelar o lançamento de notas. O sistema descarta as alterações e retorna à interface anterior.
  
 ![Cadastro nota 1](https://github.com/rafabertuol/pisegundaentrega/blob/d741ed9d2763f50494df05872e228f78283f0381/Caso%20de%20Uso%204%20-%20Cadastro%20de%20Notas%20-%20V%C3%A1lido.png)
 ![Cadastro nota 2](https://github.com/rafabertuol/pisegundaentrega/blob/d741ed9d2763f50494df05872e228f78283f0381/Caso%20de%20Uso%204-%20Cadastro%20de%20Notas%20-%20Cancelar.png)
 ![Cadastro nota 3](https://github.com/rafabertuol/pisegundaentrega/blob/d741ed9d2763f50494df05872e228f78283f0381/Caso%20de%20Uso%204-%20Notas%20Inv%C3%A1lidas!.png)
