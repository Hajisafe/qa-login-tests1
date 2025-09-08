# Plano de Testes — Sistema de Login

**Objetivo:** Validar a funcionalidade de autenticação (login) garantindo que credenciais válidas sejam aceitas e inválidas rejeitadas com mensagens adequadas.

**Escopo:**
- Login com credenciais válidas
- Login com credenciais inválidas (usuário e/ou senha)
- Campos obrigatórios e validações de limite (comprimento mínimo/máximo)
- Bloqueio após tentativas repetidas (se aplicável)
- Mensagens de erro e usabilidade

**Fora do escopo:** Cadastro, redefinição de senha, MFA (caso não existam).

**Ambiente:** Windows 10/11, Chrome recente.

**Critérios de Entrada:**
- Página de login acessível
- Usuário(s) de teste definidos (se houver)

**Critérios de Saída:**
- 100% dos casos de teste executados
- Defeitos críticos identificados e reportados

**Riscos:** Intermitência de rede, ambiente de teste instável.

**Responsável:** Nikolas Bezerra da Silva

**Métricas:** Nº de casos executados, taxa de aprovação, nº de defeitos por severidade.
