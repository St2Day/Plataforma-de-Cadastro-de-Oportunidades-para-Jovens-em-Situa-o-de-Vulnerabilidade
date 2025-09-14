### Caso de Uso: Candidatar-se
- Ator: Jovem
- Pré-condição: Usuário autenticado
- Fluxo principal:
  1. Jovem abre página da oportunidade.
  2. Clica em "Candidatar".
  3. Sistema grava candidatura e retorna confirmação.
- Fluxos alternativos:
  - Se usuário não autenticado → redirecionar para login.
- Pós-condição: Registro de candidatura criado (id, id_jovem, id_oportunidade, data).
