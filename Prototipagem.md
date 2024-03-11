# Protótipo de interface de usuário: Pessoa Física
## 1) Alunos:
Descrição das telas para criação do protótipo:

a) Página de Login do sistema:
- Campo de entrada para o login do aluno.
- Campo de entrada para a senha do aluno.
- Botão "Entrar" para submeter as credenciais e autenticar o aluno.
- Botão “recuperar senha” para uso se necessário. 

b) Página Principal do Sistema:

Após o login bem-sucedido, o aluno é redirecionado para a página principal do sistema.

Interface com os seguintes botões:
- "Notas": Acessa as notas do aluno em disciplinas anteriores.
- "Calendário Acadêmico": Exibe eventos e datas importantes relacionadas ao calendário acadêmico.
- "Realizar Matrícula": Permite que o aluno se matricule em disciplinas para o próximo semestre.
- "Financeiro": Fornece acesso às informações financeiras, como pagamentos, mensalidades, etc.
- "Serviços": Oferece acesso a outros serviços oferecidos pela instituição, como biblioteca, refeitório, etc.
- "Comunicação": Facilita a comunicação entre alunos e professores, através de mensagens internas.

c) Tela de Realizar Matrícula:
- Ao clicar no botão "Realizar Matrícula", o aluno é levado para a tela onde todas as disciplinas disponíveis para o próximo semestre são listadas.
- Cada disciplina é exibida com seu nome, código, horário e disponibilidade de vagas.
- Botão "Voltar" para retornar à página principal.
- Botão "Confirmar Matrícula" ao lado de cada disciplina disponível.

d) Pop-up de Confirmação de Matrícula:

- Ao clicar no botão "Confirmar Matrícula" de uma disciplina específica, um pop-up de confirmação é exibido.
- O pop-up exibe o texto “Deseja efetuar a matrícula na disciplina?”, com as opções de botão “sim” ou “não”.
- O aluno clica na opção “sim” e, havendo vaga/disponibilidade na disciplina selecionada, a matrícula é efetuada com sucesso. Abrirá um pop-up exibindo o texto ““Matrícula efetuada com sucesso”.
- Botão "Fechar" para fechar o pop-up e retornar à tela de Realizar Matrícula.

## 2) Professores:
Descrição das telas para criação do protótipo:

a) Página de Login do sistema:
- Campo de entrada para o login do professor.
- Campo de entrada para a senha do professor.
- Botão "Entrar" para submeter as credenciais e autenticar o professor.
- Botão “recuperar senha” para uso se necessário. 

b) Página principal do sistema:
Após o login bem-sucedido, o professor é redirecionado para a página principal do sistema.

Interface com os seguintes botões:

- "Lançamento de Notas": Permite que o professor insira notas para os alunos.
- "Calendário Acadêmico": Exibe eventos e datas importantes relacionadas ao calendário acadêmico.
- "Criação de Planos de Aula": Permite que o professor crie planos de aula para suas disciplinas.
- "Publicação de Materiais Didáticos": Facilita a publicação de materiais de estudo para os alunos.
- "Fóruns e Grupos de Estudos": Oferece espaço para interação entre alunos e professores.
- "Comunicação": Facilita a comunicação entre professores e alunos.
- "Atualizar Dados": Permite que o professor atualize suas informações pessoais.

c) Tela de Lançamento de Notas:
- Ao clicar no botão "Lançamento de Notas", o professor é levado para a tela onde pode inserir notas para os alunos. Na tela, estarão disponíveis as turmas para qual leciona com nome da disciplina e código da turma.
- O professor seleciona a turma para a qual deseja lançar as notas.
- O sistema exibe uma tabela com os alunos matriculados na turma, permitindo a inserção das notas correspondentes a cada aluno. Ao lado do nome de cada aluno há um campo de digitação para inserção da nota. 
- Botão "Voltar" para retornar à página principal.
- Botão "Salvar Notas" para submeter as notas inseridas.

d) Pop-up de Confirmação de lançamento das notas:
- O pop-up exibe o texto “Deseja confirmar as notas inseridas?”, com as opções de botão “sim” ou “não”.
- O professor clica na opção “sim” e abre um pop-up exibindo o texto “Notas registradas com sucesso”.
- Botão "Fechar" para fechar o pop-up e retornar à tela de lançamento de notas.

