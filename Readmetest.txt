SMBIOS Header
---------------------------------------
Name				Type		Data
====				====		====
SMBIOS Signature        	4 BYTEs 	_SM_
SMBIOS Checksum         	BYTE    	EEh
SMBIOS Table Length     	BYTE    	31 bytes
SMBIOS Version          	WORD    	2.8
SMBIOS Max. Struc. Size 	WORD    	394
SMBIOS Point Revision   	BYTE    	00h
SMBIOS Formatted Area   	5 BYTEs 	00 00 00 00 00h
DMI Signature           	5 BYTEs 	_DMI_
DMI Checksum            	BYTE    	50h
DMI Table Length        	WORD    	4605 bytes
DMI Table Address       	DWORD   	CEB90000h
SMBIOS # Sturc          	WORD    	91
DMI Revision            	BYTE    	2.8
==============================================================================


[Type 000] -- BIOS Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	26 bytes
Struc. Handle           	WORD    	0000h
BIOS Vendor             	STRING  	American Megatrends Inc.
BIOS Version            	STRING  	F5
BIOS Starting Add. Seg. 	WORD    	F000h
BIOS Release Date       	STRING  	08/13/2019
BIOS ROM Size           	BYTE    	16384 KB
BIOS Characteristics    	QWORD   	0000 0001 378B 9880h
						Bit.07:PCI is Reserved
						Bit.11:BIOS is Upgradeable(Flash)
						Bit.12:BIOS shadowing is allowed
						Bit.15:Boot from CD is supported
						Bit.16:Selectable Boot is supported
						Bit.17:BIOS ROM is socketed
						Bit.19:EDD(Enhanced Disk Drive) Specification is supported
						Bit.23:Int 13h - 5.25" / 1.2MB Floppy Services are supported
						Bit.24:Int 13h - 3.5" / 720 KB Floppy Services are supported
						Bit.25:Int 13h - 3.5" / 2.88 MB Floppy Services are supported
						Bit.26:Int 5h, Print Screen Service is supported
						Bit.28:Int 14h,Serial Services are supported
						Bit.29:Int 17h, Printer Services are supported
						Bit.32~47:Reserved for BIOS Vendor
BIOS Char. Extension    	WORD    	0D03h
						Bit.00:ACPI is supported
						Bit.01:USB Legacy is supported
						Bit.08:BIOS Boot Specification is supported
						Bit.10:Enable Targeted Content Distribution
						Bit.11:UEFI Specification is supported
						Bit.13~15:Reserved
System BIOS Major       	BYTE    	05h
System BIOS Minor       	BYTE    	0Ch
Embedded Controller Firmware Major Release	BYTE    	FFh
Embedded Controller Firmware Minor Release	BYTE    	FFh
Extended BIOS ROM Size  	WORD    	16 MB
						
==============================================================================


[Type 001] -- System Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	27 bytes
Struc. Handle           	WORD    	0001h
Manufacturer            	STRING  	Gigabyte Technology Co., Ltd.
Product Name            	STRING  	B365M DS3H
Version                 	STRING  	Default string
Serial Number           	STRING  	adsfsafdsfbvcbcvbvbxbngtrgw
UUID                    	16 BYTEs	18 CB C0 8E 4D 98 5B 11 0E E5 F1 C9 34 2C 36 53h
Wake-up Type            	BYTE    	06h
						Power Switch
SKUNumber               	STRING  	Default string
Family                  	STRING  	Default string
==============================================================================


[Type 002] -- Base Board/Module Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	15 bytes
Struc. Handle           	WORD    	0002h
Manufacturer            	STRING  	Gigabyte Technology Co., Ltd.
Product                 	STRING  	B365M DS3H
Version                 	STRING  	x.x
Serial Number           	STRING  	Gfdgfdsgfdgngfbvbcbx
Asset Tag               	STRING  	Default string
Feature Flags           	BYTE    	09h
						Bit.00:the board is a hosting board.
						Bit.03:the board is replaceable.
Location in Chassis     	STRING  	Default string
Chassis Handle          	WORD    	0003h
Board Type              	BYTE    	0Ah
						Motherboard(includes processor, memory, and I/O)
Number of Contained Object Handles	BYTE    	00h
==============================================================================


[Type 003] -- System Enclosure or Chassis
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	22 bytes
Struc. Handle           	WORD    	0003h
Manufacturer            	STRING  	Default string
Type                    	BYTE    	03h
						Desktop
Version                 	STRING  	Default string
Serial Number           	STRING  	ghfdjkshgjkbvcbwqrqrqr
Asset Tag               	STRING  	Default string
Bootup State            	BYTE    	03h
						Safe
Power Supply State      	BYTE    	03h
						Safe
Thermal State           	BYTE    	03h
						Safe
Security Status         	BYTE    	03h
						None
OEM-defined             	DWORD   	0000 0000h
Height                  	BYTE    	00h
Number of Power Cords   	BYTE    	01h
Contained Element Count 	BYTE    	00h
Contained Element Record Length	BYTE    	03h
Contained Elements      	BYTEs   	None
SKU Number              	STRING  	Default string
==============================================================================


[Type 004] -- Processor Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	48 bytes
Struc. Handle           	WORD    	003Eh
Socket Designation      	STRING  	U3E1
Processor Type          	BYTE    	03h
						Central Processor
Processor Family        	BYTE    	CDh
						Intel(R) Core(TM) i5 processor
Processor Manufacturer  	STRING  	Intel(R) Corporation
Processor ID            	DWORD   	0009 06EAh
Processor Features      	DWORD   	BFEB FBFFh
Processor Version       	STRING  	Intel(R) Core(TM) i5-9400F CPU @ 2.90GHz
Voltage                 	BYTE    	8Bh
						Bit.07:Set to 1, the remaining seven bits of the field are set  
		      to contain the processor's current voltage times 10.
						Current voltage = 1.1V
