### Atv03
Nesta atividade, utilizando a classe JOptionPanecriei, criei um programa que solicita a nota de duas provas e um trabalho e realiza a média destas atividades.

### Código:
```
import javax.swing.JOptionPane;

public class atv_03 {

    public static void main(String[] args) {

        double nota_p1, nota_p2, nota_trab, media;
        
        nota_p1 = Double.parseDouble(JOptionPane.showInputDialog("Informe a nota da 1ª prova:"));
        nota_p2 = Double.parseDouble(JOptionPane.showInputDialog("Informe a nota da 2ª prova:"));
        nota_trab = Double.parseDouble(JOptionPane.showInputDialog("Informe a nota do trabalho:"));

        media = (nota_p1 + nota_p2 + nota_trab) / 3;

        JOptionPane.showMessageDialog(null, "A média das atividades é: " + media);
   }
}

}
```

