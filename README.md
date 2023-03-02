# Java-Basic
Repositório para armazenar o conteúdo do curso de formação em Java

public class MinhaClasse {

	public static void main (String [] args) {
		
		String primeiroNome = "Eduardo";
		String segundoNome = "Mattiolli";
		String nomeCompleto = nomeCompleto(primeiroNome, segundoNome);
		
		System.out.println(nomeCompleto);
		
	}
	public static String nomeCompleto (String primeiroNome, String segundoNome) {
		return primeiroNome.concat(" ").concat(segundoNome);
	
	}

}
