# meuBOOT
umAMIGO

import java.util.Scanner;

public class boot {

	public static void main(String[] args) {

		Scanner can = new Scanner(System.in);

		System.out.println(
				"Quem vai te responder é o próprio computador então não se preocupe pois nenhuma de suas mensagens-");
		System.out.println("será lida por ninguém :D");
		System.out.println("Nenhuma mensagem será salva ou arquivada.");
		System.out.println("Divirta-se :D");

		System.out.println("");

		System.out.println("Qual seu nome ?");
		String nome = can.nextLine();

		System.out.println("");

		System.out.println("Como devo te chamar ?");
		String nick = can.nextLine();

		System.out.println("");

		System.out.println("É um prazer " + nick);
		System.out.println("Meu nome é キ Mr.Costela キ, :) mas pode me chamar só de costela.");

		System.out.println("");

		System.out.println("Tem quantos anos ?");
		int idade = can.nextInt();

		if (idade <= 12) {
			System.out.println("Legal haha na sua idade eu gostava bastande de ver desenho.");
			System.out.println("Qual seu desenho favorito ? ");
			String desenho = can.next();
			System.out.println("Bom acho que esse não é da minha época haha");

		} else if (idade >= 12 && idade <= 18) {
			System.out.println("Na sua idade eu gostava de jogar video game haha");
			System.out.println("Você gosta de jogar ? s/n");
			String sn = can.next();

			if (sn.equalsIgnoreCase("s")) {
				System.out.println("Oque você joga ?");
				String resposta1 = can.next();
				System.out.println("Interessante, me conta sobre ele_");
				String resposta2 = can.next();
				System.out.println("Parece ser bom eu irei dar uma olhada :D");

			} else if (sn.equalsIgnoreCase("n")) {
				System.out.println("Por quê ?");
				String resosta3 = can.next();
				System.out.println("Ata entendi.");

			} else if (sn.equalsIgnoreCase("sim")) {
				System.out.println("Oque você joga ?");
				String resposta1 = can.next();
				System.out.println("Interessante, me conta sobre ele_");
				String resposta2 = can.next();
				System.out.println("Parece ser bom eu irei dar uma olhada :D");

			} else if (sn.equalsIgnoreCase("não")) {
				System.out.println("Por quê ?");
				String resosta3 = can.next();
				System.out.println("Ata entendi.");

			} else if (sn.equalsIgnoreCase("nao")) {
				System.out.println("Por quê ?");
				String resosta3 = can.next();
				System.out.println("Ata entendi.");

			} else {
				System.out.println("Perdão não entendi, tente digitar: s, n, sim, não.");
				System.out.println("Você gosta de jogar ?");
				String resposta4 = can.next();
				System.out.println("");
				System.out.println("Tendi ;D");
			}
		} else if (idade >= 19) {
			System.out.println("Você trabalha ou faz faculdade ?");
			String VsVn = can.next();
			System.out.println("Se sente confortável para falar disso ? s/n");
			String sn = can.next();

			if (sn.equalsIgnoreCase("s")) {
				System.out.println("Me fale um pouco sobre_");
				String desabafo = can.next();
				System.out.println("Entendo...você tem um futúro brilhante eu aposto :D");

			} else if (sn.equalsIgnoreCase("sim")) {
				System.out.println("Me fale um pouco sobre_");
				String desabafo = can.next();
				System.out.println("Entendo...você tem um futúro brilhante eu aposto :D");

			} else if (sn.equalsIgnoreCase("n")) {
				System.out.println("Tudo bem :D");

			} else if (sn.equalsIgnoreCase("não")) {
				System.out.println("Tudo bem :D");

			} else if (sn.equalsIgnoreCase("nao")) {
				System.out.println("Tudo bem :D");

			}
		}

		System.out.println("");
		
		System.out.println("Qual sua cor favorita ?");
		String cor = can.toString();
		
		System.out.println("");
		
		System.out.println("Legal haha");
		
		System.out.println("");
		
		System.out.println("A minha é o amarelo como o Sol  🌞"); 
		System.out.println("Se bem que o Sol não é amarelo 🤔 mas ok :D");
		
		
		
	}

}