External Clock          	WORD    	100 MHz
Max Speed               	WORD    	8300 MHz
Current Speed           	WORD    	3900 MHz
Status                  	BYTE    	41h
						Bit.06:CPU Socket Populated
						CPU Enabled
Processor Upgrade       	BYTE    	32h
						Socket LGA1151
L1 Cache Handle         	WORD    	003Bh
L2 Cache Handle         	WORD    	003Ch
L3 Cache Handle         	WORD    	003Dh
Serial Number           	STRING  	dahsjkghjkvcvfqrqer
Asset Tag               	STRING  	To Be Filled By O.E.M.
Part Number             	STRING  	To Be Filled By O.E.M.
Core Count              	BYTE    	06h
Core Enabled            	BYTE    	06h
Thread Count            	BYTE    	06h
Processor Characteristics	WORD    	00ECh
						Bit.02:64-Bit.Capable
						Bit.03:Multi-Core
						Bit.05:Execute Protection
						Bit.06:Enhanced Virtualization
						Bit.07:Power/Performance Control
						Bit.08~15:Reserved
Processor Family 2      	WORD    	00CDh
						Intel(R) Core(TM) i5 processor
Unknown                 	BYTEs   	06 06 06 EC 00 CD 00 06 00 06 00 06 00h
==============================================================================


[Type 007] -- Cache Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	27 bytes
Struc. Handle           	WORD    	003Bh
Socket Designation      	STRING  	L1 Cache
Cache Configuration     	WORD    	0180h
						Cache Level - 1
						Cache Socketed:Not Socketed
						Location, relative to the CPU module:Internal
						At boot time:Enable
						Operational Mode:Write Back
Maximum Cache Size      	WORD    	0180h
						1K granularity [Max Size:384]
Installed Size          	WORD    	0180h
						1K granularity [Max Size:384]
Supported SRAM Type     	WORD    	0020h
						Bit.05:Synchronous
Current SRAM Type       	WORD    	0020h
						Bit.05:Synchronous
Cache Speed             	BYTE    	00h
						Unknown
Error Correction Type   	BYTE    	04h
						Parity
System Cache Type       	BYTE    	05h
						Unified
Associativity           	BYTE    	07h
						8-way Set-Asociative
Maximum Cache Size 2    	DWORD   	0000 0000h
						1K granularity [Max Size:0]
Installed Size 2        	DWORD   	0000 0000h
						1K granularity [Max Size:0]
==============================================================================


[Type 007] -- Cache Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	27 bytes
Struc. Handle           	WORD    	003Ch
Socket Designation      	STRING  	L2 Cache
Cache Configuration     	WORD    	0181h
						Cache Level - 2
						Cache Socketed:Not Socketed
						Location, relative to the CPU module:Internal
						At boot time:Enable
						Operational Mode:Write Back
Maximum Cache Size      	WORD    	0600h
						1K granularity [Max Size:1536]
Installed Size          	WORD    	0600h
						1K granularity [Max Size:1536]
Supported SRAM Type     	WORD    	0020h
						Bit.05:Synchronous
Current SRAM Type       	WORD    	0020h
						Bit.05:Synchronous
Cache Speed             	BYTE    	00h
						Unknown
Error Correction Type   	BYTE    	05h
						Single-Bit.ECC
System Cache Type       	BYTE    	05h
						Unified
Associativity           	BYTE    	05h
						4-way Set-Asociative
Maximum Cache Size 2    	DWORD   	0000 0000h
						1K granularity [Max Size:0]
Installed Size 2        	DWORD   	0000 0000h
						1K granularity [Max Size:0]
==============================================================================


[Type 007] -- Cache Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	27 bytes
Struc. Handle           	WORD    	003Dh
Socket Designation      	STRING  	L3 Cache
Cache Configuration     	WORD    	0182h
						Cache Level - 3
						Cache Socketed:Not Socketed
						Location, relative to the CPU module:Internal
						At boot time:Enable
						Operational Mode:Write Back
Maximum Cache Size      	WORD    	2400h
						1K granularity [Max Size:9216]
Installed Size          	WORD    	2400h
						1K granularity [Max Size:9216]
Supported SRAM Type     	WORD    	0020h
						Bit.05:Synchronous
Current SRAM Type       	WORD    	0020h
						Bit.05:Synchronous
Cache Speed             	BYTE    	00h
						Unknown
Error Correction Type   	BYTE    	06h
						Multi-Bit.ECC
System Cache Type       	BYTE    	05h
						Unified
Associativity           	BYTE    	09h
						12-way Set-Associative
Maximum Cache Size 2    	DWORD   	0000 0000h
						1K granularity [Max Size:0]
Installed Size 2        	DWORD   	0000 0000h
						1K granularity [Max Size:0]
==============================================================================


[Type 008] -- Port Connector Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	9 bytes
Struc. Handle           	WORD    	0004h
Inter. Ref. Designator  	STRING  	J1A1
Internal Connector Type 	BYTE    	00h
						None
Ext. Ref. Designator    	STRING  	PS2Mouse
Ext. Conn. Type         	BYTE    	0Fh
						PS/2
Port Type               	BYTE    	0Eh
						Mouse Port
==============================================================================


[Type 008] -- Port Connector Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	9 bytes
Struc. Handle           	WORD    	0005h
Inter. Ref. Designator  	STRING  	J1A1
Internal Connector Type 	BYTE    	00h
						None
Ext. Ref. Designator    	STRING  	Keyboard
Ext. Conn. Type         	BYTE    	0Fh
						PS/2
Port Type               	BYTE    	0Dh
						Keyboard Port
==============================================================================


[Type 008] -- Port Connector Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	9 bytes
Struc. Handle           	WORD    	0006h
Inter. Ref. Designator  	STRING  	J2A1
Internal Connector Type 	BYTE    	00h
						None
