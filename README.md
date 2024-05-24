faturamento=1000 #int para numeros inteiros
custo=720
taxa_imposto=0.1 #porcentagem vai para decimal,(float)
novas_vendas=300
lucro=faturamento
faturamento=faturamento+novas_vendas
mensagem=("o faturamento foi de 1000")
print("faturamento",faturamento)
print("custo",custo)
print("lucro",faturamento-custo)
print("mensagem")
margem_lucro=lucro / faturamento
faturamento=1000
custo=700
novas_vendas=300
faturamento=faturamento + novas_vendas
lucro=faturamento - custo #subtrair
print(faturamento)
print(lucro)
margem_lucro=lucro/faturamento #dividir
print(margem_lucro)
#mod resto da divisao
#10 % 3 5=mod
tempo_em_meses=160
tempo_em_anos=int(tempo_em_meses/12)
print(tempo_em_anos,"anos")
print(tempo_em_meses %12,"meses")

