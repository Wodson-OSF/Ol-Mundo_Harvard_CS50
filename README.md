# Ol-Mundo_Harvard_CS50
#include<stdio.h>  // Inclui a biblioteca padrão de entrada e saída (stdio.h)
#include<cs50.h>   // Inclui a biblioteca cs50 para funções adicionais

int main(void) {  // Função principal do programa

    // Declara uma variável 'name' do tipo 'string'
    string name = get_string("Qual o seu nome?");

    // Imprime a mensagem "Olá, " seguido do valor da variável 'name' e uma quebra de linha
    printf("Olá, %s\n", name);

    return 0;  // Indica que o programa foi executado com sucesso
}
