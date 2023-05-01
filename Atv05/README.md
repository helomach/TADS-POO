### Atv05
Nesta atividade, utilizei o mesmo código da atividade 04 e acrescentei a média do gasto mensal da empresa.

### Código:
```
package atv_05;
public class BalancoTrimestral {
    public static void main(String[] args ){

        float gastosJaneiro = (float )3000.00;
        float gastosFevereiro = (float) 2500.67;
        float gastosMarco = (float) 4568.89;
        float gastosTrimestre = gastosJaneiro + gastosFevereiro + gastosMarco;

       float mediaMensal = gastosTrimestre / 3;

        System.out.println("R$" + gastosTrimestre);

        System.out.println("Valor da média mensal = " + mediaMensal);

    }
}
```

### Saída:
```
Valor da média mensal = 3356.5203
```

