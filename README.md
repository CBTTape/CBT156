# CBT156
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. 
Due to amazing work by Alison Zhang and Jake Choi repos are no longer deleted.

```
         MACRO                                                             @FILL
&NAME    @FILL &AREA=,&CHAR=40                                             @FILL
.*********************************************************************     @FILL
&NAME    MVI   &AREA,X'&CHAR'                                              @FILL
         MVC   &AREA+1(L'&AREA-1),&AREA                                    @FILL
.*********************************************************************     @FILL
         MEXIT                                                             @FILL
         MEND                                                              @FILL
```
