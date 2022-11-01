# algoritmos-trener
Algoritmos c//

#include <stdio.h>
#include <math.h>
double x1,x2,py1,py2,distc;

int main(){
    printf("\ndigite o valor de x1 :");
    scanf("%lf",&x1);
    printf("\ndigite o valor x2 :");
    scanf("%lf",&x2);
    printf("\ndigite o valor de py1 :");
    scanf("%lf",&py1);
    printf("\ndigite o valor de py2 :");
    scanf("%lf",&py2);
    
    distc=(x2-x1)*(x2-x1)+(py2-py1)*(py2-py1);
    distc=sqrt(distc);
    printf("\na distancia e :%.4lf",distc);
    
    
    return 0;
}


