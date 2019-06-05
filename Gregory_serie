//Calcular e mostrar o valor de PI utilizando a série de Gregory:

class Main {
	public static void main(String[] args) {
		float den = 3; // denominador
		float shift = 1;
		float serie = 1;
		float PI;

		for (int i = 0; i < 200; i++) {
			shift *= -1;
			serie = serie + shift / den;
			den = den + 2;
			// System.out.println(serie);
		}
		PI = 4 * serie;
		System.out.println("Valor de PI pela série de Gregory: " + PI);
	}
}
