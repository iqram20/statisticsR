# MAT 120 R Quick Reference

## Create a vector

```r
x <- c(4, 7, 7, 9, 12)
```

## Basic summaries

```r
length(x)
mean(x)
median(x)
sd(x)
summary(x)
fivenum(x)
```

## Frequency tables

```r
table(x)
prop.table(table(x))
```

## Graphs

```r
barplot(table(x))
hist(x)
boxplot(x)
plot(x, y)
```

## Random sampling

```r
sample(1:100, 10)
sample(x, 3)
```

## Correlation and regression

```r
cor(x, y)
fit <- lm(y ~ x)
summary(fit)
plot(x, y)
abline(fit)
```

## Binomial distribution

```r
dbinom(x, size = n, prob = p)
pbinom(x, size = n, prob = p)
```

## Normal distribution

```r
pnorm(z)
qnorm(p)
pnorm(x, mean = mu, sd = sigma)
qnorm(p, mean = mu, sd = sigma)
```

## t procedures

```r
t.test(x)
t.test(x, mu = mu0)
t.test(x, mu = mu0, alternative = "greater")
t.test(x, mu = mu0, alternative = "less")
```
