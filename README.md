# Logisim
Hello guys, here I created Morris Mano CPU on Logisim Simulator(exclude I/O instructions)

including all other instructions...

Memory Refrence Instruction

Symbol   Hexadecimal Code	Description
	 	I=O  I=1  		
AND 		0xxx 8xxx 		AND memory word to AC
ADD 		lxxx 9xxx 		Add memory word to AC
LOA 		2xxx Axxx 		Load memory word to A C
STA 		3xxx Bxxx 		Store content of AC in memory
BUN 		4xxx Cxxx 		Branch unconditionally
BSA 		5xxx Dxxx 		Branch and save return address
ISZ 		6xxx Exxx 		Increment and skip if zero

Register Refrence instruction

Symbol   Hexadecimal Code	Description

CLA 		7800 			Clear AC
CLE 		7400 			Clear E
CMA 		7200 			Complement AC
CME 		7100 			Complement E
CIR 		7080 			Circulate right AC and E
CIL 		7040 			Circulate left AC and E
INC 		7020 			Increment AC
SPA 		7010 			Skip next instruction if AC positive
SNA 		7008 			Skip next instruction if AC negative
SZA 		7004 			Skip next instruction if AC zero
SZE 		7002 			Skip next instruction if E is 0
HLT 		7001 			Halt computer

