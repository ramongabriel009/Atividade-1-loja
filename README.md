# Atividade-1-loja


import java.util.Scanner;
public class Main
{
    public static void main(String[] args) {
        Scanner loja = new Scanner(System.in);

        // nome do produto
        System.out.print("Digite um nome: ");
        String nome = loja.nextLine();
        System.out.println("seu nome é: " + nome);

        // nome do produto
        System.out.print("Digite o nome do produto");
        String produto = loja.next();
        System.out.println("o nome do produto é: " + produto);

        // código do produto
        System.out.print("codigo_produto: ");
        String codigo = loja.next();
        System.out.println("o codigo é: " + codigo);

        // preço do produto
        System.out.print("preço do produto: ");
        double preco = loja.nextDouble();
        System.out.println("o preço é: " + preco);
    }
}