Ext. Ref. Designator    	STRING  	TV Out
Ext. Conn. Type         	BYTE    	1Dh
						Mini-Centronics Type-14
Port Type               	BYTE    	FFh
						Other
==============================================================================


[Type 008] -- Port Connector Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	9 bytes
Struc. Handle           	WORD    	0007h
Inter. Ref. Designator  	STRING  	J2A2A
Internal Connector Type 	BYTE    	00h
						None
Ext. Ref. Designator    	STRING  	COM A
Ext. Conn. Type         	BYTE    	08h
						DB-9 pin male
Port Type               	BYTE    	09h
						Serial Port 16550A Compatible
==============================================================================


[Type 008] -- Port Connector Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	9 bytes
Struc. Handle           	WORD    	0008h
Inter. Ref. Designator  	STRING  	J2A2B
Internal Connector Type 	BYTE    	00h
						None
Ext. Ref. Designator    	STRING  	Video
Ext. Conn. Type         	BYTE    	07h
						DB-15 pin female
Port Type               	BYTE    	1Ch
						Video Port
==============================================================================


[Type 008] -- Port Connector Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	9 bytes
Struc. Handle           	WORD    	0009h
Inter. Ref. Designator  	STRING  	J3A1
Internal Connector Type 	BYTE    	00h
						None
Ext. Ref. Designator    	STRING  	USB1
Ext. Conn. Type         	BYTE    	12h
						Access Bus(USB)
Port Type               	BYTE    	10h
						USB
==============================================================================


[Type 008] -- Port Connector Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	9 bytes
Struc. Handle           	WORD    	000Ah
Inter. Ref. Designator  	STRING  	J3A1
Internal Connector Type 	BYTE    	00h
						None
Ext. Ref. Designator    	STRING  	USB2
Ext. Conn. Type         	BYTE    	12h
						Access Bus(USB)
Port Type               	BYTE    	10h
						USB
==============================================================================


[Type 008] -- Port Connector Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	9 bytes
Struc. Handle           	WORD    	000Bh
Inter. Ref. Designator  	STRING  	J3A1
Internal Connector Type 	BYTE    	00h
						None
Ext. Ref. Designator    	STRING  	USB3
Ext. Conn. Type         	BYTE    	12h
						Access Bus(USB)
Port Type               	BYTE    	10h
						USB
==============================================================================


[Type 008] -- Port Connector Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	9 bytes
Struc. Handle           	WORD    	000Ch
Inter. Ref. Designator  	STRING  	J9A1 - TPM HDR
Internal Connector Type 	BYTE    	FFh
						Other
Ext. Ref. Designator    	STRING  	
Ext. Conn. Type         	BYTE    	00h
						None
Port Type               	BYTE    	FFh
						Other
==============================================================================


[Type 008] -- Port Connector Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	9 bytes
Struc. Handle           	WORD    	000Dh
Inter. Ref. Designator  	STRING  	J9C1 - PCIE DOCKING CONN
Internal Connector Type 	BYTE    	FFh
						Other
Ext. Ref. Designator    	STRING  	
Ext. Conn. Type         	BYTE    	00h
						None
Port Type               	BYTE    	FFh
						Other
==============================================================================


[Type 008] -- Port Connector Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	9 bytes
Struc. Handle           	WORD    	000Eh
Inter. Ref. Designator  	STRING  	J2B3 - CPU FAN
Internal Connector Type 	BYTE    	FFh
						Other
Ext. Ref. Designator    	STRING  	
Ext. Conn. Type         	BYTE    	00h
						None
Port Type               	BYTE    	FFh
						Other
==============================================================================


[Type 008] -- Port Connector Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	9 bytes
Struc. Handle           	WORD    	000Fh
Inter. Ref. Designator  	STRING  	J6C2 - EXT HDMI
Internal Connector Type 	BYTE    	FFh
						Other
Ext. Ref. Designator    	STRING  	
Ext. Conn. Type         	BYTE    	00h
						None
Port Type               	BYTE    	FFh
						Other
==============================================================================


[Type 008] -- Port Connector Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	9 bytes
Struc. Handle           	WORD    	0010h
Inter. Ref. Designator  	STRING  	J3C1 - GMCH FAN
Internal Connector Type 	BYTE    	FFh
						Other
Ext. Ref. Designator    	STRING  	
Ext. Conn. Type         	BYTE    	00h
						None
Port Type               	BYTE    	FFh
						Other
==============================================================================


[Type 008] -- Port Connector Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	9 bytes
Struc. Handle           	WORD    	0011h
Inter. Ref. Designator  	STRING  	J1D1 - ITP
Internal Connector Type 	BYTE    	FFh
						Other
Ext. Ref. Designator    	STRING  	
Ext. Conn. Type         	BYTE    	00h
						None
Port Type               	BYTE    	FFh
						Other
==============================================================================


[Type 008] -- Port Connector Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	9 bytes
Struc. Handle           	WORD    	0012h
Inter. Ref. Designator  	STRING  	J9E2 - MDC INTPSR
Internal Connector Type 	BYTE    	FFh
						Other
Ext. Ref. Designator    	STRING  	
Ext. Conn. Type         	BYTE    	00h
						None
Port Type               	BYTE    	FFh
						Other
==============================================================================


[Type 008] -- Port Connector Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	9 bytes
Struc. Handle           	WORD    	0013h
Inter. Ref. Designator  	STRING  	J9E4 - MDC INTPSR
Internal Connector Type 	BYTE    	FFh
						Other
Ext. Ref. Designator    	STRING  	
Ext. Conn. Type         	BYTE    	00h
						None
Port Type               	BYTE    	FFh
						Other
==============================================================================


