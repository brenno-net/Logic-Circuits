Tabela de estados primitivos para estudo de um circuito proposto em classe

 ** | STATE | P'R'    | P'R    | PR    | PR'    | Z | **
    |-------|---------|--------|-------|--------|---|
    | IDLE  | IDLE*   | IDLE*  | RESET | PULSE  | 0 |
    | PULSE | PULSE*  | IDLE   | PASS  | PULSE* | 1 |
    | RESET | IDLE    | IDLE   | RESET*| RESET* | 0 |
    | PASS  | ---     | ---    | RESET | ---    | 0 |
