# sdes-go
Simplified DES implementation in GO language

## Usage: 
### Ecrypt:
go run sdes.go '8 bit plain text' '10 bit key'

Example: go run sdes.go 11100101 1011001010
       
### Decrypt (add 'd' flag):
go run sdes.go '8 bit encrypted text' '10 bit key' 

Example: go run sdes.go 11011111 1011110111 d

## TO-DO
- Implement CBC system
- Translate variable names
- Add code comments
- Search about the possibility of padding the plain text entry
         