[Type 008] -- Port Connector Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	9 bytes
Struc. Handle           	WORD    	0014h
Inter. Ref. Designator  	STRING  	J9E3 - LPC HOT DOCKING
Internal Connector Type 	BYTE    	FFh
						Other
Ext. Ref. Designator    	STRING  	
Ext. Conn. Type         	BYTE    	00h
						None
Port Type               	BYTE    	FFh
						Other
==============================================================================


[Type 008] -- Port Connector Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	9 bytes
Struc. Handle           	WORD    	0015h
Inter. Ref. Designator  	STRING  	J9E1 - SCAN MATRIX
Internal Connector Type 	BYTE    	FFh
						Other
Ext. Ref. Designator    	STRING  	
Ext. Conn. Type         	BYTE    	00h
						None
Port Type               	BYTE    	FFh
						Other
==============================================================================


[Type 008] -- Port Connector Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	9 bytes
Struc. Handle           	WORD    	0016h
Inter. Ref. Designator  	STRING  	J9G1 - LPC SIDE BAND
Internal Connector Type 	BYTE    	FFh
						Other
Ext. Ref. Designator    	STRING  	
Ext. Conn. Type         	BYTE    	00h
						None
Port Type               	BYTE    	FFh
						Other
==============================================================================


[Type 008] -- Port Connector Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	9 bytes
Struc. Handle           	WORD    	0017h
Inter. Ref. Designator  	STRING  	J8F1 - UNIFIED
Internal Connector Type 	BYTE    	FFh
						Other
Ext. Ref. Designator    	STRING  	
Ext. Conn. Type         	BYTE    	00h
						None
Port Type               	BYTE    	FFh
						Other
==============================================================================


[Type 008] -- Port Connector Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	9 bytes
Struc. Handle           	WORD    	0018h
Inter. Ref. Designator  	STRING  	J6F1 - LVDS
Internal Connector Type 	BYTE    	FFh
						Other
Ext. Ref. Designator    	STRING  	
Ext. Conn. Type         	BYTE    	00h
						None
Port Type               	BYTE    	FFh
						Other
==============================================================================


[Type 008] -- Port Connector Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	9 bytes
Struc. Handle           	WORD    	0019h
Inter. Ref. Designator  	STRING  	J2F1 - LAI FAN
Internal Connector Type 	BYTE    	FFh
						Other
Ext. Ref. Designator    	STRING  	
Ext. Conn. Type         	BYTE    	00h
						None
Port Type               	BYTE    	FFh
						Other
==============================================================================


[Type 008] -- Port Connector Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	9 bytes
Struc. Handle           	WORD    	001Ah
Inter. Ref. Designator  	STRING  	J2G1 - GFX VID
Internal Connector Type 	BYTE    	FFh
						Other
Ext. Ref. Designator    	STRING  	
Ext. Conn. Type         	BYTE    	00h
						None
Port Type               	BYTE    	FFh
						Other
==============================================================================


[Type 008] -- Port Connector Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	9 bytes
Struc. Handle           	WORD    	001Bh
Inter. Ref. Designator  	STRING  	J1G6 - AC JACK
Internal Connector Type 	BYTE    	FFh
						Other
Ext. Ref. Designator    	STRING  	
Ext. Conn. Type         	BYTE    	00h
						None
Port Type               	BYTE    	FFh
						Other
==============================================================================


[Type 009] -- System Slots
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	17 bytes
Struc. Handle           	WORD    	0048h
Slot Designation        	STRING  	PCI-Express
Slot Type               	BYTE    	AAh
						AAh PCI Express x16
Slot Data Bus Width     	BYTE    	0Dh
						16x or x16
Current Usage           	BYTE    	04h
						In use
Slot Length             	BYTE    	04h
						Long Length
Slot ID                 	WORD    	0001h
Slot Characteristics 1  	BYTE    	04h
						Bit.2:Provides 3.3 Volts
Slot Characteristics 2  	BYTE    	01h
						Bit.0:PCI slot supports PME# signal
Segment Group Number    	WORD    	0000h
Bus Number              	BYTE    	00h
Device/Function Number  	BYTE    	08h
						Device Number:08h
						function number:00h
==============================================================================


[Type 009] -- System Slots
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	17 bytes
Struc. Handle           	WORD    	0049h
Slot Designation        	STRING  	PCI-Express 6
Slot Type               	BYTE    	A5h
						PCI Express
Slot Data Bus Width     	BYTE    	08h
						1x or x1
Current Usage           	BYTE    	04h
						In use
Slot Length             	BYTE    	04h
						Long Length
Slot ID                 	WORD    	0002h
Slot Characteristics 1  	BYTE    	04h
						Bit.2:Provides 3.3 Volts
Slot Characteristics 2  	BYTE    	01h
						Bit.0:PCI slot supports PME# signal
Segment Group Number    	WORD    	0000h
Bus Number              	BYTE    	00h
Device/Function Number  	BYTE    	E6h
						Device Number:E0h
						function number:06h
==============================================================================


[Type 009] -- System Slots
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	17 bytes
Struc. Handle           	WORD    	004Ah
Slot Designation        	STRING  	PCI-Express 7
Slot Type               	BYTE    	A5h
						PCI Express
Slot Data Bus Width     	BYTE    	08h
						1x or x1
Current Usage           	BYTE    	04h
						In use
Slot Length             	BYTE    	04h
						Long Length
Slot ID                 	WORD    	0003h
Slot Characteristics 1  	BYTE    	04h
						Bit.2:Provides 3.3 Volts
Slot Characteristics 2  	BYTE    	01h
						Bit.0:PCI slot supports PME# signal
Segment Group Number    	WORD    	0000h
Bus Number              	BYTE    	00h
Device/Function Number  	BYTE    	E7h
						Device Number:E0h
						function number:07h
==============================================================================


