## MersennePrimeExponentQ

```
MersennePrimeExponentQ(n)
```

> returns `True` if `2^n - 1` is a prime number. Currently `0 <= n <= 45` can be computed in reasonable time.

### Examples

```
>> Select(Range(10000), MersennePrimeExponentQ)
{2,3,5,7,13,17,19,31,61,89,107,127,521,607,1279,2203,2281,3217,4253,4423,9689,9941}
```