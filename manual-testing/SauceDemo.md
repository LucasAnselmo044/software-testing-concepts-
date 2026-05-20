# Cenários de Teste — SauceDemo

## Objetivo

Validar funcionalidades principais da aplicação SauceDemo através de testes manuais focados em autenticação, sessão, autorização e comportamento do carrinho.

---

## C1 — Login válido

### Objetivo
Validar autenticação com credenciais válidas.

### Passos
1. Acessar a tela de login.
2. Inserir usuário válido.
3. Inserir senha válida.
4. Clicar em Login.

### Resultado Esperado
O sistema deve autenticar o usuário e redirecionar para a Dashboard.

### Resultado Obtido
✅ PASSOU

---

## C2 — Login inválido

### Objetivo
Validar bloqueio de acesso utilizando credenciais inválidas.

### Passos
1. Inserir usuário inválido.
2. Inserir senha inválida.
3. Clicar em Login.

### Resultado Esperado
O sistema deve impedir o acesso e exibir mensagem de erro.

### Resultado Obtido
✅ PASSOU

---

## C3 — Logout

### Objetivo
Validar encerramento correto da sessão do usuário.

### Passos
1. Realizar login.
2. Abrir menu lateral.
3. Selecionar opção Logout.

### Resultado Esperado
O sistema deve encerrar a sessão e retornar para a tela de login.

### Resultado Obtido
✅ PASSOU

---

## C4 — Controle de acesso à Dashboard

### Objetivo
Validar proteção da Dashboard para usuários não autenticados.

### Passos
1. Realizar logout.
2. Inserir diretamente a URL da Dashboard.

### Resultado Esperado
O sistema deve impedir acesso direto e redirecionar para a página de login.

### Resultado Obtido
✅ PASSOU

---

## C5 — Persistência da sessão após atualização

### Objetivo
Validar manutenção da sessão ativa após atualização da página.

### Passos
1. Realizar login.
2. Acessar Dashboard.
3. Atualizar página (F5).

### Resultado Esperado
O usuário deve permanecer autenticado sem necessidade de novo login.

### Resultado Obtido
✅ PASSOU

---

## C6 — Persistência do carrinho

### Objetivo
Validar comportamento do carrinho após múltiplas interações.

### Passos
1. Realizar login.
2. Adicionar múltiplos produtos ao carrinho.
3. Navegar entre páginas.
4. Atualizar a página.

### Resultado Esperado
Os produtos adicionados devem permanecer no carrinho.

### Resultado Obtido
✅ PASSOU

---

# Resumo da Execução

| ID | Cenário | Status |
|-----|---------|--------|
| C1 | Login válido | ✅ Passou |
| C2 | Login inválido | ✅ Passou |
| C3 | Logout | ✅ Passou |
| C4 | Controle de acesso à Dashboard | ✅ Passou |
| C5 | Persistência da sessão | ✅ Passou |
| C6 | Persistência do carrinho | ✅ Passou |

---

## Ambiente

- Aplicação: SauceDemo
- Tipo de teste: Manual
- Categoria: Funcional / Sistema / UI (End-to-End)
# Cenários de Teste — SauceDemo

## Objetivo

Validar funcionalidades principais da aplicação SauceDemo através de testes manuais focados em autenticação, sessão, autorização e comportamento do carrinho.

---

## C1 — Login válido

### Objetivo
Validar autenticação com credenciais válidas.

### Passos
1. Acessar a tela de login.
2. Inserir usuário válido.
3. Inserir senha válida.
4. Clicar em Login.

### Resultado Esperado
O sistema deve autenticar o usuário e redirecionar para a Dashboard.

### Resultado Obtido
✅ PASSOU

---

## C2 — Login inválido

### Objetivo
Validar bloqueio de acesso utilizando credenciais inválidas.

### Passos
1. Inserir usuário inválido.
2. Inserir senha inválida.
3. Clicar em Login.

### Resultado Esperado
O sistema deve impedir o acesso e exibir mensagem de erro.

### Resultado Obtido
✅ PASSOU

---

## C3 — Logout

### Objetivo
Validar encerramento correto da sessão do usuário.

### Passos
1. Realizar login.
2. Abrir menu lateral.
3. Selecionar opção Logout.

### Resultado Esperado
O sistema deve encerrar a sessão e retornar para a tela de login.

### Resultado Obtido
✅ PASSOU

---

## C4 — Controle de acesso à Dashboard

### Objetivo
Validar proteção da Dashboard para usuários não autenticados.

### Passos
1. Realizar logout.
2. Inserir diretamente a URL da Dashboard.

### Resultado Esperado
O sistema deve impedir acesso direto e redirecionar para a página de login.

### Resultado Obtido
✅ PASSOU

---

## C5 — Persistência da sessão após atualização

### Objetivo
Validar manutenção da sessão ativa após atualização da página.

### Passos
1. Realizar login.
2. Acessar Dashboard.
3. Atualizar página (F5).

### Resultado Esperado
O usuário deve permanecer autenticado sem necessidade de novo login.

### Resultado Obtido
✅ PASSOU

---

## C6 — Persistência do carrinho

### Objetivo
Validar comportamento do carrinho após múltiplas interações.

### Passos
1. Realizar login.
2. Adicionar múltiplos produtos ao carrinho.
3. Navegar entre páginas.
4. Atualizar a página.

### Resultado Esperado
Os produtos adicionados devem permanecer no carrinho.

### Resultado Obtido
✅ PASSOU

---

# Resumo da Execução

| ID | Cenário | Status |
|-----|---------|--------|
| C1 | Login válido | ✅ Passou |
| C2 | Login inválido | ✅ Passou |
| C3 | Logout | ✅ Passou |
| C4 | Controle de acesso à Dashboard | ✅ Passou |
| C5 | Persistência da sessão | ✅ Passou |
| C6 | Persistência do carrinho | ✅ Passou |

---

## Ambiente

- Aplicação: SauceDemo
- Tipo de teste: Manual
- Categoria: Funcional / Sistema / UI (End-to-End)