[Type 009] -- System Slots
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	17 bytes
Struc. Handle           	WORD    	004Bh
Slot Designation        	STRING  	PCI-Express 8
Slot Type               	BYTE    	A5h
						PCI Express
Slot Data Bus Width     	BYTE    	0Ah
						4x or x4
Current Usage           	BYTE    	04h
						In use
Slot Length             	BYTE    	04h
						Long Length
Slot ID                 	WORD    	0004h
Slot Characteristics 1  	BYTE    	04h
						Bit.2:Provides 3.3 Volts
Slot Characteristics 2  	BYTE    	01h
						Bit.0:PCI slot supports PME# signal
Segment Group Number    	WORD    	0000h
Bus Number              	BYTE    	00h
Device/Function Number  	BYTE    	E8h
						Device Number:E8h
						function number:00h
==============================================================================


[Type 010] -- On Board Devices Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	6 bytes
Struc. Handle           	WORD    	001Ch
Device Type             	BYTE    	83h
						Device Enabled
						Video
Description String      	STRING  	   To Be Filled By O.E.M.
==============================================================================


[Type 011] -- OEM Strings
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	5 bytes
Struc. Handle           	WORD    	001Dh
Count                   	BYTE    	01h
String #1               	STRING  	Default string
==============================================================================


[Type 012] -- System Configuration Options
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	5 bytes
Struc. Handle           	WORD    	001Eh
Count                   	BYTE    	01h
String #1               	STRING  	Default string
==============================================================================


[Type 013] -- BIOS Language Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	22 bytes
Struc. Handle           	WORD    	0043h
Installable Languages   	BYTE    	0Fh
Flags                   	BYTE    	00h
						The Current Language strings use the long format
Reserved                	15 BYTEs	00 00 00 00 00 00 00 00 00 00 00 00 00 00 00h
Current Language        	STRING  	en|US|iso8859-1
==============================================================================


[Type 014] -- Group Associations
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	20 bytes
Struc. Handle           	WORD    	004Eh
Group Name              	STRING  	Firmware Version Info
Item Type               	BYTE    	DDh
Item Handle             	WORD    	0044h
Unknown                 	BYTEs   	DD 45 00 DD 46 00 DD 47 00 DD 4C 00h
==============================================================================


[Type 014] -- Group Associations
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	8 bytes
Struc. Handle           	WORD    	0058h
Group Name              	STRING  	$MEI
Item Type               	BYTE    	DBh
Item Handle             	WORD    	0000h
==============================================================================


[Type 016] -- Physical Memory Array
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	23 bytes
Struc. Handle           	WORD    	0035h
Location                	BYTE    	03h
						System board or motherboard
Use                     	BYTE    	03h
						System memory
Memory Error Correction 	BYTE    	03h
						None
Maximum Capacity        	DWORD   	0400 0000h
						67108864 KB
Mem. Err. Info. Handle  	WORD    	FFFEh
						The system does not provide the error information structure.
Number of Memory Devices	WORD    	0004h
Extended Maximum Capacity	QWORD   	0000 0000 0000 0000h
==============================================================================


[Type 017] -- Memory Device
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	40 bytes
Struc. Handle           	WORD    	0036h
Phys. Mem. Array Handle 	WORD    	0035h
Mem. Err. Info. Handle  	WORD    	FFFEh
						The system does not provide the error information structure.
Total Width             	WORD    	0000h
						0 bits
Data Width              	WORD    	0000h
						0 bits
Size                    	WORD    	0000h
						No memory device is installed in the socket
Form Factor             	BYTE    	02h
						Unknown
Device Set              	BYTE    	00h
						The device is not part of a set
Device Locator          	STRING  	ChannelA-DIMM0
Bank Locator            	STRING  	BANK 0
Memory Type             	BYTE    	02h
						Unknown
Type Detail             	WORD    	0000h
Speed                   	WORD    	0000h
Manufacturer            	STRING  	
Serial Number           	STRING  	
Asset Tag               	STRING  	
Part Number             	STRING  	
Attributes              	BYTE    	00h
Extended Size           	DWORD   	0000 0000h
Configured Memory Clock Speed	WORD    	0000h
Minimum voltage         	WORD    	0000h
Maximum voltage         	WORD    	0000h
Configured voltage      	WORD    	0000h
==============================================================================


[Type 017] -- Memory Device
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	40 bytes
Struc. Handle           	WORD    	0037h
Phys. Mem. Array Handle 	WORD    	0035h
Mem. Err. Info. Handle  	WORD    	FFFEh
						The system does not provide the error information structure.
Total Width             	WORD    	0040h
						64 bits
Data Width              	WORD    	0040h
						64 bits
Size                    	WORD    	2000h
						8192 MB
Form Factor             	BYTE    	09h
						DIMM
Device Set              	BYTE    	00h
						The device is not part of a set
Device Locator          	STRING  	ChannelA-DIMM1
Bank Locator            	STRING  	BANK 1
Memory Type             	BYTE    	1Ah
						DDR4
Type Detail             	WORD    	4080h
						Bit.07:Synchronous
						Bit.14:Unbuffered (Unregistered)
Speed                   	WORD    	0A6Ah
Manufacturer            	STRING  	Kingston
Serial Number           	STRING  	2A6EAA09
Asset Tag               	STRING  	9876543210
Part Number             	STRING  	KHX2666C16/8G       
Attributes              	BYTE    	01h
Extended Size           	DWORD   	0000 0000h
Configured Memory Clock Speed	WORD    	0A6Ah
Minimum voltage         	WORD    	04B0h
Maximum voltage         	WORD    	04B0h
Configured voltage      	WORD    	04B0h
==============================================================================


[Type 017] -- Memory Device
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	40 bytes
Struc. Handle           	WORD    	0038h
Phys. Mem. Array Handle 	WORD    	0035h
Mem. Err. Info. Handle  	WORD    	FFFEh
						The system does not provide the error information structure.
