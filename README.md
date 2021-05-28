# Sistema Banco Para Avaliacao
*Código final para avaliação de Programação Orientada a Objetos.*


### 🔨Criação de classes
- [x] Cliente</br>
- [x] Conta</br>
- [x] Conta Corrente</br>
- [x] Conta Poupança</br>
✔Funcionário</br>
- [x] Gerente</br>
- [x] Diretor</br>
- [x] Presidente</br>
✔Sistema Interno (main)</br>
- [x] Login</br>
- [x] CFP</br>
- [x] Senha</br></br>
### 🖋Descrição das Classes
#### 💼Conta 
- [x] Deve ser abstrata;</br>
- [x] Deve conter atributos CPF e agência do titular para relacionar a conta com o usuário logado e saldo.</br>
#### 💼Conta Corrente e Poupança
- [x] Deve herda os atributos e métodos da classe conta;</br>
- [x] Devem conter atributo 'tipo' para identificação do tipo de conta.</br>
#### 🧑‍Funcionário
- [x] Deve ser abstrata;</br>
- [x] Deve conter CPF e senha para login;</br>
- [x] Deve ter um atributo cargo.</br>
#### 🧑‍Gerente
- [x] Deve conter o atributo de identificação da agência, responsável por gerir.</br></br>
### 🔑Sistema características gerais
- [x] Menu interativo;</br>
- [x] É esperado que seja populado com os valores referentes aos clientes: contas e funcionários;</br>
~- [ ] O sistema deve guardar os dados em um arquivo de texto.~</br></br>
### 🦥Passos de execução do Sistema
- [x] Menu inicial: fornecer CPF e Senha para login;</br>
- [x] Deve ser capaz de identificar se o usuário é um cliente, gerente, diretor ou presidente;</br></br>
### 📌Casos
#### 🧍Cliente
Movimentação na conta</br>
- [x] Saque;</br>
- [x] Depósito;</br>
- [x] Transferência.</br>
#### 📃Relatório
- [x] Exibir saldo na tela;</br>
- [x] Exibir relatório de tributação, que devera apresentar: total de gastos nas operações ate o momento de impressão;</br>
- [x] Deve ser informado o valor de taxas por operação: Saque R$ 0,10 - Depósito R$ 0,10 - Transferência R$ 0,20);</br>
- [x] Deve ser cobrado apenas do remetente.</br>
#### 📃Relatório de rendimento da poupança
- [x] Simular rendimento da poupança em um prazo informado, o cliente deve informar o valor e quantidade de dias.
#### 🧑📃Gerente
- [x] Relatório devera ser igual ao do cliente, com acréscimo das seguintes informações: numero de contas na mesma agência que este gerente trabalha.</br>
#### 👨‍📃Diretor
- [x] Relatório devera ser igual ao do gerente, com acréscimo das seguintes informações: nome, CPF, agência de todos os clientes do sistema em ordem alfabética.</br>
#### 👨‍⚖📃Presidente
- [x] Relatório devera ser igual ao do diretor, com acréscimo das seguintes informações: valor total do capital do banco.</br></br>
### ⚠Obs: Restrições
~- [ ] As operações de saque, depósito e transferência, devem ter registro em um arquivo de texto de saída que armazena as operações realizadas durante a execução;~</br>
~- [ ] Todos os relatórios devem ter registro em um arquivo de texto individual;~</br>
- [x] O sistema deve realizar no mínimo um tratamento de erro personalizado
- [x] Sugestão: Tentativa de depósito indevida (valores negativos).</br></br>
### 🔃Exeption
- [x] Implementar;</br>
- [x] Refatorar;</br>
- [x] Testar.</br></br>
### ⚡Desafio 
#### ⚰Seguro de vida
- [x] Criar uma classe seguro de vida;</br>
- [x] Deve ser contratado pelo cliente que ira informar: o valor a ser assegurado, a contratação custara 20% do valor contratado;</br> 
- [x] O valor devera ser incluído no relatório de tributação.</br> </br> 
### 🚨Revisão
- [x] Conferir com o prof. se o projeto esta atendendo aos requisitos;</br>
- [x] Positivo, tudo dentro do pedido. -[ ] Negativo, mudanças necessárias.</br>
   * ***Em caso 'Negativo', listar as modificação nesta área ou criar nova 'issues' com o link logo abaixo.***</br></br>
### 😭Não implementado🤯</br>
***Caso algum requisito não tenha sua implementação por motivo de data limite, listar nesse local para futura realização.***
* O sistema deve guardar os dados em um arquivo de texto;</br>
* As operações de saque, depósito e transferência, devem ter registro em um arquivo de texto de saída que armazena as operações realizadas durante a execução;</br>
* Todos os relatórios devem ter registro em um arquivo de texto individual.</br></br>
### 🧪Teste geral de funcionamento
- [x] Refatorar todo código;</br>
- [x] ❤OK, sistema funcionando e pronto para avaliação;</br>
- [x] Entregue. Não deu para fazer tudo, mas também não é de jogar fora.</br></br>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![mDlZnB](https://user-images.githubusercontent.com/57602117/117394985-92d6a000-aecd-11eb-8099-b19385405fa6.gif)

