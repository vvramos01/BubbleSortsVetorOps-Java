import java.util.Scanner;
public class VetorOps {

    int[] vetor = new int[10];
    Scanner scanner = new Scanner(System.in);

    public VetorOps() {
    }

    public void preencherVetor() {
        Scanner scanner = new Scanner(System.in);
        for (int i = 0; i < this.vetor.length; i++) {
            System.out.print("Vetor[" + i + "] = ");
            vetor[i] = scanner.nextInt();
        }
    }

    public void exibirVetor() {
        System.out.println("EXIBINDO Vetor");
        Scanner scanner = new Scanner(System.in);
        for (int i = 0; i < this.vetor.length; i++) {
            System.out.println("Vetor[" + i + "] = " + vetor[1]);
        }
        System.out.println("----------------------------");
    }

    public void ordenarVetorCrescente() {
        for (int i = 0; i < this.vetor.length; i++) {
            int aux;
            for (int j = 0; j < this.vetor.length - 1; j++) {
                if (this.vetor[j] > this.vetor[j + 1]) {
                    aux = vetor[j];
                    vetor[j] = vetor[j + 1];
                    vetor[j + 1] = aux;
                }
            }
        }
    }
}
