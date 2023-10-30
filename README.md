int main()
{
    float  A,B,C;
    printf("la valeur de A : ");
    scanf ("%f",&A);
    printf ("la valeur de B : ");
    scanf ("%f",&B);
    C=A;
    A=B;
    B=C;
    printf ("la valeur de A : %.0f\n",A);
    printf ("la valeur de B : %.0f",B);
    return 0;
}
