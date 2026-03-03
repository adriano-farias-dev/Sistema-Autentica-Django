# Projeto (Django)

Projeto de estudo com fluxo de login/logout e dashboard protegido.
O objetivo aqui é praticar autenticação no Django com uma base simples para evoluir.

## O que já tem
- Login usando `LoginView` e logout com `LogoutView`
- Dashboard protegido com `@login_required`
- Redirecionamento da raiz para a área autenticada
- Configuração por variáveis de ambiente

## Como rodar localmente
1. Crie e ative o ambiente virtual.
2. Instale as dependências:
   ```bash
   pip install -r requirements.txt
   ```
3. Copie `.env.example` para `.env` e ajuste os valores.
4. Rode as migrações:
   ```bash
   python manage.py migrate
   ```
5. Inicie o servidor:
   ```bash
   python manage.py runserver
   ```

## Variáveis de ambiente
- `DJANGO_SECRET_KEY`
- `DJANGO_DEBUG`
- `DJANGO_ALLOWED_HOSTS`

## Próximos passos
- Adicionar testes de autenticação
- Melhorar o visual das telas
- Preparar deploy
