# Exemplo básico de Aplicativo descentralizado na Web 3.0
<br>
<br>
<br>

### O Que é Blockchain?

<br>
O blockchain é um protocolo de registro distribuído. Cada bloco que faz parte da cadeia é protegido por um código criptografado e armazena uma informação (como uma transação financeira). Quando ele é validado e se junta aos demais blocos, ganha um registro permanente e não pode ser alterado. Vale lembrar que os blocos são adicionados à blockchain de modo linear e cronológico.

<br>

A grande vantagem da blockchain é que duas partes podem fazer uma transação sem a necessidade de intermediários. Isso garante agilidade e custos menores.

<br>
<br>
<br>

### O Que são contratos inteligentes?

<br>

Contratos inteligentes são linhas de código armazenadas em blockchain e executadas automaticamente quando termos e condições pré-determinados são atendidos. Basicamente, são programas executados conforme foram configurados pelos desenvolvedores. Os benefícios dos contratos inteligentes são mais aparentes nas colaborações comerciais, nas quais geralmente são usados para impor algum tipo de acordo para que todos os participantes possam ter certeza do resultado sem o envolvimento de um intermediário.

<br>
<br>

O que os contratos inteligentes fazem é simplificar esse processo complexo que envolve vários intermediários devido à falta de confiança entre os participantes da transação. Com sua identidade armazenada em um blockchain, os credores podem tomar rapidamente uma decisão sobre crédito. Em seguida, seria criado um contrato inteligente entre o seu banco, o revendedor e o credor para que, uma vez liberados os fundos, o credor mantenha o título do carro e o pagamento seja iniciado com base nos termos acordados. A transferência de propriedade seria automática, já que a transação é gravada em um blockchain e compartilhada entre os participantes e pode ser verificada a qualquer momento.

<br>
<br>
<br>

### O Que é um DApp?

<br>
Ao contrário de aplicativos da **Web 2.0** como o Medium, a **Web 3.0** elimina o intermediário. Não há banco de dados centralizado que armazene o estado do aplicativo e não há servidor Web centralizado onde reside a lógica de back-end.
<br>
Em vez disso, você pode aproveitar o **blockchain** para criar aplicativos em uma máquina de estado descentralizada que é mantida por nós anônimos na Internet.
<br>
<br>
Blockchains são máquinas de estado que são instanciadas com algum estado de gênese e possuem regras muito rígidas (ou seja, consenso) que definem como esse estado pode fazer a transição. Ela é mantida coletivamente por todos na rede.

<br>
<br>
Queremos que nosso **frontend** se comunique com nossos contratos inteligentes para que eles possam invocar funções, mas lembre-se de que o *Ethereum* é uma rede descentralizada. Cada nó na rede *Ethereum* mantém uma cópia de todos os estados na máquina de estado *Ethereum*, incluindo o código e os dados associados a cada contrato inteligente.

<br>
Quando queremos interagir com os dados e o código em uma blockchain, precisamos interagir com um desses nós. Isso ocorre porque qualquer nó pode transmitir uma solicitação para que uma transação seja executada no **EVM**. Um minerador executará a transação e propagará a mudança de estado resultante para o resto da rede.


<br>
<br>
Este projeto demonstra um caso de uso básico com **Hardhat**. Ele vem com um contrato de amostra, um teste para esse contrato, um script de amostra que implanta esse contrato e um exemplo de implementação de tarefa, que simplesmente lista as contas disponíveis.
<br>
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

<br>
<br>
Mais sobre blockchain com as fontes: 

https://www.tecmundo.com.br/software/176575-contratos-inteligentes-blockchain.htm
https://hardhat.org/guides/project-setup.html
https://www.preethikasireddy.com/post/the-architecture-of-a-web-3-0-application
https://blog.suhailkakar.com/setup-and-build-your-first-web-3-application