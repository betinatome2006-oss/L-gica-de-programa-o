 Logica-de-programação
Utilizo da linguagem Python para começar o aprendizado em programação, uma linguagem básica mas que abre caminhos para as demais linguagens dessa área. Até o momento, já entendo e utilizo os comandos while Thue, (if,elif,else), for..in range e def.
ct = 0
print('Numeros naturais')
print('Quantidade de valores:')
for numero in range (20,-1,-1 ):
    ct = ct + 1
    print(numero)
    print('Fim')
    print('Quantidade:' , ct)
[provapratica3.2.py](https://github.com/user-attachments/files/33452911/provapratica3.2.py)ct = 0
ct_menos_5 = 0
ct_5_ate_10 = 0
ct_10_ou_mais = 0
salario_minimo = 1621
valor_total = 0
print('Digite [0] para sair da repetição:')
while True:
    salario=float(input('Digite o salario:'))
    if salario == 0 :
       break
    ct = ct + 1
    valor_total = salario + valor_total
    if salario < salario_minimo * 5 :
        ct_menos_5 = ct_menos_5 + 1
    elif salario < salario_minimo *10 :
        ct_5_ate_10 = ct_5_ate_10 + 1
    else:
        ct_10_ate_mais = ct_10_ou_mais + 1
print('\nQuantidade:' , ct)
print('\nSalario menor que 5 salarios minimos:' , ct_menos_5)
print('\nSalario de 5 ate 10 salarios minimos:' , ct_5_ate_10)
print('\nSalario de 10 a mais salarios minimos:' , ct_10_ou_mais)
print('\nValor total:' , valor_total)

[provapratica5q2.py](https://github.com/user-attachments/files/33453572/provapratica5q2.py)
[provapratica4_3.py](https://github.com/user-attachments/files/33453588/provapratica4_3.py)
