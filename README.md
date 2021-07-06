programa
{
	inteiro ld1
	inteiro ld2
	inteiro ld3
	
	funcao inicio()
	{
		leia(lado1, lado2, lado3)

		se(lado1 + lado2 > lado3 e lado1 + lado3 > lado2 e lado2 + lado3 > lado1){

						
			se(lado1 == lado2 e lado1 == lado3 e lado3 == lado2){
				escreva(" Um triângulo equilátero.")
			
			} senao se(lado1 != lado2 e lado1 != lado3 e lado2 != lado3){
				escreva(" Um triânguloescaleno.")
			} senao {
				escreva(" Um triângulo Isósceles.")
			}
			
		}senao {
			escreva(" Não pode ser um triangulo.")
		}

		
	}
}
