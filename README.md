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
O projeto consiste em apresentar protótipos de interface de um sistema de gestão escolar, de acordo com diagramas de caso de uso desenvolvidos na primeira etapa do projeto. Os protótipos serão divididos de acordo com o usuário a utilizar o sistema, sendo: pessoas físicas: alunos, professores, funcionários; e pessoas jurídicas: fornecedores.

## Caso de uso 1: fazer login no sistema
- O ator "Pessoa Física" (professor, aluno ou funcionário) acessa a página de login do sistema, insere as credenciais (matrícula e senha) e o sistema valida as credenciais. Se forem válidas, o ator é autenticado e tem acesso a página inicial do sistema. Caso contrário, uma mensagem de erro é exibida.

- Ao serem inseridas as credenciais, caso sejam inválidas, uma mensagem de erro é exibida. O ator tem a opção de tentar novamente.

- Ao tentar inserir as credenciais, caso não se lembre destas, o ator pode selecionar a opção de recuperação de senha. O sistema envia um e-mail com um link de redefinição de senha. O ator acessa o link, define uma nova senha e é redirecionado para a página de login.

- O passo a passo da prototipagem pode ser verificado [aqui](https://github.com/rafabertuol/pisegundaentrega/blob/3205ca31f96789bdb9b7d26c3f9188f3009886e3/Prototipagem.md)
  
![Login aluno](https://github.com/rafabertuol/pisegundaentrega/blob/780889a08dda2583c0bbc7f37dff949c7a15395c/Caso%20de%20uso%201%20-%20Fazer%20login.png)

## Caso de uso 2: cadastrar fornecedor
- Visualização de novo pedido: o fornecedor (pessoa jurídica) acessa a página de login do sistema, onde há campo para inserir as suas credenciais (login e senha). Caso válidas, o fornecedor é autenticado e tem acesso ao sistema. No sistema há uma interface com os botões: novos pedidos, pedidos em andamento, pedidos finalizados, gestão de contratos, rastreamento de entregas, emissão de notas fiscais, comunicação. O fornecedor clica na opção "novos pedidos" e abre uma interface com a lista dos pedidos novos. Ao clicar sobre um pedido, abre uma nova janela com os itens solicitados e as opções "aceitar" e "recusar". O fornecedor seleciona a opção "aceitar", o sistema registra o novo pedido e exibe uma mensagem de sucesso.
- O passo a passo da prototipagem pode ser verificado [aqui](https://github.com/rafabertuol/pisegundaentrega/blob/3205ca31f96789bdb9b7d26c3f9188f3009886e3/Prototipagem.md)

![Fornecedor 1](https://github.com/rafabertuol/pisegundaentrega/blob/943384806dc7b862d5fb48d5c0e45d2205f7104d/Caso%20de%20uso%202%20-%20Cadastro%20de%20fornecedor%20produto%20ou%20servico%20nao%20encontrado.png)
![Fornecedor 2](https://github.com/rafabertuol/pisegundaentrega/blob/d7ea340240409332cdfd42f4a14b978ee5473f76/Caso%20de%20uso%202%20-%20Cadastro%20de%20fornecedor%20cancelado.png)
  
## Caso de uso 3: cadastrar aluno
- Cadastro do aluno no sistema: após o aluno se matricular no curso desejado e a matrícula ter sido confirmada, o funcionário responsável inicia o cadastro desse como aluno no sistema. O funcionário acessa o sistema inserindo login e senha; na tela principal há uma interface com os botões: novos cadastros, consulta de cadastros, recursos humanos, folha de pagamento, treinamentos, controle de estoque, requisição de materiais e serviços. O funcionário clica na opção "novos cadastros" e seleciona a opção "cadastrar aluno". O sistema registra as informações e atribui uma matrícula ao aluno. O sistema registra o novo usuário no banco de dados e exibe uma mensagem de sucesso. Caso a matrícula não tenha sido confirmada pelo sistema, abrirá uma mensagem de erro "aluno não encontrado" e o aluno receberá um e-mail informado o motivo da não confirmação, para que possa tomar as medidas cabíveis. O processo também pode ser cancelado clicando na opção "cancelar". 
- O passo a passo da prototipagem pode ser verificado [aqui](https://github.com/rafabertuol/pisegundaentrega/blob/3205ca31f96789bdb9b7d26c3f9188f3009886e3/Prototipagem.md)

![Cadastro aluno 1](https://github.com/rafabertuol/pisegundaentrega/blob/c9b407058ce9ade12af68c009718ac3f522ccfe4/Caso%20de%20Uso%203%20-%20Cadastrar%20Aluno.png)
![Cadastro aluno 2](https://github.com/rafabertuol/pisegundaentrega/blob/80a12a00d6bf555fec21a3d8a2bc743ef4d5e52f/Caso%20de%20Uso%203%20-%20Matr%C3%ADcula%20n%C3%A3o%20confirmada.png)
![Cadastro aluno 3](https://github.com/rafabertuol/pisegundaentrega/blob/2927027e006192b4ec3044e4c43ce8b707e6a9df/Caso%20de%20Uso%203%20-%20Cadastrar%20Aluno%20Cancelada.png)

## Caso de uso 4: cadastrar notas
- Inserção de notas no sistema: o professor acessa o sistema inserindo login e senha; na tela principal, clica em "lançamento de notas", onde seleciona a turma e insere as notas dos alunos. O sistema valida as notas e as armazena no banco de dados, exibindo uma mensagem de confirmação. No momento de validar as notas, se o sistema identificar uma nota inválida (fora da faixa permitida), exibe uma mensagem de erro. O professor corrige a nota e reenvia o dado correto.
- O passo a passo da prototipagem pode ser verificado [aqui](https://github.com/rafabertuol/pisegundaentrega/blob/3205ca31f96789bdb9b7d26c3f9188f3009886e3/Prototipagem.md)
  
 ![Cadastro nota 1](https://github.com/rafabertuol/pisegundaentrega/blob/d741ed9d2763f50494df05872e228f78283f0381/Caso%20de%20Uso%204%20-%20Cadastro%20de%20Notas%20-%20V%C3%A1lido.png)
 ![Cadastro nota 2](https://github.com/rafabertuol/pisegundaentrega/blob/d741ed9d2763f50494df05872e228f78283f0381/Caso%20de%20Uso%204-%20Cadastro%20de%20Notas%20-%20Cancelar.png)
 ![Cadastro nota 3](https://github.com/rafabertuol/pisegundaentrega/blob/d741ed9d2763f50494df05872e228f78283f0381/Caso%20de%20Uso%204-%20Notas%20Inv%C3%A1lidas!.png)
