# 1 - Template de Reporte dos Testes 

- **Data da identificação:** 09/05/2024
- **Navegador utilizado:** Google Chrome
- **Ambiente:** Usuário/Cliente do site Casa & Vídeo

### Teste 01

- **Nome do requisito:** Cadastro de usuário
- **Cenário de teste:** Cadastro de conta usando dados válidos
- **Resultado obtido:** O site realizou o cadastro com sucesso, porém não foi mostrada uma mensagem de cadastro realizado com sucesso.
- **Status:** Passou
![Print da tela01](https://i.imgur.com/ZhEApu9.jpeg)

### Teste 02

- **Nome do requisito:** Cadastro de usuário
- **Cenário de teste:** Cadastro de conta usando um e-mail falso
- **Resultado obtido:** Usando o email falso: exemplo@mail.com, o site entende como um email existente.
- **Status:** Falhou
- **Nível de criticidade:** Alta
![Criação da conta pelo email falso](https://i.imgur.com/fJnnpWK.png)


### Teste 03

- **Nome do requisito:** Cadastro de usuário
- **Cenário de teste:** Cadastro com senha que não correspondem
- **Resultado obtido:** Usando uma senha diferente da outra o site passa a seguinte mensagem: confirmação de senha incorreta. 
- **Status:** Passou
![Senhas não correspondente](https://i.imgur.com/BXHLYX0.png)


### Teste 04

- **Nome do requisito:** Cadastro de usuário
- **Cenário de teste:** Cadastro com senha "fraca"
- **Resultado obtido:** O site possui um sistema de validação de senha e por isso não autoriza a criação de contas quando as senhas não preenchem os requisitos de senha "forte".
- **Status:** Passou
![Senha "fraca"](https://i.imgur.com/5SIwaah.png)

### Teste 05

- **Nome do requisito:** Carrinho de compras 
- **Cenário de teste:** Testar a funcionalidade do carrinho
- **Resultado obtido:** Ao adicionar produtos no carrinho a funcionalidade funciona corretamente. Só não exibe a mensagem "produto adicionado com sucesso!"
- **Status:** Passou

### Teste 06

- **Nome do requisito:** Carrinho de compras 
- **Cenário de teste:** Testar se é possivel editar a quantidade de produtos no carrinho
- **Resultado obtido:** Ao adicionar mais quantidades do mesmo produto ocorre um bug no carrinho. Ele automaticamente adiciona o mesmo produto novamente no carrinho, ou seja, existem 2 PS5 no carrinho sendo um deles com quantidade 5 e outro com 1 somente.
- **Status:** Falhou
- **Nível de criticidade:** Média
![Bug de duplicidade do produto](https://i.imgur.com/8MTwi87.jpeg)

### Teste 07

- **Nome do requisito:** Carrinho de compras 
- **Cenário de teste:** Testar se é possivel retirar produtos do carrinho
- **Resultado obtido:** A função de remover o produto não está operando corretamente após a ocorrência do bug anterior. O produto duplicado permanece no carrinho, enquanto a remoção é aplicada apenas a um dos cinco outros consoles PS5. No entanto, quando a quantidade é reduzida para 1, tanto o produto duplicado quanto o original não são removidos do carrinho.
- **Status:** Falhou
- **Nível de criticidade:** Média
![Bug de excluir o produto](https://i.imgur.com/a77UlGd.png)

### Teste 08

- **Nome do requisito:** Carrinho de compras 
- **Cenário de teste:** Testar se é possivel fazer o checkout
- **Resultado obtido:** Logo após adicionar os produtos no carrinho a função de checkout funciona corretamente, te redirecionando para o pagamento.
- **Status:** Passou

### Teste 09

- **Nome do requisito:** Exibição Correta do Catálogo de Produtos
- **Cenário de teste:** Verificar se o site apresenta o Catálogo correto de Produtos
- **Resultado obtido:** Ao realizar o teste, observou-se que na categoria de SMART TV, um produto denominado 'SMART' não corresponde a uma TV, mas sim a um aspirador.
- **Status:** Falhou
- **Nível de criticidade:** Baixa
![Texto Alternativo](https://i.imgur.com/VZ3GFoj.jpeg)

### Teste 10

- **Nome do requisito:** Exibição Correta do Catálogo de Produtos
- **Cenário de teste:** Verificar se o site identifica corretamente os produtos disponiveis dos indisponiveis 
- **Resultado obtido:** Ao realizar o teste, foi constatado que todos os produtos exibidos no site estão disponíveis em estoque. No entanto, o sistema não apresenta os produtos fora de estoque, deixando de exibir a mensagem ou observação "Fora de estoque". Isso resulta na visualização apenas dos produtos que estão atualmente em estoque no catálogo.
- **Status:** Passou

### Teste 11

- **Nome do requisito:** Produtos com desconto
- **Cenário de teste:** Verificar se o site apresenta o desconto correto do produto dentro do carrinho 
- **Resultado obtido:** Ao clicar em um produto promovido com desconto no site, a exibição dos preços, tanto antes quanto depois de adicioná-lo ao carrinho, é correta e reflete com precisão os valores promocionais.
- **Status:** Passou
# 2 - Componentes:

| Aluno                        | Professora                | Turma | Disciplina                     |
| ---------------------------- | ------------------------- | ----- | ------------------------------ |
| João Victor Piumbini Cheroto | Gabriela Martins de Jesus | CC5N  | Qualidade e Testes de Software |
| Rodrigo da Cunha             | Gabriela Martins de Jesus | CC5N  | Qualidade e Testes de Software |
| Luiz Fernando Sacht          | Gabriela Martins de Jesus | CC5N  | Qualidade e Testes de Software |