d) Mensagem de Erro:
- Após clicar na opção sim no pop-up, se o sistema identificar uma nota inválida (fora da faixa permitida), uma mensagem de erro é exibida “nota inválida”, indicando a necessidade de correção.
- O professor pode corrigir a nota incorreta e reenviar os dados corrigidos.

## 3) Funcionários:
Descrição das telas para criação do protótipo:

a) Página de Login do sistema:

- Campo de entrada para o login do funcionário.
- Campo de entrada para a senha do funcionário.
- Botão "Entrar" para submeter as credenciais e autenticar o funcionário.
- Botão “recuperar senha” para uso se necessário. 

b) Página principal do sistema:

Após o login bem-sucedido, o funcionário é redirecionado para a página principal do sistema.

Interface com os seguintes botões:
- "Novos Cadastros": Permite a realização de novos cadastros no sistema.
- "Consulta de Cadastros": Permite a busca e visualização de informações de cadastros existentes.
- "Recursos Humanos": Gerencia informações relacionadas aos funcionários da instituição.
- "Folha de Pagamento": Gerencia informações relacionadas à folha de pagamento dos funcionários.
- "Treinamentos": Gerencia informações sobre treinamentos oferecidos aos funcionários.
- "Controle de Estoque": Gerencia informações sobre o estoque da instituição.
- "Requisição de Materiais e Serviços": Permite a solicitação de materiais e serviços necessários.

c) Tela de Novos Cadastros:

Ao clicar no botão "Novos Cadastros", o funcionário é apresentado a uma nova tela com opções de cadastro.

Interface com opções para:
- Cadastro de Aluno
- Cadastro de Professores
- Cadastro de Funcionários

d) Interface de Cadastro de Aluno:
- Ao selecionar a opção "Cadastro de Aluno", o funcionário é levado para a tela de inserção de dados do novo aluno com campos para digitar texto/números.
- Campos para inserção de informações pessoais do aluno, como nome, data de nascimento, endereço, etc.
- O sistema atribui uma matrícula ao aluno automaticamente.
- Botão "Salvar" para registrar o novo aluno no sistema.

e) Mensagens de Confirmação e Erro:
- Após o registro bem-sucedido, o sistema exibe uma mensagem de sucesso.
- Se a matrícula do aluno não foi confirmada, uma mensagem pop-up de erro é exibida: "Aluno não encontrado".
- Nesse caso, o aluno recebe um e-mail informando o motivo da não confirmação, com instruções para tomar as medidas cabíveis.

# Protótipo de interface de usuário: Pessoa Jurídica
## 1) Fornecedores:
Descrição das telas para criação do protótipo:

a) Página de Login do sistema:
- Campo de entrada para o login do fornecedor (pessoa jurídica).
- Campo de entrada para a senha do fornecedor.
- Botão "Entrar" para submeter as credenciais e autenticar o fornecedor.
- Botão “recuperar senha” para uso se necessário. 

b) Página principal do sistema:

Após o login bem-sucedido, o fornecedor é redirecionado para a página principal do sistema.

Interface com os seguintes botões:
- "Novos Pedidos": Permite visualizar e responder a novos pedidos.
- "Pedidos em Andamento": Mostra os pedidos que já foram aceitos e estão em processo de execução.
- "Pedidos Finalizados": Lista os pedidos que foram concluídos.
- "Gestão de Contratos": Permite gerenciar contratos com os clientes.
- "Rastreamento de Entregas": Fornece informações sobre o status das entregas.
- "Emissão de Notas Fiscais": Permite ao fornecedor emitir notas fiscais para os pedidos realizados.
- "Comunicação": Facilita a comunicação entre o fornecedor e a empresa.

c) Tela de Novos Pedidos:
- Ao clicar no botão "Novos Pedidos", o fornecedor é apresentado com uma lista de pedidos recentes feitos pela universidade.
- Cada pedido é listado na tela com informações básicas, como número do pedido, data e hora do pedido.
- Ao clicar sobre um pedido, abre-se uma nova janela com os detalhes do pedido, incluindo os itens solicitados e suas quantidades. Na tela há a opção de botões de "Aceitar pedido" e "Recusar pedido".

d) Mensagem de Confirmação:
- Se o fornecedor selecionar a opção "Aceitar", o sistema registra o novo pedido e exibe uma mensagem de sucesso. O fornecedor pode então prosseguir com o processamento do pedido.

