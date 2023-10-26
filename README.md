# desafio-qa-dio
Caso real de desafio de projeto

# Projeto de Teste: Cadastro de Novos Produtos

Este projeto demonstra como levantar e planejar os testes para uma user story de cadastro de novos produtos em um site de comércio eletrônico.

## User Story

Como usuário, quero poder cadastrar um novo produto no site, para que eu possa vender meus produtos online.

## Mind Map

![Mind Map](images/mind-map.png)



**Requisitos:**

- O produto deve ter um nome
- O produto deve ter uma descrição
- O produto deve ter um preço
- O produto deve ter uma imagem

**Cenários:**

- O usuário fornece todos os dados necessários para o cadastro do produto
- O usuário fornece apenas alguns dos dados necessários para o cadastro do produto
- O usuário fornece dados inválidos para o cadastro do produto

**Testes:**

### Caso de Teste 1 (Step-by-Step):

1. O usuário acessa a página de cadastro de produtos.
2. O usuário preenche todos os campos obrigatórios.
3. O usuário clica no botão "Cadastrar".
4. O produto é cadastrado com sucesso.

### Caso de Teste 2 (BDD):

```gherkin
Dado que um usuário está na página de cadastro de produtos
Quando o usuário preenche todos os campos obrigatórios
Então o produto deve ser cadastrado com sucesso
```

### Ciclo de Testes
Plano de Execução:
Preparar o ambiente
Executar os testes
Registrar os resultados
Resultados:
Todos os testes foram executados com sucesso.

### Documentação
Mind Map
Casos de Teste (Step-by-Step e BDD)
Plano de Execução do Ciclo de Testes

### Como Executar os Testes
Para executar os testes, siga estas etapas:
```
1. Clone o repositório do projeto.
2. Instale as dependências do projeto.
3. Execute o script de teste.

O script de teste irá executar todos os testes especificados no plano de execução.
```

### Visualização dos Resultados dos Testes
Os resultados dos testes são registrados em um relatório de testes. O relatório de testes inclui informações sobre cada teste, incluindo o resultado do teste e qualquer mensagem de erro.

Para visualizar os resultados dos testes, abra o relatório de testes no editor de texto.

### Conclusão

Este projeto de teste demonstra como levantar e planejar os testes para uma user story de cadastro de novos produtos. O plano de testes inclui elementos como um mind map, casos de teste detalhados e um ciclo de testes para garantir que o cadastro de produtos funcione corretamente.

