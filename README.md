# -Modelando o Sistema Bancrio em POO com Python

Desafio: Construindo um Sistema Bancário

Crie um sistema bancário com as operações: saque, depósito e visualização de extrato. Fomos contratados por um grande banco para desenvolver seu novo sistema. Este banco pretende modernizar suas operações e escolheu a linguagem Python para esse fim. Para a primeira versão do sistema, devemos implementar apenas 3 operações: depósito, saque e visualização de extrato.

Regras
Deveria ser possível depositar valores positivos em minha conta bancária. A versão 1 do projeto funciona apenas com 1 usuário, portanto não precisamos nos preocupar em identificar o número da conta e agência. Todos os depósitos devem ser armazenados em uma variável e exibidos na operação do extrato.

O sistema deve permitir 3 saques por dia com limite máximo de US$ 500,00 por saque. Caso o usuário não tenha saldo suficiente na conta, o sistema deverá exibir uma mensagem indicando que não é possível sacar o dinheiro por saldo insuficiente. Todos os saques devem ser armazenados em uma variável e exibidos na operação do extrato.

Esta operação deverá listar todos os depósitos e saques realizados na conta. Ao final da listagem deverá ser exibido o saldo da conta corrente. Se o extrato estiver em branco, exibe a mensagem: Nenhuma transação foi realizada. Os valores deverão ser exibidos no formato $xxx.xx, por exemplo: 1500,45 = $1500,45.
