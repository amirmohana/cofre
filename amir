package aula20200323.cofre;

import static org.junit.jupiter.api.Assertions.*;

import org.junit.jupiter.api.Test;

class TestesComCofre {

	@Test
	void cofreRecemCriado(){

		Cofre cofreUm = new Cofre();
		Cofre cofreDois = new Cofre ();

		assertEquals(false,cofreUm.isAberto());
		assertEquals(false,cofreDois.isAberto());
		}
		void cofreAberto (){
		Cofre cofreUm = new Cofre();
		Cofre cofreDois = new Cofre();

		cofreUm.fechar();
		cofreUm.abrir();
		cofreDois.fechar();
		cofreDois.abrir();

		assertEquals(true, cofreUm.isAberto());
		assertEquals(true, cofreDois.isAberto());
		}
}
