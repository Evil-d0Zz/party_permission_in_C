#Permission to join the party in C 🌐

![Alerta de texto](https://github.com/N3w-elf/party_permission_in_C/blob/master/video/aaa.mp4)

## Description

A simple program in C language, based on my studies in the language.

## Code

```bash
#include <stdio.h>
#include <stdlib.h>

int main(){
    printf("[*] - Digite sua idade: ");
        int a;
            scanf("%i", &a);
            if (a >= 18){
                    printf("\n[+] -Voce tem %i anos, pode entrar", a);
                            exit(0);
                                
            }
            else if(a <= 17){
                    printf("\n[x] - Voce tem %i anos, nao pode entrar.", a);
                            exit(0);
                                
            }
            else{
                    printf("Comando invalido!");
                            exit(0);
                                
            }
            
}

```
