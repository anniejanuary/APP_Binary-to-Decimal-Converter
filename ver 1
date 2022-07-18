binary_number=[0,0,0,0,0,0,0,0]

input_number=int(input("Enter a number: "))
if input_number>255:
    print("The number you entered exceeds an 8-bit number 255")  

binary_number[7]=input_number%2
integer_division=input_number//2

index=1 #index działań żeby wyliczyć liczbę binarną
        #dlatego index=1 a nie 0, bo pierwsze modulo bylo juz zrobione w linijce 7.

while integer_division>0:
    binary_number[7-index]=integer_division%2   #7 bo to ostatnia pozycja z tabelki konwersji do liczby binarnej, czyli zaczynam od 7-1=6 -> 6.ty indeks w liście liczba_binarna
    integer_division=integer_division//2
    index=index+1
    
print(f"The decimal number {input_number} converted to binary is: ",end=" ")

for x in binary_number:
    print(x,end=" ")
