# javaNoEclipse
Programas  básicos realizados em java como forma de aperfeiçoamento do Scanner  e da linguagem Java
/calcular a area de um terreno 
//Author :phjLopes

import java.util.Locale;
import java.util.Scanner;

public class area {

	public static void main(String[] args) {
		Locale.setDefault(Locale.US);
		
		Scanner sc = new Scanner(System.in);
		
		double largura = sc.nextDouble();
		
		double comprimento = sc.nextDouble();
		
		double valorMetro = sc.nextDouble();
		
		double area = largura * comprimento;
		double preco = area * valorMetro;

		System.out.printf("Area= %.2f%n", area);
		System.out.printf("Preco=%.2f%n", preco);

		sc.close();

	}
}

//calcular a area de um circulo
//Author :phjLopes
import java.util.Locale;
import java.util.Scanner;

public class areadocirculo {

	public static void main(String[] args) {

		Scanner sc = new Scanner(System.in);
		Locale.setDefault(Locale.US);
		double pi = 3.14159;
		double r = sc.nextDouble();
		double area = pi * (r * r);

		System.out.printf("A= %.4f%n ", area);

		sc.close();
	}

}/calculadora de 2 digitos
//Author :phjLopes
import java.util.Scanner;

public class calculadora {

	public static void main(String[] args) {
		Scanner sc = new Scanner(System.in);

		int x = sc.nextInt();
		int y = sc.nextInt();
		int soma = x + y;

		System.out.printf("Resultado:" + soma);
		sc.close();
	}

}
import java.util.Locale;
import java.util.Scanner;

public class calculoDoSalario {

	public static void main(String[] args) {
         Locale.setDefault(Locale.US);
		Scanner sc = new Scanner(System.in);

		double horas, valor;
       int number = sc.nextInt();
		horas = sc.nextDouble();
		valor = sc.nextDouble();
		double salario = horas * valor;
		
		System.out.println("Number: " + number);
		System.out.println("Salario: " +salario);

		sc.close();
	}

}
//calcular diversas areas

import java.util.Locale;
import java.util.Scanner;

public class calculosDiversos {
	
	public static void main(String []args) {
	
	Locale.setDefault(Locale.US);
	Scanner sc = new Scanner(System.in);
	double A,B,C,pi= 3.14159;
	A= sc.nextDouble();
	B=sc.nextDouble();
	C=sc.nextDouble();	
	
	double areaDoTriangulo= A*C/2;
	double areaDoCirculo = pi*(C*C);
	double areaDoTrapezio = (A+B)*C/2;
	double areaDoQuadrado = B*B;
	double areaDoRetangulo = A*B;
	
	
	System.out.printf("Area do triangulo=%.3f%n ", areaDoTriangulo);	
	System.out.printf("Area do triangulo=%.3f%n ", areaDoCirculo);	
	System.out.printf("Area do triangulo=%.3f%n ",areaDoTrapezio);	
	System.out.printf("Area do triangulo=%.3f%n", areaDoQuadrado);	
	System.out.printf("Area do triangulo=%.3f%n", areaDoRetangulo);	
	sc.close();
	}
}
// ler a diferença entre os numeros  
// Author :phjLopes
import java.util.Scanner;

public class diferenca {
	
	
	
	public static void main(String[]args) {
		Scanner sc = new Scanner(System.in);
		
		int a, b ,c ,d ;
		
		a= sc.nextInt();
		b= sc.nextInt();
		c = sc.nextInt();
		d = sc.nextInt();
		int diferenca = ((a*b)-(c*d));
		System.out.println("Diferença e de "+ diferenca);		
		
		
		sc.close();
	}

}
