### Atv01
Nesta atividade, criei uma classe que mostra a soma de todos os números informados pelo usuário, do tipo inteiro o real.

### Código:
```
import java.util.*;

public class atv_01 {
    public static void main(String[] args ){
        Scanner in = new Scanner(System.in);
        
        float num, sum = 0;
        
        do {
            System.out.println("Digite um número:");
            num = in.nextFloat(); // Usuário digita um número
            
            if (num >= 0) { // Caso o número digitado seja maior que zero, é executado a soma
                sum = num + sum; // Soma os valores digitados
            }
        } while (num > 0); // Caso o número digitado seja menor que zero, o while para
        
        System.out.println("A soma dos valores é " + sum); // sum
    }
}
```

### Saída:
```
Digite um número:
10
Digite um número:
2
Digite um número:
56
Digite um número:
9
Digite um número:
0
A soma dos valores é 77.0
```
