import Calculadora;

public class CalculadoraSimples {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        
        System.out.print("Digite o primeiro número: ");
        double numero1 = scanner.nextDouble();
        
        System.out.print("Digite o segundo número: ");
        double numero2 = scanner.nextDouble();
        
        System.out.print("Digite a operação (+, -, *, /): ");
        char operacao = scanner.next().charAt(0);
        
        double resultado;
        
        switch (operacao) {
            case '+':
                resultado = numero1 + numero2;
                System.out.println("Resultado: " + resultado);
                break;
                
            case '-':
                resultado = numero1 - numero2;
                System.out.println("Resultado: " + resultado);
                break;
                
            case '*':
                resultado = numero1 * numero2;
                System.out.println("Resultado: " + resultado);
                break;
                
            case '/':
                if (numero2 == 0) {
                    System.out.println("Erro: Divisão por zero não é permitida.");
                } else {
                    resultado = numero1 / numero2;
                    System.out.println("Resultado: " + resultado);
                }
                break;
                
            default:
                System.out.println("Operação inválida.");
                break;
        }
        scanner.close();
    }
}
