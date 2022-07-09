# segregation
R package for calculating measures of social segregation in schools


## TODO: 

[] Measures of segregation functions

  [] Dissimilarity index
  
  [] Hutchen's Square Root
  
  [] Intra-class correlation (steal from other repo?) 
  
  [] D-Index (kelly and price)
  
  [] RDCI (steal from other repo?)
  
  [] Inequity score (really gotta figure this one out. Based on Donna Ford
  
  [] Ds (racial Dispersion. Check for accuracy) 
  
[] segregation curves ggplot proto

All of these should theoretically be pipeable or `mutate`able functions e.g. 

```R
data |>
   mutate(RDCI = RDCI(target, population))
```
