# Exemplo básico de Aplicativo descentralizado na Web 3.0

#### O Que é um DApp?

Ao contrário de aplicativos da **Web 2.0** como o Medium, a **Web 3.0** elimina o intermediário. Não há banco de dados centralizado que armazene o estado do aplicativo e não há servidor Web centralizado onde reside a lógica de back-end.
<br>
Em vez disso, você pode aproveitar o **blockchain** para criar aplicativos em uma máquina de estado descentralizada que é mantida por nós anônimos na Internet.
<br>
Blockchains são máquinas de estado que são instanciadas com algum estado de gênese e possuem regras muito rígidas (ou seja, consenso) que definem como esse estado pode fazer a transição. Ela é mantida coletivamente por todos na rede.

<br>
Queremos que nosso **frontend** se comunique com nossos contratos inteligentes para que eles possam invocar funções, mas lembre-se de que o *Ethereum* é uma rede descentralizada. Cada nó na rede *Ethereum* mantém uma cópia de todos os estados na máquina de estado *Ethereum*, incluindo o código e os dados associados a cada contrato inteligente.

<br>
Quando queremos interagir com os dados e o código em uma blockchain, precisamos interagir com um desses nós. Isso ocorre porque qualquer nó pode transmitir uma solicitação para que uma transação seja executada no **EVM**. Um minerador executará a transação e propagará a mudança de estado resultante para o resto da rede.


<br>
<br>
Este projeto demonstra um caso de uso básico com **Hardhat**. Ele vem com um contrato de amostra, um teste para esse contrato, um script de amostra que implanta esse contrato e um exemplo de implementação de tarefa, que simplesmente lista as contas disponíveis.
<br>


Tente executando as seguintes tarefas:

```shell
npx hardhat compile
npx hardhat accounts
npx hardhat clean
npx hardhat test
npx hardhat node
node scripts/sample-script.js
npx hardhat help
```
