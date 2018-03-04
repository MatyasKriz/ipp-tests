# Seznam testů

### General
1. Pouze komentáře
2. Prázdný program
3. Prázdný program - case insensitive
4. Špatná hlavička
5. Špatná hlavička #2
6. Garbage

### Variables
1. Práce s nedefinovanou proměnnnou
2. Práce s globální proměnnou
3. Práce s lokální proměnnou
4. Práce s lokální proměnnou bez LF
5. Definice proměnné na neexistujícím LF
6. Práce s proměnnou definovanou na TF

### Stack
1. PUSHFRAME bez CREATEFRAME
2. POP prázdného stacku
3. POP do nedefinované proměnné
4. PUSH z nedefinované proměnné
5. PUSH neinicializované proměnné
6. PUSH this, POP that
7. PUSH this, POP that #2
8. PUSH this, POP that #3
9. Jednoduchá práce s proměnnými na LF
10. POP do nedefinované proměnné (rámec neexistuje)

### Functions
1. Return bez CALL
2. Volání funkce bez parametrů a návratové hodnoty
3. Volání funkce s parametrem a návratovou hodnotou
4. Volání funkce s parametrem a návratovou hodnotu - bez LF
5. Volání funkce, neexistuje label

### Strings
1. Správný string
2. String - chybné escape sekvence
3. String - chybné escape sekvence #2
4. String - chybné escape sekvence #3
5. Správný string #2
6. Správný string #3

### Identifiers
1. Identifikátor začíná číslem
2. Identifikátor začíná speciálním znakem
3. Identifikátor začíná písmenem
4. Identifikátor obsahuje čísla
5. Identifikátor obsahuje nesprávné znaky
6. Identifikátor jako opcode
7. Case sensitive test
8. Definice proměnné s prázdným jménem
