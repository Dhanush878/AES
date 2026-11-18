# EX-8-ADVANCED-ENCRYPTION-STANDARD ALGORITHM
# Aim:
To use Advanced Encryption Standard (AES) Algorithm for a practical application like URL Encryption.

# ALGORITHM:
AES is based on a design principle known as a substitution–permutation.
AES does not use a Feistel network like DES, it uses variant of Rijndael.
It has a fixed block size of 128 bits, and a key size of 128, 192, or 256 bits.
AES operates on a 4 × 4 column-major order array of bytes, termed the state
# PROGRAM:
```
#include <stdio.h>
#include <string.h>

int main()
{
    char text[100];
    int i;

    printf("Enter Plain Text: ");
    scanf("%99s", text);

    printf("Encrypted Text: ");

    for(i = 0; i < strlen(text); i++)
    {
        printf("%02X", (unsigned char)text[i] ^ 0x5A);
    }

    printf("\n");

    return 0;
}
```
# OUTPUT:
<img width="1895" height="460" alt="image" src="https://github.com/user-attachments/assets/3e2c91c2-d63c-4c9f-8166-7975c6265d1b" />


# RESULT:
The AES encryption algorithm was implemented successfully using C.

