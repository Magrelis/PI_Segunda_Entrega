# PI_Segunda_Entrega

---



### Protótipo: Cadastro de Pessoa Física

#### Descrição Geral
O protótipo permite a inserção, validação e gerenciamento dos dados de uma pessoa física no sistema de gestão da universidade. As principais funções incluem cadastro, atualização e cancelamento de registros.

#### Funcionalidades

1. **Cadastro de Pessoa Física**
   - **Acesso:** Usuário acessa a função "Cadastro de Pessoa Física".
   - **Inserção de Dados:** Sistema solicita e usuário insere dados pessoais (Nome, CPF, Endereço, etc.).
   - **Validação:** Sistema valida as informações inseridas.
   - **Confirmação:** Se os dados estiverem corretos, o sistema confirma o cadastro e exibe uma mensagem de sucesso.

2. **Cenário Alternativo 1: Dados Inválidos**
   - **Detecção de Erros:** Sistema detecta dados incorretos.
   - **Correção:** Exibe mensagem de erro e solicita correção dos dados.
   - **Revalidação:** Sistema valida novamente até aprovação.

3. **Cenário Alternativo 2: Cancelamento do Cadastro**
   - **Opção de Cancelamento:** Usuário opta por cancelar o cadastro.
   - **Confirmação:** Sistema solicita confirmação do cancelamento.
   - **Cancelamento:** Cadastro é cancelado e dados não são salvos.

#### Pré-condições
- Usuário deve estar autenticado no sistema.
- Sistema deve estar funcionando corretamente.

#### Pós-condições
- **Cadastro Bem-sucedido:** Dados da pessoa física são armazenados.
- **Erro no Cadastro:** Sistema exibe mensagens para correção.
- **Cancelamento:** Nenhuma informação é salva.

!Protoripo pessoa fisica

