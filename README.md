# Implementation of Perceptron Model

## Procedure:

1. Set random weights (W) and bias (b)
2. First quadrant points was labeled as “1” and eighth quadrant points was labeled as “-1”
3. Train and test data points were splitted. ( 80% train, 20% test)
4. For every misclassified point (p1, p2, …, pn):
    4.1 if First quadrant point (i.e. prediction = 1 WX+b ≥ 0 but should be < 0)
        For i <- 1 to n
        update W <- W - α * xi
        update bias<- bias - α
    4.2 if Eighth quadrant point (i.e. prediction = -1 WX+b <0 but should be >=0)
        For i <- 1 to n
        update W <- W + α * xi
        update bias <- bias + α

**First quadrant points & eighth quadrant points:**
![Image](https://i.ibb.co/YkcfYYD/Ads-z.png)
**Decision plane and all samples after implementation:**
![Image](https://i.ibb.co/RbdGMk5/Ads-z.png)
