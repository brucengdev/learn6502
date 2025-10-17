Instructions: 
- http://www.6502.org/tutorials/6502opcodes.html
- http://www.obelisk.me.uk/6502/reference.html


LDA #$02  
Loads the value #$02 to register A.

STA $0200  
Stores the value in register A to the byte at memory $0200

ADC $02  
ADC #$02  
ADC $02 adds the value stored at $02 to register A with carry.
ADC #$02 adds $02 to register A with carry.

SBC $02  
SBC #$02  
Subtracts from register C.  

TAX  
Copy values from A to X

INX
Increment X by 1

DEX  
Decrement X by 1

CPX #$02  
Compares value of register X to $02, set Z flag is equal, or unset if not equal.

BNE [location]  
Branch if not equal, if Z flag is not set

BEQ [location]  
Branch if equal, or Z flag is set.