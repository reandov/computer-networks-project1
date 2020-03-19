# Computer Networks - Project 1

First **Computer Networks** project implementation.

The goal it's to make an client-server application that communicates through a switch.
Destiny <- Switch <- Origin

The project also specifies that we need to implement a fake "tcp" over a real UDP communication.

## How to Compile

### Script Compilation

```bash
chmod +x compiler.sh
./compiler.sh
```

### Manual Compilation

```bash
gcc comutador.c -o comutador
gcc destino.c -o destino
gcc origem.c -o origem
```

## How to Run

In three separate terminals, run:

```bash
./comutador
./destino
./origem
```
