
**Simulate BBH and NBH ToOs** (for lensed BNS and BBH see https://github.com/fedhere/_scoc_/blob/main/ToOGWruns_lensedBNS.md and https://github.com/fedhere/_scoc_/blob/main/ToOGWruns_BBH.md)

**N total = 22** triggers

All after June 2027 and before January 2030 _should we simulate the yield or the population??_

Case A) 9 triggers with 30 sq deg area -> yealds 3 visible. Only cover if center in footprint

Case B) 15 triggers with 50 sq deg area -> yields 5 observable. Only cover if center in footprint

Case C) 24 triggers with 100 sq deg area -> yelds 8 observable. Only cover if center in footprint

Case D) 6 triggers with 250 sq deg area -> yelds 4 observable. Only cover if center in footprint

Case E) 12 triggers with 500 sq deg area -> yelds 2 observable. Only cover if center in footprint

Simulate Tw observability window of area of interest randomly

**A:** (3)
*  Night 0:
      
        if Tw> 4.7h:

           4x(u)griz(y)) x 3 passes
   
        if 3.2h < Tw < 4.7h:
   
           4x(u)griz(y)) x 2 passes
   
        if Tw < 3.2h:
   
           4x(u)griz(y) x 1 passes
* Night 1,2:

        4x(u)griz(y) x 1 pass
* Night 3 only 1/3 of the times:

        4x(u)griz(y) x 1 pass
  

**B/C:** (13)
* Night 0:

      if Tw> 4.7h:

        (4xgri) x 3 passes

      else if 3.2h < Tw < 4.7h:

        (4xgri) x 3 passes

      else if Tw < 3.2h:

        (4xgri) + (4xr)
* Night 1,2:

      6xri x 1 pass

* Night 3 only 1/3 of the times:

      6xri x 1 pass
      

**D/E:** (6)
* Night 0:

        1xgr x 1 pass
  
* Night 1,2:
  
        4xgr 30s x 1 pass
 
* Night 3 only 1/3 of the times:
  
        4xgr x 1 pass


