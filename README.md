
print ('ola mundo')
name = input ('qualo seu nome:')
idade = int (input ('qual o ano de nascimento:'))
cidade = input ('qual a sua cidade:')
calculo = 2026 - idade

print ('infomacoes salva',name,'sua idade aproximanda e',calculo,' anos,',
      cidade,' seu local de nascimento')

arquivo  = open ('cadrastro.txt', 'w')

arquivo.write('Nome: ' + name + '\n')
arquivo.write('Idade: ' + str(calculo) + '\n')
arquivo.write('Cidade: ' + cidade + '\n')
