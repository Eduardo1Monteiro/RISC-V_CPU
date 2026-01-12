🚀 RISC-V CPU Simulator

Um simulador de ciclo único (ou pipeline) da arquitetura RISC-V (RV32I), desenvolvido para fins educacionais e de estudo de sistemas computacionais. O projeto emula a execução de instruções, o banco de registradores e a hierarquia de memória.
🛠️ Funcionalidades Implementadas

    Conjunto de Instruções: Suporte completo ao set base RV32I.

    Decodificação: Decodificador de instruções eficiente para tipos R, I, S, B, U e J.

    Memória: Simulação de memória RAM linear com suporte a endereçamento de 32 bits.

    Dump de Estado: Exportação do estado dos registradores e memória após a execução (útil para debug).

    Interface CLI: Carregamento de arquivos binários diretamente via linha de comando.

🏗️ Arquitetura do Simulador

O simulador segue o fluxo clássico de execução de uma CPU:

    Fetch (Busca): Busca a instrução na memória baseada no PC (Program Counter).

    Decode (Decodificação): Extrai opcodes, registradores e imediatos.

    Execute (Execução): Realiza operações lógicas e aritméticas via ALU.

    Memory (Memória): Acessa a memória de dados (Load/Store).

    Write Back (Escrita): Atualiza o banco de registradores.
