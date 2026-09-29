# **Calculador de Média**
 **uma calculadora que pega notas as soma e divide para dar uma média**

```

### **Técnologias Utilizadas**
 ***Python***

***
def calcular_media(nota1, nota2):
    return (nota1 + nota2) / 2

print("=== Sistema De Notas do Aluno ===")
n1 = float(input("digite a primeira nota:"))
n2 = float(input("digite a segunda nota:"))
media = calcular_media(n1, n2)
print(f"A média final é: {media:.2f}")

if media >= 7.0:
    print("Status: APROVADO!")
else:
    print("status: REPROVADO.")


***


PS C:\Users\TIAGOSILVA\Documents\aula_git28092026>  c:; cd 'c:\Users\TIAGOSILVA\Documents\aula_git28092026'; & 'c:\Program Files\Python313\python.exe' 'c:\Users\TIAGOSILVA\.vscode\extensions\ms-python.debugpy-2026.6.0-win32-x64\bundled\libs\debugpy\launcher' '59268' '--' 'C:\Users\TIAGOSILVA\Documents\aula_git28092026\app.py' 
=== Sistema De Notas do Aluno ===
digite a primeira nota:8
digite a segunda nota:9
A média final é: 8.50
Status: APROVADO!

***

### Tiago Silva
### https://www.linkedin.com/feed/

