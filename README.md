# ContaBanco

Programa de terminal em Java que simula a abertura de uma conta bancária. O usuário informa número da conta, agência, nome e saldo, e o programa exibe uma mensagem de confirmação com esses dados.

## Como rodar

Requer Java (JDK 8 ou superior).

```bash
javac -d bin src/ContaTerminal.java
java -cp bin ContaTerminal
```

## Exemplo

```
Por favor, digite o número da conta: 
1021
Por favor, digite o número da agência: 
067-8
Por favor, digite o nome do cliente: 
Mario Andrade
Por favor, digite o saldo da conta: 
237.48
Olá Mario Andrade, obrigado por criar uma conta em nosso banco. Sua agência é 067-8, conta 1021 e seu saldo 237.48 já está disponível para saque.
```
