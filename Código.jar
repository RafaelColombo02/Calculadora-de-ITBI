import javax.swing.JOptionPane;

public class CalculadoraITBI {
    public static void main(String[] args) {
        // Entrada de dados usando JOptionPane
        String valorTransacaoInput = JOptionPane.showInputDialog(null, "Digite o valor da transação:");
        double valorTransacao = Double.parseDouble(valorTransacaoInput);

        String valorVenalInput = JOptionPane.showInputDialog(null, "Digite o valor venal:");
        double valorVenal = Double.parseDouble(valorVenalInput);

        String porcentagemITBIInput = JOptionPane.showInputDialog(null, "Digite a porcentagem do ITBI:");
        double porcentagemITBI = Double.parseDouble(porcentagemITBIInput);

        // Calcular o ITBI com base no maior valor entre a transação e o venal
        double valorITBI = Math.max(valorTransacao, valorVenal) * (porcentagemITBI / 100);

        // Exibir o valor do ITBI usando JOptionPane
        JOptionPane.showMessageDialog(null, "O valor do ITBI é: R$" + valorITBI);
    }
}
