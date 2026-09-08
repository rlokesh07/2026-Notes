EFCS 287 Lecture 2

Input size $n$
$n$ could be bits, or items put into the input

Conting Steps

Variable assignment, arithmetic operation, compression,
array indexing, runter reference, function calls
returns are idealized one step

for loop steps: (Init, check, update)
$n$ for $n$th
$n$ states
$1+n$ for check+find

int func(int a) &amp;c
int sum = 0;
for (int i = 0; i &lt; 0; &lt; 1) &amp;c
sum += i;
q
return sum;
1 step
1 step
1+1+2n step
1 x n step
1 step
4+3n

$f(n) = O(q(n))$ if $c(70) = (q(n))$ then $n \geq 2$
$f\left( \frac{m}{n-2} \alpha \left( \frac{f(n)}{q(n)} \right) \right)$ converges then you know $f(n) \geq O(q(n))$
but if not then its not necessary