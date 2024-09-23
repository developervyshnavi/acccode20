# acccode20
sql 
'''select ename
  2  from emp
  3  where sal>(select sal
  4  from emp
  5  where ename='ADAMS');'''

ENAME                                                                                               
----------                                                                                          
ALLEN                                                                                               
WARD                                                                                                
JONES                                                                                               
MARTIN                                                                                              
BLAKE                                                                                               
CLARK                                                                                               
SCOTT                                                                                               
KING                                                                                                
TURNER                                                                                              
FORD                                                                                                
MILLER                                                                                              

11 rows selected.

