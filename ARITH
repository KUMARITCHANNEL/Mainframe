      ********************************************
      * COBOL PROGRAM USING ARITHMETIC OPERATION *
      * DATE : 07.08.2020                        *
      * ADD , MULTIPLY , SUBTRACT , DIVIDE       *
      * COMPUTE                                  *
      * ON SIZE ERROR                            *
      * AUTHOR : VIJAY KUMAR                     *
      ********************************************
       IDENTIFICATION DIVISION.
       PROGRAM-ID. IFPGM.
       DATA DIVISION.
       WORKING-STORAGE SECTION.
          01 WS-A   PIC 9(03) VALUE 20.
          01 WS-B   PIC 9(03) VALUE 30.
          01 WS-C   PIC 9(03).
          01 WS-D   PIC 9(03).
          01 WS-E   PIC 9(03).
          01 WS-F   PIC 9(03).
          01 WS-G   PIC 9(03).
          01 WS-ITEM PIC 9(03) VALUE 47.
          01 WS-DOZENS PIC 9(03).
          01 WS-LEFT PIC 9(03).
          01 WS-TOT  PIC 9(01).
       PROCEDURE DIVISION.
       ARITHMETIC-OPERA.
           ADD WS-A TO WS-B GIVING WS-C.
           DISPLAY 'ADD OF TWO NUMBERS : ' WS-C.
           SUBTRACT WS-A FROM WS-B GIVING WS-D.
           DISPLAY 'SUB OF TWO NUMBERS : ' WS-D.
           MULTIPLY WS-A BY WS-B GIVING WS-E.
           DISPLAY 'MUL OF TWO NUMBERS : ' WS-E.
           DIVIDE WS-B INTO WS-A GIVING WS-F.
           DIVIDE 12 INTO WS-ITEM GIVING WS-DOZENS REMAINDER WS-LEFT
           DISPLAY 'DIV OF TWO NUMBERS : ' WS-F.
           DISPLAY 'WS-DOZENS          : ' WS-DOZENS.
           DISPLAY 'WS-REMAINDER       : ' WS-LEFT.
           COMPUTE WS-G = WS-A + WS-B.
           DISPLAY 'USING THE COMPUTE: ' WS-G.
           ADD WS-A, WS-B, WS-ITEM GIVING WS-TOT
               ON SIZE ERROR
               DISPLAY "NO MEMORY".
           STOP RUN.
