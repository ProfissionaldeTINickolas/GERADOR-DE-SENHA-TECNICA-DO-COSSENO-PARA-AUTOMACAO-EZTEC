#include <stdio.h>
#include <math.h>

#define PI 3.14159265

int main() {
    double num, cos_val;
    printf("Digite um número: ");
    scanf("%lf", &num);

    // Converte o ângulo para radianos, pois a função cos em C usa radianos
    num = num * (PI / 180.0);

    cos_val = cos(num);

    // Multiplica por 1000 e depois faz o módulo por 1000 para obter os 3 primeiros dígitos após a vírgula
    int first_three_digits = ((int)(cos_val * 1000)) % 1000;

    printf("Os três primeiros dígitos após a vírgula do cosseno do número digitado são: %03d\n", first_three_digits);

    return 0;
}