Total Width             	WORD    	0000h
						0 bits
Data Width              	WORD    	0000h
						0 bits
Size                    	WORD    	0000h
						No memory device is installed in the socket
Form Factor             	BYTE    	02h
						Unknown
Device Set              	BYTE    	00h
						The device is not part of a set
Device Locator          	STRING  	ChannelB-DIMM0
Bank Locator            	STRING  	BANK 2
Memory Type             	BYTE    	02h
						Unknown
Type Detail             	WORD    	0000h
Speed                   	WORD    	0000h
Manufacturer            	STRING  	
Serial Number           	STRING  	
Asset Tag               	STRING  	
Part Number             	STRING  	
Attributes              	BYTE    	00h
Extended Size           	DWORD   	0000 0000h
Configured Memory Clock Speed	WORD    	0000h
Minimum voltage         	WORD    	0000h
Maximum voltage         	WORD    	0000h
Configured voltage      	WORD    	0000h
==============================================================================


[Type 017] -- Memory Device
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	40 bytes
Struc. Handle           	WORD    	0039h
Phys. Mem. Array Handle 	WORD    	0035h
Mem. Err. Info. Handle  	WORD    	FFFEh
						The system does not provide the error information structure.
Total Width             	WORD    	0040h
						64 bits
Data Width              	WORD    	0040h
						64 bits
Size                    	WORD    	2000h
						8192 MB
Form Factor             	BYTE    	09h
						DIMM
Device Set              	BYTE    	00h
						The device is not part of a set
Device Locator          	STRING  	ChannelB-DIMM1
Bank Locator            	STRING  	BANK 3
Memory Type             	BYTE    	1Ah
						DDR4
Type Detail             	WORD    	4080h
						Bit.07:Synchronous
						Bit.14:Unbuffered (Unregistered)
Speed                   	WORD    	0A6Ah
Manufacturer            	STRING  	Kingston
Serial Number           	STRING  	EEAEA9F3
Asset Tag               	STRING  	9876543210
Part Number             	STRING  	KF2666C16D4/8G      
Attributes              	BYTE    	01h
Extended Size           	DWORD   	0000 0000h
Configured Memory Clock Speed	WORD    	0A6Ah
Minimum voltage         	WORD    	04B0h
Maximum voltage         	WORD    	04B0h
Configured voltage      	WORD    	04B0h
==============================================================================


[Type 019] -- Memory Array Mapped Address
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	31 bytes
Struc. Handle           	WORD    	003Ah
Starting Address        	DWORD   	0000 0000h
End Address             	DWORD   	00FF FFFFh
Mem. Array Handle       	WORD    	0035h
Partition Width         	BYTE    	02h
Extended Starting Address	QWORD   	0000 0000 0000 0000h
Extended Ending Address 	QWORD   	0000 0000 0000 0000h
==============================================================================


[Type 020] -- Memory Device Mapped Address
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	35 bytes
Struc. Handle           	WORD    	003Fh
Starting Address        	DWORD   	0000 0000h
End Address             	DWORD   	007F FFFFh
Memory Device Handle    	WORD    	0037h
Mem. Map. Add. Handle   	WORD    	003Ah
Partition Row Position  	BYTE    	FFh
Interleave Position     	BYTE    	01h
Interleaved Data Depth  	BYTE    	02h
Extended Starting Address	QWORD   	0000 0000 0000 0000h
Extended Ending Address 	QWORD   	0000 0000 0000 0000h
==============================================================================


[Type 020] -- Memory Device Mapped Address
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	35 bytes
Struc. Handle           	WORD    	0040h
Starting Address        	DWORD   	0080 0000h
End Address             	DWORD   	00FF FFFFh
Memory Device Handle    	WORD    	0039h
Mem. Map. Add. Handle   	WORD    	003Ah
Partition Row Position  	BYTE    	FFh
Interleave Position     	BYTE    	02h
Interleaved Data Depth  	BYTE    	02h
Extended Starting Address	QWORD   	0000 0000 0000 0000h
Extended Ending Address 	QWORD   	0000 0000 0000 0000h
==============================================================================


[Type 026] -- Voltage Probe
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	22 bytes
Struc. Handle           	WORD    	0021h
Description             	STRING  	LM78A
Location and Status     	BYTE    	67h
						Location:Motherboard
						Status:OK
Max. value in mil.      	WORD    	8000h
Mini. value in mil.     	WORD    	8000h
Resolution              	WORD    	8000h
Tolerance               	WORD    	8000h
Accuracy                	WORD    	8000h
OEM-defined             	DWORD   	0000 0000h
Nominal Value           	WORD    	8000h
==============================================================================


[Type 026] -- Voltage Probe
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	22 bytes
Struc. Handle           	WORD    	0030h
Description             	STRING  	LM78A
Location and Status     	BYTE    	6Ah
						Location:Power Unit
						Status:OK
Max. value in mil.      	WORD    	8000h
Mini. value in mil.     	WORD    	8000h
Resolution              	WORD    	8000h
Tolerance               	WORD    	8000h
Accuracy                	WORD    	8000h
OEM-defined             	DWORD   	0000 0000h
Nominal Value           	WORD    	8000h
==============================================================================


[Type 027] -- Cooling Device
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	15 bytes
Struc. Handle           	WORD    	0027h
Temperature Probe Handle	WORD    	0024h
Device Type and Status  	BYTE    	67h
						Device Type:Power Supply Fan
						Status:OK
Cooling Unit Group      	BYTE    	01h
OEM-defined             	DWORD   	0000 0000h
Nominal Speed           	WORD    	8000h
Nominal Speed           	STRING  	Cooling Dev 1
==============================================================================


[Type 027] -- Cooling Device
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	15 bytes
Struc. Handle           	WORD    	002Ah
Temperature Probe Handle	WORD    	0024h
Device Type and Status  	BYTE    	67h
						Device Type:Power Supply Fan
						Status:OK
Cooling Unit Group      	BYTE    	01h
OEM-defined             	DWORD   	0000 0000h
Nominal Speed           	WORD    	8000h
Nominal Speed           	STRING  	
==============================================================================


[Type 027] -- Cooling Device
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	15 bytes
Struc. Handle           	WORD    	0032h
Temperature Probe Handle	WORD    	0031h
Device Type and Status  	BYTE    	67h
						Device Type:Power Supply Fan
						Status:OK
Cooling Unit Group      	BYTE    	01h
OEM-defined             	DWORD   	0000 0000h
Nominal Speed           	WORD    	8000h
Nominal Speed           	STRING  	Cooling Dev 1
==============================================================================


[Type 028] -- Temperature Probe
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	22 bytes
Struc. Handle           	WORD    	0024h
Description             	STRING  	LM78A
Location and Status     	BYTE    	67h
						Location:Motherboard
						Power supply is present
Maximum Value           	WORD    	8000h
Minimum Value           	WORD    	8000h
Resolution              	WORD    	8000h
Tolerance               	WORD    	8000h
Accuracy                	WORD    	8000h
OEM-defined             	DWORD   	0000 0000h
Nominal Value           	WORD    	8000h
==============================================================================


[Type 028] -- Temperature Probe
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	22 bytes
Struc. Handle           	WORD    	0031h
Description             	STRING  	LM78A
Location and Status     	BYTE    	6Ah
						Location:Power Unit
						Power supply is present
Maximum Value           	WORD    	8000h
Minimum Value           	WORD    	8000h
Resolution              	WORD    	8000h
Tolerance               	WORD    	8000h
Accuracy                	WORD    	8000h
OEM-defined             	DWORD   	0000 0000h
Nominal Value           	WORD    	8000h
==============================================================================


[Type 029] -- Electrical Current Probe
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	22 bytes
Struc. Handle           	WORD    	002Dh
Description             	STRING  	ABC
Location and Status     	BYTE    	67h
						Location:Motherboard
						Status:OK
Maximum Value           	WORD    	8000h
Minimum Value           	WORD    	8000h
Resolution              	WORD    	8000h
Tolerance               	WORD    	8000h
Accuracy                	WORD    	8000h
OEM-defined             	DWORD   	0000 0000h
Nominal Value           	WORD    	8000h
==============================================================================


[Type 029] -- Electrical Current Probe
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	22 bytes
Struc. Handle           	WORD    	0033h
Description             	STRING  	ABC
Location and Status     	BYTE    	6Ah
						Location:Power Unit
						Status:OK
Maximum Value           	WORD    	8000h
Minimum Value           	WORD    	8000h
Resolution              	WORD    	8000h
Tolerance               	WORD    	8000h
Accuracy                	WORD    	8000h
OEM-defined             	DWORD   	0000 0000h
Nominal Value           	WORD    	8000h
==============================================================================


[Type 032] -- System Boot Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	20 bytes
Struc. Handle           	WORD    	001Fh
Reserved                	6 BYTEs 	00 00 00 00 00 00h
Boot Status             	10 BYTEs	00 00 00 00 00 00 00 00 00 00h
						No errors detected
==============================================================================


[Type 034] -- Management Device
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	11 bytes
Struc. Handle           	WORD    	0020h
Description             	STRING  	LM78-1
Type                    	BYTE    	04h
						National Semiconductor LM78
Address                 	DWORD   	0000 0000h
Address Type            	BYTE    	03h
						I/O Port
==============================================================================


[Type 035] -- Management Device Component
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	11 bytes
Struc. Handle           	WORD    	0023h
Description             	STRING  	Default string
Management Device Handle	WORD    	0020h
Component Handle        	WORD    	0021h
Threshold Handle        	WORD    	0022h
==============================================================================


[Type 035] -- Management Device Component
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	11 bytes
Struc. Handle           	WORD    	0026h
Description             	STRING  	Default string
Management Device Handle	WORD    	0020h
Component Handle        	WORD    	0024h
Threshold Handle        	WORD    	0025h
==============================================================================


[Type 035] -- Management Device Component
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	11 bytes
Struc. Handle           	WORD    	0029h
Description             	STRING  	Default string
Management Device Handle	WORD    	0020h
Component Handle        	WORD    	0027h
Threshold Handle        	WORD    	0028h
==============================================================================


[Type 035] -- Management Device Component
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	11 bytes
Struc. Handle           	WORD    	002Ch
Description             	STRING  	Default string
Management Device Handle	WORD    	0020h
Component Handle        	WORD    	002Ah
Threshold Handle        	WORD    	002Bh
==============================================================================


[Type 035] -- Management Device Component
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	11 bytes
Struc. Handle           	WORD    	002Fh
Description             	STRING  	Default string
Management Device Handle	WORD    	0020h
Component Handle        	WORD    	002Dh
Threshold Handle        	WORD    	002Eh
==============================================================================


[Type 036] -- Management Device Threshold Data
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	16 bytes
Struc. Handle           	WORD    	0022h
Lower T.N.C             	WORD    	0001h
Upper T.N.C             	WORD    	0002h
Lower T.C               	WORD    	0003h
Upper T.C               	WORD    	0004h
Lower T.C               	WORD    	0005h
Upper T.C               	WORD    	0006h
==============================================================================


[Type 036] -- Management Device Threshold Data
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	16 bytes
Struc. Handle           	WORD    	0025h
Lower T.N.C             	WORD    	0001h
Upper T.N.C             	WORD    	0002h
Lower T.C               	WORD    	0003h
Upper T.C               	WORD    	0004h
Lower T.C               	WORD    	0005h
Upper T.C               	WORD    	0006h
==============================================================================


[Type 036] -- Management Device Threshold Data
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	16 bytes
Struc. Handle           	WORD    	0028h
Lower T.N.C             	WORD    	0001h
Upper T.N.C             	WORD    	0002h
Lower T.C               	WORD    	0003h
Upper T.C               	WORD    	0004h
Lower T.C               	WORD    	0005h
Upper T.C               	WORD    	0006h
==============================================================================


[Type 036] -- Management Device Threshold Data
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	16 bytes
Struc. Handle           	WORD    	002Bh
Lower T.N.C             	WORD    	0001h
Upper T.N.C             	WORD    	0002h
Lower T.C               	WORD    	0003h
Upper T.C               	WORD    	0004h
Lower T.C               	WORD    	0005h
Upper T.C               	WORD    	0006h
==============================================================================


[Type 036] -- Management Device Threshold Data
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	16 bytes
Struc. Handle           	WORD    	002Eh
Lower T.N.C             	WORD    	8000h
Upper T.N.C             	WORD    	8000h
Lower T.C               	WORD    	8000h
Upper T.C               	WORD    	8000h
Lower T.C               	WORD    	8000h
Upper T.C               	WORD    	8000h
==============================================================================


[Type 039] -- System Power Supply
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	22 bytes
Struc. Handle           	WORD    	0034h
Power Unit Group        	BYTE    	01h
Location                	STRING  	To Be Filled By O.E.M.
Device Name             	STRING  	To Be Filled By O.E.M.
Manufacturer            	STRING  	To Be Filled By O.E.M.
Serial Number           	STRING  	To Be Filled By O.E.M.
Asset Tag Number        	STRING  	To Be Filled By O.E.M.
Model Part Number       	STRING  	To Be Filled By O.E.M.
Revision Level          	STRING  	To Be Filled By O.E.M.
Max Power Capacity      	WORD    	8000h
Power Supply Char.      	WORD    	11A2h
						Power supply is present
						Power supply is unplugged from the wall
						DMTF Input Voltage Range Switching:Manual
						Status:Other
						DMTF Power Supply Type:Linear
						
						Power Switch
Input Voltage Probe Handle	WORD    	0030h
Cooling Device Handle   	WORD    	0032h
Input Current Probe Handle	WORD    	0033h
==============================================================================


[Type 041] -- Onboard Devices Extended Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	11 bytes
Struc. Handle           	WORD    	004Fh
Reference Designation   	BYTE    	Onboard - Other
Device Type             	BYTE    	81h
						Device Enabled
						Other
Device TypeInstance     	BYTE    	01h
Segment Group Number    	WORD    	0000h
Bus Number              	BYTE    	00h
==============================================================================


[Type 041] -- Onboard Devices Extended Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	11 bytes
Struc. Handle           	WORD    	0050h
Reference Designation   	BYTE    	Onboard - Other
Device Type             	BYTE    	81h
						Device Enabled
						Other
Device TypeInstance     	BYTE    	02h
Segment Group Number    	WORD    	0000h
Bus Number              	BYTE    	00h
==============================================================================


[Type 041] -- Onboard Devices Extended Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	11 bytes
Struc. Handle           	WORD    	0051h
Reference Designation   	BYTE    	Onboard - Other
Device Type             	BYTE    	81h
						Device Enabled
						Other
Device TypeInstance     	BYTE    	03h
Segment Group Number    	WORD    	0000h
Bus Number              	BYTE    	00h
==============================================================================


[Type 041] -- Onboard Devices Extended Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	11 bytes
Struc. Handle           	WORD    	0052h
Reference Designation   	BYTE    	Onboard - Other
Device Type             	BYTE    	81h
						Device Enabled
						Other
Device TypeInstance     	BYTE    	04h
Segment Group Number    	WORD    	0000h
Bus Number              	BYTE    	00h
==============================================================================


[Type 041] -- Onboard Devices Extended Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	11 bytes
Struc. Handle           	WORD    	0053h
Reference Designation   	BYTE    	Onboard - SATA
Device Type             	BYTE    	89h
						Device Enabled
						SATA Controller
Device TypeInstance     	BYTE    	01h
Segment Group Number    	WORD    	0000h
Bus Number              	BYTE    	00h
==============================================================================


[Type 041] -- Onboard Devices Extended Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	11 bytes
Struc. Handle           	WORD    	0054h
Reference Designation   	BYTE    	Onboard - Other
Device Type             	BYTE    	81h
						Device Enabled
						Other
Device TypeInstance     	BYTE    	05h
Segment Group Number    	WORD    	0000h
Bus Number              	BYTE    	00h
==============================================================================


[Type 041] -- Onboard Devices Extended Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	11 bytes
Struc. Handle           	WORD    	0055h
Reference Designation   	BYTE    	Onboard - Other
Device Type             	BYTE    	81h
						Device Enabled
						Other
Device TypeInstance     	BYTE    	06h
Segment Group Number    	WORD    	0000h
Bus Number              	BYTE    	00h
==============================================================================


[Type 041] -- Onboard Devices Extended Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	11 bytes
Struc. Handle           	WORD    	0056h
Reference Designation   	BYTE    	Onboard - Sound
Device Type             	BYTE    	87h
						Device Enabled
						Sound
Device TypeInstance     	BYTE    	01h
Segment Group Number    	WORD    	0000h
Bus Number              	BYTE    	00h
==============================================================================


[Type 041] -- Onboard Devices Extended Information
---------------------------------------
Name				Type		Data
====				====		====
Struc. Length           	BYTE    	11 bytes
Struc. Handle           	WORD    	0057h
Reference Designation   	BYTE    	Onboard - Other
Device Type             	BYTE    	81h
						Device Enabled
						Other
Device TypeInstance     	BYTE    	07h
Segment Group Number    	WORD    	0000h
Bus Number              	BYTE    	00h
