# Caixa-eletr-nico Caixa Eletrônico 🏦
📖 Descrição

Este programa em Python simula um caixa eletrônico.
Ele recebe um valor solicitado para saque (mínimo R$ 2) e calcula automaticamente a quantidade de cada nota necessária para compor o valor, sempre priorizando as de maior valor.

🚀 Como funciona

O usuário digita o valor que deseja sacar.

O programa valida se o valor é maior ou igual a R$ 2.

O algoritmo faz a divisão inteira e calcula o resto sucessivamente para determinar a quantidade de cada nota:

R$ 100

R$ 50

R$ 20

R$ 10

R$ 5

R$ 2

O resultado é exibido mostrando apenas as notas que foram utilizadas no saque.

📂 Exemplo de uso

Entrada no terminal:

Digite um valor para saque(minimo R$ 2): 286


Saída:

=== saque realizado com sucesso ===
notas de 100: 2
notas de 50: 1
notas de 20: 1
notas de 10: 1
notas de 5: 1
notas de 2: 0

⚠️ Observações

O programa não trabalha com moedas, apenas com notas.

Valores como R$ 1 ou R$ 3 não podem ser sacados, pois não há notas correspondentes.
