        ############
        # Puzzle 5 #
        ############

        00      34          CALLVALUE
        01      80          DUP1
        02      02          MUL
        03      610100      PUSH2 0100
        06      14          EQ
        07      600C        PUSH1 0C
        09      57          JUMPI
        0A      FD          REVERT
        0B      FD          REVERT
        0C      5B          JUMPDEST
        0D      00          STOP
        0E      FD          REVERT
        0F      FD          REVERT

        ? Enter the value to send: <>