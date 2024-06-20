### Cadastro de Vinhos

#### Descrição
Este projeto consiste em um programa simples para cadastro, listagem, pesquisa e cálculo estatístico de vinhos. Utiliza Node.js com o prompt-sync para interação via terminal.

#### Funcionalidades Principais
1. **Inclusão de Vinhos**
   - Permite adicionar novos vinhos especificando marca, tipo e preço.

2. **Listagem de Vinhos**
   - Exibe todos os vinhos cadastrados em formato tabular, mostrando marca, tipo e preço.

3. **Pesquisa por Tipo**
   - Permite buscar vinhos cadastrados por tipo, exibindo marca, tipo e preço dos vinhos encontrados.

4. **Média e Destaques**
   - Calcula e exibe o preço médio dos vinhos cadastrados, além do vinho com menor e maior preço.

#### Estrutura do Código
- **Funções:**
  - `titulo(texto)`: Exibe um título formatado no console.
  - `incluir()`: Permite a inclusão de novos vinhos no cadastro.
  - `listar()`: Lista todos os vinhos cadastrados.
  - `pesquisar()`: Permite buscar vinhos por tipo.
  - `calcularMedia()`: Calcula a média de preços e identifica os vinhos com menor e maior preço.

- **Programa Principal:**
  - Um loop principal que apresenta um menu de opções para o usuário escolher a operação desejada.
  - Utilização de condicionais para chamar as funções correspondentes a cada opção selecionada.

#### Uso
Para executar o programa:
1. Clone o repositório ou copie o código para um arquivo local com extensão `.js`.
2. Certifique-se de ter o Node.js instalado.
3. Instale o `prompt-sync` com `npm install prompt-sync`.
4. Execute o programa com `node nome-do-arquivo.js`.

#### Exemplo de Execução
```
===< Cadastro de Vinhos >==
1. Inclusão de Vinhos
2. Listagem de Vinhos
3. Pesquisa por Tipo
4. Média e Destaques
5. Finalizar
Opção: 2

===< Lista de Vinhos Cadastrados >===
Marca............... Tipo............... Preço R$:
ExemploMarca          Tinto               50.00
OutraMarca            Branco              30.00

Opção: 3

===< Pesquisa por Tipo de Vinho >===
Tipo: Tinto
Marca.............. Tipo............... Preço R$:
ExemploMarca          Tinto               50.00

===< Cadastro de Vinhos >==
1. Inclusão de Vinhos
2. Listagem de Vinhos
3. Pesquisa por Tipo
4. Média e Destaques
5. Finalizar
Opção: 4

===< Média e Destaques do Cadastro de Vinhos >===
Preço Médio dos Vinhos R$: 40.00
Menor Valor R$: 30.00 - OutraMarca
Maior Valor R$: 50.00 - ExemploMarca

===< Cadastro de Vinhos >==
1. Inclusão de Vinhos
2. Listagem de Vinhos
3. Pesquisa por Tipo
4. Média e Destaques
5. Finalizar
Opção: 5
```

#### Contribuição
Contribuições são bem-vindas. Sinta-se à vontade para melhorar e expandir este projeto.

---
