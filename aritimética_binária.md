Na arquitetura de computadores, entender a aritmética binária é essencial porque os registradores trabalham diretamente com valores em binário. 

### 🔹 Soma binária

```asm  
    1 + 1 = 10 → porque 2 em binário é 10.

    100 + 10 = 110 → 4 + 2 = 6.

```

    
 ### 🔹 Subtração binária

 ```asm

    100 − 100 = 000 → 4 − 4 = 0.

    110 − 10 = 100 → 6 − 2 = 4.

```
    
### 🔹 Números negativos (complemento de dois)

Para representar −2 em 8 bits:

```asm  

    +2 = 0000 0010

    Inverter bits = 1111 1101

    Somar 1 = 1111 1110

``` 

#### 🔹Resultado: 1111 1110 = −2.

### 🔹 Multiplicação binária

Funciona como na decimal, mas em base 2:

```asm
110 (6)
×  10 (2)
---------
1100 (12)

```

#### 🔹O resultado correto é 1100.

### 🔹 Divisão binária

Segue a mesma lógica:

```asm

110 (6)
/  10 (2)
---------
11 (3)

```  

#### 🔹O resultado correto é 11.


A aritmética binária se baseia nesses princípios, e dominar isso é fundamental para manipulação de registradores e programação em assembly.