![pessoa-fisica resized](https://github.com/user-attachments/assets/1f86a487-d9a1-47db-a836-a99fa5cb5784)

---


### Protótipo: Cadastro de Pessoa Jurídica

#### Descrição Geral
Este prototipo permite que o usuário insira, edite ou remova o cadastro de uma empresa no sistema. O sistema valida o CNPJ e, se estiver correto, realiza o cadastro. É possível cancelar ou atualizar um cadastro existente.

#### Funcionalidades

1. **Cadastro de Pessoa Jurídica**
   - **Acesso:** O usuário acessa a função "Cadastro de Pessoa Jurídica".
   - **Inserção de Dados:** O sistema solicita e o usuário insere os dados da empresa (CNPJ, razão social, endereço, etc.).
   - **Validação:** O sistema valida as informações inseridas.
   - **Consulta Externa:** O sistema consulta uma API externa para validar o CNPJ.
   - **Confirmação:** Se os dados estiverem corretos e o CNPJ for válido, o sistema confirma o cadastro.
   - **Mensagem de Sucesso:** O sistema exibe uma mensagem de sucesso e oferece a opção de gerar um comprovante.

2. **Cenário Alternativo 1: CNPJ Inválido**
   - **Detecção de Erros:** O sistema detecta que o CNPJ é inválido.
   - **Correção:** O sistema exibe uma mensagem de erro e solicita a correção dos dados.
   - **Revalidação:** O sistema valida novamente até aprovação.

3. **Cenário Alternativo 2: Cancelamento do Cadastro**
   - **Opção de Cancelamento:** O usuário opta por cancelar o cadastro.
   - **Confirmação:** O sistema solicita confirmação do cancelamento.
   - **Cancelamento:** O cadastro é cancelado e os dados não são salvos.

#### Pré-condições
- O usuário deve estar autenticado e ter permissões adequadas.
- O sistema deve estar conectado ao banco de dados.
- O serviço externo para validação de CNPJ deve estar disponível.

#### Pós-condições
- **Cadastro Bem-sucedido:** Os dados da pessoa jurídica serão armazenados.
- **Erro no Cadastro:** O sistema exibirá mensagens para correção.
- **Cancelamento:** Nenhuma informação será salva.

 !prototipo pessoa juridica 
 
![pessoa_juridica](https://github.com/user-attachments/assets/aaa01a85-59a7-4485-a6a2-ed1156f3d2be)

---


###  Protótipo: Cadastro de Professor

#### Descrição Geral
O administrador insere e valida os dados de um professor no sistema, podendo cadastrar, cancelar ou atualizar o registro.

#### Funcionalidades

1. **Cadastro de Professor**
   - **Acesso:** O administrador acessa a função "Cadastro de Professor".
   - **Inserção de Dados:** O sistema solicita e o administrador insere os dados (nome, data de nascimento, CPF, RG, endereço, sexo, disciplina, salário).
   - **Validação:** O sistema valida as informações inseridas.
   - **Confirmação:** Se os dados estiverem corretos, o sistema confirma o cadastro e exibe uma mensagem de sucesso.

2. **Cenário Alternativo 1: Dados Inválidos**
   - **Detecção de Erros:** O sistema detecta dados incorretos (por exemplo, CPF inválido).
   - **Correção:** O sistema exibe uma mensagem de erro e solicita a correção dos dados.
   - **Revalidação:** O sistema revalida até que os dados estejam corretos.
   - **Confirmação:** Após a correção, o cadastro é confirmado.

3. **Cenário Alternativo 2: Cancelamento do Cadastro**
   - **Opção de Cancelamento:** O administrador decide cancelar o cadastro antes da confirmação.
   - **Confirmação:** O sistema solicita confirmação para o cancelamento.
   - **Cancelamento:** O administrador confirma, e o sistema descarta os dados inseridos.
   - **Retorno:** O sistema retorna à tela inicial ou à página anterior.

#### Pré-condições
- O administrador deve estar autenticado.
- O sistema deve estar operacional.

#### Pós-condições
- **Cadastro Bem-sucedido:** Os dados serão armazenados no banco de dados.
- **Erro no Cadastro:** O sistema exibirá mensagens de erro caso haja problemas com os dados.
- **Cancelamento:** Nenhum dado será armazenado se o cadastro for cancelado.
  
!prototipo cadastro professor

![cadastro_professor](https://github.com/user-attachments/assets/9dfddc95-85db-49cf-ae42-5a0cc6171157)

---



###  Protótipo: Cadastro de Aluno

#### Descrição Geral
O administrador insere os dados de um aluno no sistema, que valida e armazena essas informações no banco de dados.

#### Funcionalidades

1. **Cadastro de Aluno**
   - **Acesso:** O administrador acessa o módulo de cadastro de alunos.
   - **Formulário de Cadastro:** O sistema exibe o formulário de cadastro.
   - **Inserção de Dados:** O administrador insere os dados do aluno.
   - **Validação:** O sistema valida os dados inseridos.
   - **Confirmação:** Se válidos, o sistema adiciona o aluno e exibe uma mensagem de sucesso.

2. **Cenário Alternativo 1: Dados Inválidos**
   - **Detecção de Erros:** O sistema detecta dados incorretos.
   - **Correção:** Exibe uma mensagem de erro e solicita a correção dos dados.
   - **Revalidação:** O administrador corrige e a validação é feita novamente.

3. **Cenário Alternativo 2: Falha ao Salvar no Banco**
   - **Erro de Conexão:** Ocorre uma falha ao conectar com o banco de dados.
   - **Mensagem de Erro:** O sistema exibe uma mensagem de erro e permite que o administrador tente novamente.

#### Pré-condições
- O sistema deve estar funcionando e o administrador autenticado.

#### Pós-condições
- **Cadastro Bem-sucedido:** O aluno será salvo com sucesso.
- **Erro no Cadastro:** O sistema registrará o erro para correção.

!prototipo cadastro aluno

![cadastro_aluno](https://github.com/user-attachments/assets/c15ce95c-7d6d-408a-adf1-93e46989e189)

---


### Funções do Protótipo: Cadastro de Fornecedores

#### Descrição Geral
Este protótipo descreve como o funcionário cadastra, edita ou exclui fornecedores no sistema de uma empresa. Inclui a validação dos dados e o gerenciamento de duplicidades.

#### Funcionalidades

1. **Cadastro de Fornecedores**
   - **Acesso:** O funcionário acessa a função "Cadastro de Fornecedor".
   - **Lista e Novo Cadastro:** O sistema exibe a lista de fornecedores e a opção "Novo Fornecedor".
   - **Inserção de Dados:** O sistema solicita dados como Nome da Empresa, CNPJ, Endereço, Telefone, Email, Nome do Responsável e Forma de Fornecimento.
   - **Validação:** O funcionário preenche e clica em "Salvar". O sistema valida os campos obrigatórios e verifica se o CNPJ já está cadastrado.
   - **Confirmação:** Se as informações estiverem corretas, o fornecedor é salvo e uma mensagem de confirmação é exibida.
   - **Adição à Lista:** O fornecedor é adicionado à lista.

2. **Cenário Alternativo 1: Edição de Fornecedor**
   - **Acesso à Edição:** O funcionário acessa a lista de fornecedores e seleciona "Editar".
   - **Alteração de Dados:** O sistema exibe as informações atuais, e o funcionário faz as alterações.
   - **Validação e Atualização:** Após clicar em "Salvar", o sistema valida e atualiza os dados.
   - **Confirmação:** Uma mensagem de confirmação é exibida, e as informações são atualizadas.

3. **Cenário Alternativo 2: Exclusão de Fornecedor**
   - **Opção de Exclusão:** O funcionário seleciona um fornecedor e clica em "Excluir".
   - **Confirmação:** O sistema solicita confirmação, e o funcionário confirma a exclusão.
   - **Remoção:** O fornecedor é removido do sistema, e uma mensagem de confirmação é exibida.

#### Pré-condições
- O funcionário deve estar autenticado no sistema.
- O sistema deve garantir a integridade dos dados, evitando duplicidades de fornecedores.

#### Pós-condições
- **Atualização ou Remoção:** As informações do fornecedor são atualizadas ou removidas no sistema.
- **Cancelamento:** Nenhum dado será armazenado se o cadastro for cancelado.


!prototipo fornecedor

![cadastro_fornecedor](https://github.com/user-attachments/assets/8f7fffc5-75f4-47b0-9f08-e0026d5c62aa)

  
