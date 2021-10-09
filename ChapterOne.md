---
does not show in Markdown preview
---

### Proposed Answers for Chapter One


__1.1__

Pc, warehouse, super computers, and personal mobile devices are mentioned by the authors, but for a grander view of the scope of computing have a look at the types of Linux distributions [here](https://simple.wikipedia.org/wiki/List_of_Linux_distributions)

1.2
|          Real World         |          Computing         |
|:---------------------------:|:--------------------------:|
|                   Elevators | Common case                |
|             Assembly  lines | Piplining                  |
|           Navigtion systems | Performancd via prediction |
|           Suspension bridge | Parallelism                |
|        Library service desk | Memories                   |
| Dependibility via redunancy | CMOS                       |
|           Self driving cars | Abstraction                |
|                   Catapults | Moore's Law                |


Note: Methaphor is in the eye of the beholder.

__1.3__

The compiler translates code to assembly language and the assembler then
translates the assembly language to machine code.

__1.4__

8x8x8x1280x1024 = 671,088,640
Six hundred and seventy one million bits > 6.71 seconds.

__1.5 Part a.__

|         Processor        |    GHz    |           CPI          |               GIPS              |
|:------------------------:|:---------:|:----------------------:|:-------------------------------:|
|         Processor        | GigaHertz | Cycles per Instruction | Billion Instructions per second |
|                          |           |                        |                                 |
|            P1            |     3     |           1.5          |                2                |
|            P2            |    2.5    |            1           |               2.5               |
|            P3            |        |           2.2          |               1.8               |
|                          |           |                        |                                 |
| Formula: GHZ x CPI +GIPS |           |                        |                                 |
| Thus: P2 is fastest      |           |                        |                                 |_

__1.5 Part b.__

P1 > 20 billion instructions
P2 > 25 billion instructions
P3 > 18 billion instructions

P1 > 30 billion clock cycles
P2 > 25 billion clock cycles
P3 > 40 billion clock cycles

__1.5c__

|  Processor  | execution time | Executed instructions | clock cycles per instruction | Total Clock cycles | Seconds per clock cycle | instructions per second | clock rate (clock cycles per second) |   |   |
|:-----------:|:--------------:|:---------------------:|:----------------------------:|:------------------:|:-----------------------:|:-----------------------:|:------------------------------------:|---|---|
|      P1     |      10.00     |        2.00E+10       |             1.50             |      3.00E+10      |         3.33E-10        |         2.00E+09        |               3.00E+09               |   |   |
| Pi Improved |      7.00      |        2.00E+10       |             1.80             |      3.60E+10      |         1.94E-10        |         2.86E+09        |               5.14E+09               |   |   |
|             |                |                       |                              |                    |                         |                         |                                      |   |   |
|      P2     |      10.00     |        3.00E+10       |             1.00             |      3.00E+10      |         3.33E-10        |         2.00E+09        |               3.00E+09               |   |   |
| P2 Improved |      7.00      |        3.00E+10       |             1.20             |      3.60E+10      |         1.94E-10        |         4.29E+09        |               5.14E+09               |   |   |
|             |                |                       |                              |                    |                         |                         |                                      |   |   |
|      P3     |      10.00     |        1.80E+10       |             2.20             |      1.80E+10      |         5.56E-10        |         1.80E+09        |               4.00E+09               |   |   |
| P3 improved |      7.00      |        1.80E+10       |             2.64             |      4.75E+10      |         1.47E-10        |         2.57E+09        |               6.79E+09               |   |   |
Note: Clock speed is the combination of a hardware ocillator and multipliers. The clock speed can be adjusted by BIOS settings for a single chip and the penalty is heat. In a new design, the penalty can be increased instructions.







