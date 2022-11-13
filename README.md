 1
A=(B+b).h
    2
A=(20+12).15
     2
A=32.15
    2
A=495
   2
A= 240




2

def somaImposto(taxaImposto, Custo):
    returm (1 + taxaImposto/100)*Custo
t = float(input('Digite a taxa de imposto: '))
c = float(input('Digite o custo: '))
print('Valor com imposto:', somaImposto(t,c))



3

def converta(h, m):
    if 0 < h <= 12 and 0 < m < 60:
       print(f' {h}:{m} AM')
    elif 12 < h < 24 and 0 < m < 60:
       print(f' {h - 12}:{m} PM')
    else:
       print('Valor inválido')


while True:
    h = int(input('Hora: '))
    if h == 999: break
    m = int(input('Minuto: '))
    converta(h,m)
    print('='*12)
