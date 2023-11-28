# Sistema Bancário em C++ 🏦

Este projeto é um sistema bancário simples implementado em C++. Ele simula as operações básicas de um banco, permitindo ao usuário criar uma conta, verificar o saldo, depositar dinheiro, sacar dinheiro e transferir dinheiro entre contas.

## Componentes Principais

### Classes de Conta

O projeto inclui várias classes que representam diferentes tipos de contas bancárias. Cada tipo de conta tem suas próprias características e comportamentos específicos.

- `ContaBancaria`: Esta é a classe base para todas as contas. Ela define os atributos e métodos comuns a todas as contas, como o número da conta e o saldo.
- `ContaCorrente` e `ContaPoupanca`: Estas são subclasses da classe `ContaBancaria`. Elas representam tipos específicos de contas e podem ter comportamentos adicionais específicos para esse tipo de conta.

### Classe Banco

A classe `Banco` atua como o gerenciador para todas as contas bancárias no sistema. Ela mantém um registro de todas as contas e fornece métodos para realizar várias operações bancárias.

- `addAccount()`: Este método é usado para adicionar uma nova conta ao banco.
- `deposit()`, `withdraw()` e `transfer()`: Estes métodos são usados para depositar dinheiro em uma conta, sacar dinheiro de uma conta e transferir dinheiro entre contas, respectivamente.
- `getAccount()`: Este método é usado para obter uma conta específica com base no número da conta.

### Funções de Menu

O projeto inclui várias funções para exibir um menu ao usuário e realizar ações com base na opção selecionada pelo usuário.

- `menu()`: Esta função exibe o menu principal ao usuário e retorna a opção selecionada pelo usuário.
- `criarConta()`: Esta função é chamada quando o usuário seleciona a opção para criar uma nova conta. Ela solicita ao usuário que selecione o tipo de conta e, em seguida, cria a conta apropriada.
- `depositar()`, `sacar()` e `transferir()`: Estas funções são chamadas quando o usuário seleciona a opção para depositar dinheiro em uma conta, sacar dinheiro de uma conta ou transferir dinheiro entre contas, respectivamente.
- `verificarSaldo()`: Esta função é chamada quando o usuário seleciona a opção para verificar o saldo de uma conta.

### Função Principal

A função `main()` é o ponto de entrada do programa. Ela cria um objeto da classe `Banco` e, em seguida, entra em um loop onde exibe o menu ao usuário e realiza ações com base na opção selecionada pelo usuário.

## Como Usar

Para usar este sistema bancário, você precisa compilar e executar o código. Depois disso, você pode interagir com o sistema através do menu exibido no console. As opções do menu permitem que você crie uma nova conta, verifique o saldo de uma conta, deposite dinheiro em uma conta, saque dinheiro de uma conta e transfira dinheiro entre contas.

## Contribuição
Contribuições são bem-vindas. Sinta-se à vontade para abrir uma issue ou enviar um pull request.

## Licença
Este projeto está licenciado sob a licença MIT.
