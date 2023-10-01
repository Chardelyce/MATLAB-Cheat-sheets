# **MATLAB Calculus Cheat Sheet:smile:**

| Function Name | Definition |
| :---: | --- |
| **Symbolic Math** | |
| 💡 `syms` | Define symbolic variables for algebraic manipulations. |
| Example: `syms x y` |
| 💡 `solve` | Solve algebraic equations symbolically. |
| Example: `eqn = x^2 - 4*x + 4 == 0;`<br> `sol = solve(eqn, x);` |
| 💡 `diff` | Compute derivatives symbolically. |
| Example: `f = x^2 + 2*x + 1;`<br> `df = diff(f, x);` |
| 💡 `int` | Compute integrals symbolically. |
| Example: `f = x^2 + 2*x + 1;`<br> `F = int(f, x);` |
| **Numeric Calculations** | |
| 💡 `sum` | Calculate the sum of elements in an array. |
| Example: `A = [1, 2, 3, 4, 5];`<br> `total = sum(A);` |
| 💡 `prod` | Calculate the product of elements in an array. |
| Example: `A = [1, 2, 3, 4, 5];`<br> `product = prod(A);` |
| 💡 `mean` | Compute the mean (average) of data. |
| Example: `data = [75, 80, 85, 90, 95];`<br> `avg = mean(data);` |
| 💡 `std` | Calculate the standard deviation of data. |
| Example: `data = [75, 80, 85, 90, 95];`<br> `deviation = std(data);` |
| **Plotting** | |
| 💡 `plot` | Create 2D plots of data. |
| Example: `x = linspace(0, 2*pi, 100);`<br> `y = sin(x);`<br> `plot(x, y);` |
| 💡 `ezplot` | Create plots of symbolic expressions. |
| Example: `syms x`<br> `f = x^2 - 4*x + 4;`<br> `ezplot(f);` |
| **Linear Algebra** | |
| 💡 `inv` | Compute the inverse of a matrix. |
| Example: `A = [1, 2; 3, 4];`<br> `B = inv(A);` |
| 💡 `det` | Calculate the determinant of a matrix. |
| Example: `A = [1, 2; 3, 4];`<br> `determinant = det(A);` |
| **Numerical Methods** | |
| 💡 `fminunc` | Find the minimum of a function numerically. |
| Example: `fun = @(x) x^2 - 4*x + 4;`<br> `x0 = 0; % Initial guess`<br> `xmin = fminunc(fun, x0);` |
| 💡 `ode45` | Solve ordinary differential equations (ODEs). |
| Example: `dydt = @(t, y) -2*y;`<br> `[t, y] = ode45(dydt, [0, 5], 1);` |
| **Statistics** | |
| 💡 `normpdf` | Compute the probability density function of a normal distribution. |
| Example: `mu = 0; % Mean`<br> `sigma = 1; % Standard deviation`<br> `x = -3:0.1:3;`<br> `pdf = normpdf(x, mu, sigma);` |
| 💡 `binopdf` | Compute the probability mass function of a binomial distribution. |
| Example: `n = 10; % Number of trials`<br> `p = 0.5; % Probability of success`<br> `k = 0:10;`<br> `pmf = binopdf(k, n, p);` |
