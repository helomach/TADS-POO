### Atv01
Nesta atividade, criei uma classe que mostra a soma de todos os números informados pelo usuário, do tipo inteiro o real.

### Código:
```
import java.util.*;

public class atv_01 {
    public static void main(String[] args ){
        Scanner in = new Scanner(System.in);
        
        float num = -1, sum = 0;
        
        do {
            try {
            System.out.println("Informe um número para somar ou digite 0 para visualizar a soma dos números informados:");
            num = in.nextFloat(); // Usuário digita um número
            
            if (num >= 0) { // Caso o número digitado seja maior que zero, é executado a soma
                sum = num + sum; // Soma os valores digitados
            }   
            } catch (Exception e) {

            }
        } while (num != 0); 
        
        System.out.println("A soma dos valores é: " + sum); // sum
    }
}
```

### Saída:
```
Informe um número para somar ou digite 0 para visualizar a soma dos números informados:
10
Informe um número para somar ou digite 0 para visualizar a soma dos números informados:
5
Informe um número para somar ou digite 0 para visualizar a soma dos números informados:
0
A soma dos valores é: 15.0
```
