# Similarity Table 

The table bellow presents the similarity measure between symbols in time series from very similar (**1**) to less similar (**0**)

+ The maximum similarity is 1 and stands for the symbols identity.

+ For example, **FD** is more similar to **TD** than to **AD** because: *Similarity(FD, TD)* = **0.7** **>** *Similarity(FD, AD)* = **0.3**

  

|        |  AD  |  FD  |  TD  |  NM  |  BI  |  OP  |  RD  |
| :----: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| **AD** |  1   | 0.3  | 0.2  | 0.4  | 0.3  | 0.4  | 0.3  |
| **FD** | 0.3  |  1   | 0.7  | 0.4  | 0.4  | 0.4  | 0.4  |
| **TD** | 0.2  | 0.7  |  1   | 0.3  | 0.5  | 0.3  | 0.4  |
| **NM** | 0.4  | 0.4  | 0.3  |  1   | 0.9  | 0.9  | 0.9  |
| **BI** | 0.3  | 0.4  | 0.5  | 0.9  |  1   | 0.9  | 0.9  |
| **OP** | 0.4  | 0.4  | 0.3  | 0.9  | 0.9  |  1   | 0.9  |
| **RD** | 0.3  | 0.4  | 0.4  | 0.9  | 0.9  | 0.9  |  1   |

Table: Similarity table between symbols in time series: the more similar the symbols are, the higher the value is, and vice versa. 

