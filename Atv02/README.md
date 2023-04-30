### Atv02
Nesta atividade, criei um programa que solicita dois números inteiros deixando o cursor na mesma linha, e depois apresenta o produto dos dois números informados.

### Código:
```
import java.util.*;

public class atv_02 {
    public static void main(String[] args ){
        Scanner in = new Scanner(System.in);

        int a, b, c;

        System.out.print("Informe um inteiro: ");
        b = in.nextInt();

        System.out.print("Informe um inteiro: ");
        c = in.nextInt();

        a = b * c;

        System.out.print("O produto de " + b + " * " + c + " é: " + a);

        // Este é um programa que é exemplo de folha de pagamento 


    }
}
```

### Saída:
```
Informe um inteiro: 5
Informe um inteiro: 5
```
