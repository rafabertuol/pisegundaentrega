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

## Protótipo de interface de usuário: Pessoa Física
1) Alunos:
- Acesso ao sistema: o aluno acessa a página de login do sistema, onde há campo para inserir as suas credenciais (login e senha). Caso válidas, o aluno é autenticado e tem acesso ao sistema. 
- O passo a passo da prototipagem pode ser verificado [aqui](https://github.com/rafabertuol/pisegundaentrega/blob/3205ca31f96789bdb9b7d26c3f9188f3009886e3/Prototipagem.md)
  
![Login aluno](https://github.com/rafabertuol/pisegundaentrega/blob/780889a08dda2583c0bbc7f37dff949c7a15395c/Caso%20de%20uso%201%20-%20Fazer%20login.png)
  

2) Professores:
- Inserção de notas no sistema: o professor acessa o sistema inserindo login e senha; na tela principal, clica em "lançamento de notas", onde seleciona a turma e insere as notas dos alunos. O sistema valida as notas e as armazena no banco de dados, exibindo uma mensagem de confirmação. No momento de validar as notas, se o sistema identificar uma nota inválida (fora da faixa permitida), exibe uma mensagem de erro. O professor corrige a nota e reenvia o dado correto.
- O passo a passo da prototipagem pode ser verificado [aqui](https://github.com/rafabertuol/pisegundaentrega/blob/3205ca31f96789bdb9b7d26c3f9188f3009886e3/Prototipagem.md)
  
 ![Cadastro nota 1](https://github.com/rafabertuol/pisegundaentrega/blob/d741ed9d2763f50494df05872e228f78283f0381/Caso%20de%20Uso%204%20-%20Cadastro%20de%20Notas%20-%20V%C3%A1lido.png)
 ![Cadastro nota 2](https://github.com/rafabertuol/pisegundaentrega/blob/d741ed9d2763f50494df05872e228f78283f0381/Caso%20de%20Uso%204-%20Cadastro%20de%20Notas%20-%20Cancelar.png)
 ![Cadastro nota 3](https://github.com/rafabertuol/pisegundaentrega/blob/d741ed9d2763f50494df05872e228f78283f0381/Caso%20de%20Uso%204-%20Notas%20Inv%C3%A1lidas!.png)

3) Funcionários:
- Cadastro do aluno no sistema: após o aluno se matricular no curso desejado e a matrícula ter sido confirmada, o funcionário responsável inicia o cadastro desse como aluno no sistema. O funcionário acessa o sistema inserindo login e senha; na tela principal há uma interface com os botões: novos cadastros, consulta de cadastros, recursos humanos, folha de pagamento, treinamentos, controle de estoque, requisição de materiais e serviços. O funcionário clica na opção "novos cadastros" e abre uma interface com as opções: cadastrar aluno, cadastro de professores e cadastro de funcionários. O funcionário seleciona a opção "cadastro de aluno" e abre uma nova interface para inserção de dados do novo aluno. O sistema registra as informações e atribui uma matrícula ao aluno. O sistema registra o novo usuário no banco de dados e exibe uma mensagem de sucesso. Caso a matrícula não tenha sido confirmada pelo sistema, abrirá uma mensagem de erro "aluno não encontrado" e o aluno receberá um e-mail informado o motivo da não confirmação, para que possa tomar as medidas cabíveis.
- O passo a passo da prototipagem pode ser verificado [aqui](https://github.com/rafabertuol/pisegundaentrega/blob/3205ca31f96789bdb9b7d26c3f9188f3009886e3/Prototipagem.md)

![Cadastro aluno 1](https://github.com/rafabertuol/pisegundaentrega/blob/c9b407058ce9ade12af68c009718ac3f522ccfe4/Caso%20de%20Uso%203%20-%20Cadastrar%20Aluno.png)
![Cadastro aluno 2](https://github.com/rafabertuol/pisegundaentrega/blob/80a12a00d6bf555fec21a3d8a2bc743ef4d5e52f/Caso%20de%20Uso%203%20-%20Matr%C3%ADcula%20n%C3%A3o%20confirmada.png)
![Cadastro aluno 3](https://github.com/rafabertuol/pisegundaentrega/blob/f92c1b94dc56430ff0bc572fdeda21e55a8367aa/Caso%20de%20Uso%203%20-%20Matr%C3%ADcula%20n%C3%A3o%20confirmada.png)

## Protótipo de interface de usuário: Pessoa Jurídica
1) Fornecedores:
- Visualização de novo pedido: o fornecedor (pessoa jurídica) acessa a página de login do sistema, onde há campo para inserir as suas credenciais (login e senha). Caso válidas, o fornecedor é autenticado e tem acesso ao sistema. No sistema há uma interface com os botões: novos pedidos, pedidos em andamento, pedidos finalizados, gestão de contratos, rastreamento de entregas, emissão de notas fiscais, comunicação. O fornecedor clica na opção "novos pedidos" e abre uma interface com a lista dos pedidos novos. Ao clicar sobre um pedido, abre uma nova janela com os itens solicitados e as opções "aceitar" e "recusar". O fornecedor seleciona a opção "aceitar", o sistema registra o novo pedido e exibe uma mensagem de sucesso.
- O passo a passo da prototipagem pode ser verificado [aqui](https://github.com/rafabertuol/pisegundaentrega/blob/3205ca31f96789bdb9b7d26c3f9188f3009886e3/Prototipagem.md)





