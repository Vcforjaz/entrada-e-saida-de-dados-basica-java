<h1><a href="https://vcforjaz.github.io/Meus-Projetos/"><img align="center" width="40px" src="https://vcforjaz.github.io/Meus-Projetos/favicon.ico"></a><a href="https://vcforjaz.github.io/Meus-Projetos/"><span>Acesse meu site de portfólios hospedado no Git Pages.</span></a></h1>

# Código abaixo:
`import java.util.Scanner;

public class ContaTerminal {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Solicitar e ler os dados do usuário
        System.out.println("Por favor, digite o número da Agência:");
        String agencia = scanner.nextLine();

        System.out.println("Por favor, digite o número da Conta:");
        int numero = scanner.nextInt();
        scanner.nextLine(); // Limpar o buffer do scanner

        System.out.println("Por favor, digite o nome do Cliente:");
        String nomeCliente = scanner.nextLine();

        System.out.println("Por favor, digite o saldo, lembre-se de utilizar ',' ");
        double saldo = scanner.nextDouble();

        // Construir a mensagem final
        String mensagem = "Olá " + nomeCliente + ", obrigado por criar uma conta em nosso banco, " +
                "sua agência é " + agencia + ", conta " + numero + " e seu saldo " + saldo +
                " já está disponível para saque.";

        // Exibir a mensagem final
        System.out.println(mensagem);
    }
}`

