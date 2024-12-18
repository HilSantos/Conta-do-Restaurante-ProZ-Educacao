# Conta-do-Restaurante-ProZ-Educacao
Almoço favorito, preço do almoço e orçamento. Imprimir a soma dos dois preços, diferença entre orçamento e o valor total. Concatenar uma string e o valor da variedade, depois declare variáveis para sua sobremesa favorita, o preço dela, e a quantidade de convidados. Na sequência, imprima o novo valor total e o valor a ser pago por cada convidado.

<classe 'str'>
<classe 'float'>
<classe 'int'>
Meu almoço favorito é strogonoff
25.01

almoco_favorito = "strogonoff"
print(type(almoco_favorito))

preco_almoco = 24.99
print(type(preco_almoco))

meu_orcamento = 50
print(type(meu_orcamento))

print("Meu almoço favorito é " + almoco_favorito)

print(meu_orcamento - preco_almoco)

<classe 'str'>
<classe 'float'>
<classe 'int'>
Gastamos no total 65,5

sobremesa_fav = "cookie"
print(type(sobremesa_fav))

valor_unitario = 5.5
print(type(valor_unitario))

quantidade_conv = 60
print(type(quantidade_conv))

print("Gastamos no total ", valor_unitario + quantidade_conv)

meuOrcamento = 35.50
contaFinal = 87.75
valorDiv = contaFinal / 4

if(meuOrcamento < contaFinal):
  print("Vamos dividir a Conta!")
elif(meuOrcamento <= 0):
  print("Poxa, vocês não vão acreditar...")
