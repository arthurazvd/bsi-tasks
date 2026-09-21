# Tarefa 01 - Teste de Unidade, Integração, Cobertura e CI

**Nome:** Arthur Azevêdo  
**GitHub:** arthurazvd  
**E-mail:** azvd.arthur@gmail.com  
**Projeto:** [Comercializa](https://github.com/arthurazvd/comercializa)

## 1. Testes de Software e Testes de Unidade

Testes de software são procedimentos utilizados para verificar se um sistema se comporta conforme o esperado e para identificar falhas antes que elas cheguem ao usuário. Eles ajudam a aumentar a confiabilidade do código e facilitam futuras alterações.

Os testes de unidade verificam pequenas partes do sistema de forma isolada, como funções, métodos ou classes. Dependências externas, como banco de dados ou serviços, podem ser substituídas por mocks. Dessa forma, o teste fica mais rápido e permite identificar com precisão em qual unidade ocorreu uma falha.

## 2. Linguagem e stack

O projeto Comercializa utiliza **Python** no backend, com **Django**, **Django REST Framework** e banco de dados **SQLite**. No frontend são utilizados **JavaScript**, **Vue 3**, **Vite** e **Axios**. Para os testes do backend são utilizados **pytest**, **pytest-django**, **pytest-cov**, **factory-boy** e `unittest.mock`.

## 3. Framework de Testes de Unidade

O framework escolhido foi o **pytest**. Ele permite escrever testes de forma simples utilizando funções e instruções `assert`, possui descoberta automática dos arquivos de teste e oferece suporte a fixtures e plugins. Neste projeto, o `pytest-django` permite testar componentes do Django e o `pytest-cov` calcula a cobertura do código.

- [Documentação do pytest](https://docs.pytest.org/)
- [Documentação do pytest-django](https://pytest-django.readthedocs.io/)
- [Documentação do pytest-cov](https://pytest-cov.readthedocs.io/)

## 4. IDE e ferramentas de debug

Utilizo o **Visual Studio Code**. A IDE possui suporte à depuração de Python por meio de breakpoints, execução passo a passo, inspeção de variáveis, pilha de chamadas e console de depuração. Também permite executar e depurar testes individualmente pela interface de testes. Para o frontend, as ferramentas do navegador ajudam a inspecionar componentes, requisições HTTP e mensagens do console.

- [Documentação de depuração em Python no VS Code](https://code.visualstudio.com/docs/python/debugging)