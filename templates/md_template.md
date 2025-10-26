## Contact Info

$for(Contact)$
$for(it/pairs)$
**$it.key$**: $it.value$  
$endfor$
$endfor$

## Summary

$Summary$

## Work Experience

$for(Work)$
### $Work.Role$ - $Work.Start$ to $Work.End$
*$Work.Company$*  
$for(Work.Summary)$
$for(it)$
$it$
$endfor$
$endfor$  
$if(Work.Tools)$
**Tools used:**
$for(Work.Tools)$
$for(it)$
- $it$
$endfor$
$endfor$
$endif$
$endfor$

## Education

$for(Education)$
### $Education.Degree$ - $Education.End$
*$Education.Institution$*
$endfor$