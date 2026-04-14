# Titulo:  VPS01
## verificaçâo Prática Somativa 01
Arquivos gerados durante a avaliaçâo de Lógica de Programaçâo, algoritima e fluxograma

## Tecnologias 

|Tecnologia|Utilidade|
|:-:|-|
|Linguagem **C** |Desenvolvimento|
|IDE |Embarcadero **Dev C++**|
|Draw.io para |Desenhar de *fluxograma*| 
|Bloco de notas para |*portugal* logica|
## Como Testar 
. 1 clone este repositor 
. 2 Abra os arquivos .c como DevC++
. 3 Pressione F11 para compilar executar

## Exemplo de Código
```c
#include<stdio.h>
#include<windows.h>
void main(){
	SetConsoleOutputCP(CP_UTF8);
	char nome[20], sexo;
	int idade;
	printf("Digite seu nome, sexo m/f e idade\n");
	scanf(" %s %c %d", &nome, &sexo, &idade);
	if(sexo == 'm'){
		if(idade > 65){
			printf("O atendimento do paciente %s é prioritário", nome);
  		}else{
		  	printf("O atendimento do paciente %s é normal", nome);
  		}
   }else{
      if(idade > 60){
	  	printf("O atendimento do paciente %s é prioritário", nome);
      }else{
      	printf("O atendimento do paciente %s é normal", nome);
	  }
    }
    getch();
}
```

![Fluxograma](./atendimento.png)
