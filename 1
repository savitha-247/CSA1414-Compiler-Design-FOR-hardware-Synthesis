#include <stdio.h>
#include <ctype.h>
#include <string.h>

int main() {
    char c, buffer[30];
    int i;

    printf("Enter code (end with $):\n");

    while ((c = getchar()) != '$') {  // End input with $
        // Skip whitespace
        if (c == ' ' || c == '\t' || c == '\n')
            continue;

        // Identifiers or numbers
        if (isalpha(c) || c == '_' || isdigit(c)) {
            i = 0;
            buffer[i++] = c;
            while ((c = getchar()) != '$' && (isalnum(c) || c == '_')) {
                buffer[i++] = c;
            }
            buffer[i] = '\0';

            if (isdigit(buffer[0]))
                printf("Constant: %s\n", buffer);
            else
                printf("Identifier: %s\n", buffer);

            if (c != '$') ungetc(c, stdin);
        }
        // Operators
        else {
            printf("Operator: %c\n", c);
        }
    }

    return 0;
}
