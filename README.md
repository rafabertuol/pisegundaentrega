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
O projeto consiste em apresentar protótipos de interface de um sistema de gestão escolar, de acordo com diagramas de caso de uso desenvolvidos na primeira etapa do projeto. Os protótipos serão divididos de acordo com o usuário a utilizar o sistema, sendo: pessoa física, pessoa jurídica, professores, fornecedores e alunos.

## Protótipo de interface de usuário: Pessoa Física
1) Alunos:
- Acesso ao sistema: o aluno acessa a página de login do sistema, onde há campo para inserir as suas credenciais (login e senha). Caso válidas, o aluno é autenticado e tem acesso ao sistema. Caso inválidas, abrirá uma janela com mensagem de erro. O aluno pode tentar inserir novamente os dados ou então clicar em "recuperação de senha". Ao clicar nessa opção, abre uma janela para que o aluno insira seu e-mail de contato. O sistema envia um e-mail com um link de redefinição de senha. O aluno acessa o link, define uma nova senha e é redirecionado para a página de login.

2) Professores:
- Inserção de notas no sistema: o professor acessa a página de login do sistema, onde há campo para inserir as suas credenciais (login e senha). Caso válidas, o professor é autenticado e tem acesso ao sistema. No sistema há uma interface com os botões: lançamento de notas, criação de planos de aula, publicação de materiais didáticos, fóruns e grupos de estudos, comunicação. O professor clica na opção "lançamento de notas", onde seleciona a turma e insere as notas dos alunos. O sistema valida as notas e as armazena no banco de dados, exibindo uma mensagem de confirmação. No momento de validar as notas, se o sistema identificar uma nota inválida (fora da faixa permitida), exibe uma mensagem de erro. O professor corrige a nota e reenvia o dado correto.

3) Funcionários:
- Cadastro do aluno no sistema: após o aluno se matricular no curso desejado e a matrícula ter sido confirmada, o funcionário responsável inicia o cadastro desse como aluno no sistema. O funcionário acessa a página de login do sistema, onde há campo para inserir as suas credenciais (login e senha). Caso válidas, o funcionário é autenticado e tem acesso ao sistema. No sistema há uma interface com os botões: novos cadastros, consulta de cadastros, recursos humanos, folha de pagamento, treinamentos, controle de estoque, requisição de materiais e serviços. O funcionário clica na opção "novos cadastros" e abre uma interface com as opções: cadastro de aluno, cadastro de professores e cadastro de funcionários. O funcionário seleciona a opção "cadastro de aluno" e abre uma nova interface para inserção de dados do novo aluno. O sistema registra as informações e atribui uma matrícula ao aluno. O sistema registra o novo usuário no banco de dados e exibe uma mensagem de sucesso. Caso a matrícula não tenha sido confirmada pelo sistema, abrirá uma mensagem de erro "aluno não encontrado" e o aluno receberá um e-mail informado o motivo da não confirmação, para que possa tomar as medidas cabíveis. 

## Protótipo de interface de usuário: Pessoa Jurídica
1) Fornecedores:


