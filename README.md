# PC Engine Boiler Plate
Assembly boiler plate for the PC Engine / TurboGrafx-16 console targeting CL65. Written in HuC6280 assembly (HuC6280 CPU based on the 65C02). 

PC Engine documentation and other resources:
+ [PC Engine Hardware Breakdown](https://www.copetti.org/writings/consoles/pc-engine)
+ [PC Engine CPU Registers](http://www.magicengine.com/mkit/doc_hard_cpu.html)
+ [PC Engine VDC Registers](http://www.magicengine.com/mkit/doc_hard_vdc.html)
+ [PC Engine VCE Registers](http://www.magicengine.com/mkit/doc_hard_vce.html)
+ [CPU Memory Map](https://pce.nesdev.org/wiki/CPU_memory_map)
+ [Chibiakumas Guides](https://www.chibiakumas.com/6502/pcengine.php)

## Compile
```
cl65 -t pce -C hucard.cfg -o game.pce main.asm -Ln labels.txt
```

Tiles edited with YYCHR using format **4BPP PCE(SG)**.
