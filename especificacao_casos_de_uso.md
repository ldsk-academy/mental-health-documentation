## Especificação de Casos de Uso

### Casos de Uso para Pacientes

### Cadastro e Login

- **Descrição:** Permite ao paciente criar uma conta e acessar o sistema.

- **Fluxo Principal:** 
    - a. O paciente acessa a página de cadastro/login.
    - b. O paciente insere informações (CPF, nome completo, número de Telefone, idade, senha e e-mail para login) e cria uma conta.
    - c. O paciente faz login no sistema com e-mail e senha.

- **Exceções:**
    - Dados inválidos: O sistema solicita a correção dos dados inseridos. 
    - E-mail já registrado: O sistema informa que o e-mail já está em uso.

### Agendar consultas

- **Descrição:** Permite ao paciente agendar uma consulta com um psicólogo.

- **Fluxo Principal:** 
    - a. O paciente faz login e acessa a seção de agendamento. 
    - b. O paciente visualiza psicólogos disponíveis e seus horários. 
    - c. O paciente seleciona um psicólogo e um horário conveniente.
    - d. O paciente confirma o agendamento.
    - e. O sistema envia uma notificação para o e-mail ou SMS do paciente quando o psicólogo confirmar ou rejeitar o agendamento.

- **Exceções:**
    - Horário indisponível: O sistema exibe uma mensagem informando que o horário não está mais disponível.

### Visualizar Consultas Agendadas 

- **Descrição:** Permite ao paciente visualizar e gerenciar consultas futuras. 

- **Fluxo Principal:** 
    - a. O paciente faz login e acessa a seção de consultas. 
    - b. O paciente visualiza a lista de consultas agendadas.
    - c. O paciente pode cancelar ou reagendar uma consulta, se permitido.

- **Exceções:**
    - Cancelamento não permitido: O sistema informa se o cancelamento não for permitido para a consulta.


### Atualizar Informações Pessoais

- **Descrição:** Permite ao paciente atualizar informações de perfil.

- **Fluxo Principal:** 
    - a. O paciente faz login e acessa a seção de perfil. 
    - b. O paciente edita informações pessoais, como telefone ou endereço.
    - c. O paciente salva as alterações.

- **Exceções:**
    - Dados inválidos: O sistema solicita a correção dos dados inseridos.

### 2.2 Casos de Uso para Psicólogos

### Cadastro e Login

- **Descrição:** Permite ao psicólogo criar uma conta e acessar o sistema.

- **Fluxo Principal:** 
    - a. O psicólogo acessa a página de cadastro/login. 
    - b. O psicólogo insere informações (nome completo, número de telefone, especialidades, CRP, senha e e-mail para login) e cria uma conta.
    - c. O psicólogo faz login no sistema com e-mail e senha.

- **Exceções:**
    - Dados inválidos: O sistema solicita a correção dos dados inseridos.
    - E-mail já registrado: O sistema informa que o e-mail já está em uso.

### Gerenciar Disponibilidade

- **Descrição:** Permite ao psicólogo atualizar seus horários e dias da semana disponíveis para consultas.

- **Fluxo Principal:** 
    - a. O psicólogo faz login e acessa a seção de disponibilidade. 
    - b. O psicólogo adiciona, remove ou altera horários disponíveis.
    - c. O psicólogo salva as alterações.

- **Exceções:**
    - Horário conflitante: O sistema informa se o horário já estiver reservado.

### Confirmar ou Rejeitar Agendamentos 

- **Descrição:** Permite ao psicólogo confirmar ou rejeitar consultas agendadas por pacientes.

- **Fluxo Principal:** 
    - a. O psicólogo faz login e acessa a seção de agendamentos. 
    - b. O psicólogo visualiza novos agendamentos.
    - c. O psicólogo confirma ou rejeita os agendamentos.
    - d. O sistema notifica o paciente sobre a confirmação ou rejeição.

- **Exceções:**
    - Problema ao confirmar: O sistema informa se não for possível confirmar o agendamento.

### Editar Ficha do Paciente

- **Descrição:** Permite ao psicólogo atualizar informações e notas sobre o paciente.

- **Fluxo Principal:** 
    - a. O psicólogo faz login e acessa a seção de fichas de pacientes.
    - b. O psicólogo seleciona um paciente específico (pesquisa por CPF).
    - c. O psicólogo atualiza informações, como diagnóstico, plano de tratamento e status do paciente.
    - d. O psicólogo salva as alterações.

- **Exceções:**
    - Dados inválidos: O sistema solicita a correção dos dados inseridos.

### Atualizar Informações Pessoais 

- **Descrição:** Permite ao psicólogo atualizar informações de perfil.

- **Fluxo Principal:** 
    - a. O psicólogo faz login e acessa a seção de perfil.
    - b. O psicólogo edita informações pessoais, como telefone ou nova especialidade.
    - c. O paciente salva as alterações.

- **Exceções:**
    - Dados inválidos: O sistema solicita a correção dos dados inseridos.