        ############
        # Puzzle 7 #
        ############

        00      36        CALLDATASIZE
        01      6000      PUSH1 00
        03      80        DUP1
        04      37        CALLDATACOPY
        05      36        CALLDATASIZE
        06      6000      PUSH1 00
        08      6000      PUSH1 00
        0A      F0        CREATE
        0B      3B        EXTCODESIZE
        0C      6001      PUSH1 01
        0E      14        EQ
        0F      6013      PUSH1 13
        11      57        JUMPI
        12      FD        REVERT
        13      5B        JUMPDEST
        14      00        STOP

        ? Enter the calldata: <>