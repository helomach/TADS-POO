### Atv06
Nesta atividade, criei uma classe para determinar quantos meses serão necessários para acumular o montante desejado.

### Código:
```
import java.util.*;

public class atv_06 {
    public static void main(String[] args) {
        
        Scanner in = new Scanner(System.in);

        double depositoFixoMensal, montante, jurosMensais;
        double saldo = 0.0;
        int meses = 0;

        System.out.println("Informe o valor do depósito fixo mensal: ");
        depositoFixoMensal = in.nextDouble();
        System.out.println("Informe o valor do montante desejado: ");
        montante = in.nextDouble();

        while (saldo < montante) {
            saldo = saldo + depositoFixoMensal;
            jurosMensais = saldo * 0.005;
            saldo = saldo + jurosMensais;
            meses = meses + 1;
        }

        System.out.println("Serão necessários " + meses + " meses para acumular o montante desejado!");
    }
}
```

### Saída:
```
Informe o valor do depósito fixo mensal: 
1000
Informe o valor do montante desejado: 
30000 
Serão necessários 28 meses para acumular o montante desejado!
```

