for i in range(6):
    nome = input('nome: ')
    if nome.isdigit():
        print('cusujo')
        break
    else:
        pass
    idd = input('idade: ')
    try:
        idd = int(idd)
    except:
        print('idade invalida.')
        break
    altura = input('altura: ')
    try: 
        altura = float(altura)
    except:
        print("altura invalida.")
        break
    peso = input('peso: ')
    try:
        peso = float(peso)
    except:
        print("peso invalido.")
        break
    
imc = peso / altura**2
if imc < 18,5:
    imc = mm
elif 18,5 <= imc < 25:
    imc = ok
elif 25 <= imc < 30:
    imc = g
elif 30 <= imc < 35:
    imc = gg
elif 35 <= imc < 40:
    imc = xgg
elif 40 <= imc:
    imc = ugg
    
    
    
    
    
    
    
    
    
    
    
    
    
    
    
