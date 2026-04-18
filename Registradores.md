# 📌 Registradores e início ao Assembly

Ao estudar arquitetura de computadores, é essencial compreender os registradores. Eles são pequenas áreas de memória dentro do processador, extremamente rápidas, usadas para armazenar dados temporários durante a execução de instruções.

Em um processador de 32 bits, cada registrador possui 32 bits de largura. Isso permite acessar partes específicas:

``` 

  . AX → 16 bits menos significativos de EAX.

  . AH → 8 bits mais altos dentro de AX.

  . AL → 8 bits mais baixos dentro de AX.

```

--- 
  
## 🔹 Tipos de registradores

Propósito geral (movimentação de dados):

```  

    EAX → operações aritméticas.

    EBX → base para endereçamento.

    ECX → contador (loops, shifts).

    EDX → operações de multiplicação/divisão.

```  
    
Ponteiros (controle de fluxo e pilha):

```  

    EIP → aponta para a próxima instrução.

    ESP → topo da pilha.

    EBP → referência para variáveis locais.

```  
    
Índice (operações com arrays e strings):

```  

    ESI → origem.

    EDI → destino.

``` 

  ---
    
## 🔹 Flags (registradores de controle)

As flags indicam o resultado de operações aritméticas e lógicas:

``` 

    Overflow Flag (OF) → indica quando o resultado excede o limite de representação.

    Sign Flag (SF) → mostra se o resultado é negativo (bit mais significativo = 1).

    Zero Flag (ZF) → ativa quando o resultado é zero.

    Auxiliary Flag (AF) → usada em operações de ajuste entre nibbles (4 bits).

    Parity Flag (PF) → ativa se o número de bits 1 no resultado for par.

``` 

 ---
    
## 🔹 Instruções básicas em Assembly

``` 

    Movimentação

        MOV EAX, EBX → copia o valor de EBX para EAX.

        PUSH EAX → coloca o valor de EAX na pilha.

        POP EBX → retira o valor do topo da pilha e coloca em EBX.

``` 

  ---
        
## Aritmética

``` 

    ADD EAX, 5 → soma 5 a EAX.

    SUB EDX, 5 → subtrai 5 de EDX.

    IMUL EAX, EDX → multiplica EAX por EDX.

    IDIV EAX, EDX → divide EAX por EDX.

``` 

   ---
    
## Controle de fluxo

```  

    JMP endereço → salto incondicional.

    JE endereço → salto se resultado for igual.

    JNE endereço → salto se resultado for diferente.

    CMP EAX, EBX → compara EAX com EBX.

```  

   ---
    
Dominar os registradores, as flags e as instruções básicas é o primeiro passo para compreender a lógica do assembly. Esse conhecimento é fundamental para manipular dados diretamente no processador e entender como programas funcionam em baixo nível.
