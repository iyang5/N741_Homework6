<!-- R Commander Markdown Template -->

Replace with Main Title
=======================

### Your Name

### 2018-04-03







```r
> RegModel.1 <- lm(cesd~mcs, data=h1)
> summary(RegModel.1)
```

```

Call:
lm(formula = cesd ~ mcs, data = h1)

Residuals:
     Min       1Q   Median       3Q      Max 
-27.3593  -6.7277  -0.0024   6.2374  24.4239 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept) 53.90219    1.14723   46.98   <2e-16 ***
mcs         -0.66467    0.03357  -19.80   <2e-16 ***
---
Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1

Residual standard error: 9.164 on 451 degrees of freedom
Multiple R-squared:  0.465,	Adjusted R-squared:  0.4638 
F-statistic:   392 on 1 and 451 DF,  p-value: < 2.2e-16
```


```r
> RegModel.2 <- lm(cesd~age, data=h1)
> summary(RegModel.2)
```

```

Call:
lm(formula = cesd ~ age, data = h1)

Residuals:
    Min      1Q  Median      3Q     Max 
-32.029  -7.866   1.161   8.216  27.093 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept) 32.36327    2.78769  11.609   <2e-16 ***
age          0.01359    0.07643   0.178    0.859    
---
Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1

Residual standard error: 12.53 on 451 degrees of freedom
Multiple R-squared:  7.007e-05,	Adjusted R-squared:  -0.002147 
F-statistic: 0.03161 on 1 and 451 DF,  p-value: 0.859
```


```r
> RegModel.3 <- lm(cesd~female, data=h1)
> summary(RegModel.3)
```

```

Call:
lm(formula = cesd ~ female, data = h1)

Residuals:
    Min      1Q  Median      3Q     Max 
-33.888  -7.888   1.112   8.402  26.402 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)  31.5983     0.6626   47.69  < 2e-16 ***
female        5.2896     1.3633    3.88  0.00012 ***
---
Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1

Residual standard error: 12.32 on 451 degrees of freedom
Multiple R-squared:  0.0323,	Adjusted R-squared:  0.03016 
F-statistic: 15.05 on 1 and 451 DF,  p-value: 0.00012
```


```r
> RegModel.4 <- lm(cesd~homeless, data=h1)
> summary(RegModel.4)
```

```

Call:
lm(formula = cesd ~ homeless, data = h1)

Residuals:
    Min      1Q  Median      3Q     Max 
-33.024  -7.840   0.976   7.976  26.160 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept)   31.840      0.799  39.850   <2e-16 ***
homeless       2.184      1.176   1.856    0.064 .  
---
Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1

Residual standard error: 12.48 on 451 degrees of freedom
Multiple R-squared:  0.007584,	Adjusted R-squared:  0.005383 
F-statistic: 3.446 on 1 and 451 DF,  p-value: 0.06404
```


```r
> RegModel.5 <- lm(cesd~mcs, data=h1)
> summary(RegModel.5)
```

```

Call:
lm(formula = cesd ~ mcs, data = h1)

Residuals:
     Min       1Q   Median       3Q      Max 
-27.3593  -6.7277  -0.0024   6.2374  24.4239 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept) 53.90219    1.14723   46.98   <2e-16 ***
mcs         -0.66467    0.03357  -19.80   <2e-16 ***
---
Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1

Residual standard error: 9.164 on 451 degrees of freedom
Multiple R-squared:  0.465,	Adjusted R-squared:  0.4638 
F-statistic:   392 on 1 and 451 DF,  p-value: < 2.2e-16
```


```r
> RegModel.6 <- lm(cesd~pss_fr, data=h1)
> summary(RegModel.6)
```

```

Call:
lm(formula = cesd ~ pss_fr, data = h1)

Residuals:
    Min      1Q  Median      3Q     Max 
-32.704  -8.404   0.896   8.171  28.771 

Coefficients:
            Estimate Std. Error t value  Pr(>|t|)    
(Intercept)   36.704      1.132  32.437   < 2e-16 ***
pss_fr        -0.575      0.145  -3.966 0.0000851 ***
---
Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1

Residual standard error: 12.32 on 451 degrees of freedom
Multiple R-squared:  0.0337,	Adjusted R-squared:  0.03155 
F-statistic: 15.73 on 1 and 451 DF,  p-value: 0.00008506
```


```r
> LinearModel.8 <- lm(cesd ~ age, data=h1)
> summary(LinearModel.8)
```

```

Call:
lm(formula = cesd ~ age, data = h1)

Residuals:
    Min      1Q  Median      3Q     Max 
-32.029  -7.866   1.161   8.216  27.093 

Coefficients:
            Estimate Std. Error t value Pr(>|t|)    
(Intercept) 32.36327    2.78769  11.609   <2e-16 ***
age          0.01359    0.07643   0.178    0.859    
---
Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1

Residual standard error: 12.53 on 451 degrees of freedom
Multiple R-squared:  7.007e-05,	Adjusted R-squared:  -0.002147 
F-statistic: 0.03161 on 1 and 451 DF,  p-value: 0.859
```


```r
> LinearModel.1 <- lm(cesd ~ age + female + pss_fr + homeless + pcs + mcs, 
+   data=h1)
> summary(LinearModel.1)
```

```

Call:
lm(formula = cesd ~ age + female + pss_fr + homeless + pcs + 
    mcs, data = h1)

Residuals:
     Min       1Q   Median       3Q      Max 
-25.1711  -5.9894  -0.2077   5.5706  27.3137 

Coefficients:
            Estimate Std. Error t value     Pr(>|t|)    
(Intercept) 65.30046    3.18670  20.492      < 2e-16 ***
age         -0.01348    0.05501  -0.245       0.8065    
female       2.35028    0.98810   2.379       0.0178 *  
pss_fr      -0.25569    0.10567  -2.420       0.0159 *  
homeless     0.46545    0.84261   0.552       0.5810    
pcs         -0.23639    0.03987  -5.929 0.0000000061 ***
mcs         -0.62093    0.03261 -19.042      < 2e-16 ***
---
Signif. codes:  0 '***' 0.001 '**' 0.01 '*' 0.05 '.' 0.1 ' ' 1

Residual standard error: 8.683 on 446 degrees of freedom
Multiple R-squared:  0.5249,	Adjusted R-squared:  0.5185 
F-statistic: 82.14 on 6 and 446 DF,  p-value: < 2.2e-16
```


```r
> LinearModel.8 <- lm(cesd ~ age, data=h1)
```



