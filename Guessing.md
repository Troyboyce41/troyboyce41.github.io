```mermaid
flowchart TD;
A(I am thinking of a number from 1 to100.) --> B{User inputs number};
B -->|Result one if the number is lower than randomly generated number| D[That is too low, try again.];
B -->|Result two if the number matches the randomly generated number| E[That is correct!];
B -->|Result three if the number is higher than randomly generated number| F[Too high! Try again!];
E -->C{Play Again?};
C --> G[yes];
C -->|closes application| H[No];
G --> |Goes back to user input| B;
```
