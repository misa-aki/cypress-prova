# cypress-prova


Projeto de testes automatizados para o site [SauceDemo](https://www.saucedemo.com/) usando Cypress.

### Cenários Testados

*   Login com usuário e senha válidos.
*   Tentativa de login com senha inválida.
*   Tentativa de login com usuário inválido.
*   Adicionar um produto ao carrinho após o login.

### Requisitos

*   Node.js

### Como Instalar

1.  Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/seu-repositorio.git
    ```
2.  Acesse o diretório do projeto:
    ```bash
    cd seu-repositorio
    ```
3.  Instale as dependências:
    ```bash
    npm install
    ```

### Como Rodar os Testes

Para abrir a interface do Cypress e executar os testes:
```bash
npx cypress open
```

Para executar os testes diretamente no terminal (modo headless):
```bash
npx cypress run
```

### Integração Contínua (CI)

Atenção: A pipeline de integração contínua (CI) não está funcionando corretamente no momento. A correção está pendente.
