# linux-ebac
projeto linux da EBAC
[calculadora.sh](https://github.com/user-attachments/files/26713588/calculadora.sh)

// parte de comandos
[comandos.txt](https://github.com/user-attachments/files/26713560/comandos.txt)
chmod 744 calculadora.sh[
./calculadora.sh
ls -l calculadora.sh

// calculadora em si
#!/bin/bash
echo "==== Calculadora Python ===="
echo "Executando o programa Calculadora.py..."
python3 calculadora.py
echo "Fim da execução!"

# Calculadora Shell Script - EBAC

## Como Executar o .sh
1. Abra terminal Linux.
2. Dê permissão: `chmod 744 calculadora.sh`
3. Execute: `./calculadora.sh`
4. Digite 2 números → Veja soma, subtração, multiplicação e divisão!

## Código Python Explicado (calculadora.py)
```python
# primeiramnete ele solicita dois números do usuário
num1 = float(input("Digite o primeiro número: "))
num2 = float(input("Digite o segundo número: "))

# e aqui alcula as 4 operações básicas
soma = num1 + num2
subtracao = num1 - num2
multiplicacao = num1 * num2
divisao = num1 / num2 if num2 != 0 else "Erro: Divisão por zero!"

# por fim ele exibe resultados
print(f"Soma: {soma}")
print(f"Subtração: {subtracao}")
print(f"Multiplicação: {multiplicacao}")
print(f"Divisão: {divisao}")

explicação do código
Entrada 2 floats via input()

Lógica operações  aritméticas com verificação de divisão por zero

Saída resultados formatados no terminal 



