Na arquitetura de computadores, entender a aritmética binária é essencial porque os registradores trabalham diretamente com valores em binário. 

<details>
  <summary>🔹 Soma binária</summary>

```asm
1 + 1 = 10  
→ porque 2 em binário é representado como 10.

100 + 10 = 110  
→ 4 + 2 = 6 em decimal, que em binário é 110.
```
</details>

<details>
  <summary>🔹 Subtração binária</summary>

```asm
100 − 100 = 000  
→ 4 − 4 = 0 em decimal.

110 − 10 = 100  
→ 6 − 2 = 4 em decimal.
```
</details>

### 🔹 Números negativos (complemento de dois)

<details>
  <summary>🔹 Representação de −2 em 8 bits</summary>

```asm
+2 = 0000 0010  

Inverter bits = 1111 1101  

Somar 1 = 1111 1110 → igual a −2

```
</details>

### 🔹 Multiplicação binária

<details>
  <summary>🔹 Multiplicação binária</summary>

```asm
110 (6)  
×  10 (2)  
---------  
1100 (12)
```
</details>

### 🔹 Divisão binária

<details>
  <summary>🔹 Divisão binária</summary>

```asm
110 (6)  
÷ 10 (2)  
---------  
11 (3)
```  

</details>

A aritmética binária se baseia nesses princípios, e dominar isso é fundamental para manipulação de registradores e programação em assembly.
