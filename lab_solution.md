Correlation Coefficient & Covariance: Temperature vs Ice Cream Sales
1. Given Dataset

We are analyzing the relationship between Temperature (X) and Ice Cream Sales (Y) across three days.

Day	Temperature (X)	Ice Cream Sales (Y)
1	20	100
2	25	120
3	15	80

Our goals:

Calculate means, deviations, covariance, variance, standard deviations, and the correlation coefficient

Interpret the results

Explain the meaning of the positive relationship

Confirm the relationship visually

2. Step 1 – Calculate the Means
Mean Temperature (X̄):
𝑋
ˉ
=
20
+
25
+
15
3
=
60
3
=
20
X
ˉ
=
3
20+25+15
	​

=
3
60
	​

=20
Mean Ice Cream Sales (Ȳ):
𝑌
ˉ
=
100
+
120
+
80
3
=
300
3
=
100
Y
ˉ
=
3
100+120+80
	​

=
3
300
	​

=100

Conclusion:

Mean temperature = 20°C

Mean ice cream sales = 100 units

These averages show the central value of each dataset.

3. Step 2 – Deviations From the Means

We calculate how far each value is from the mean.

Day	X	X − X̄	Y	Y − Ȳ
1	20	0	100	0
2	25	5	120	20
3	15	-5	80	-20

Interpretation:

Day 2 is above average in both temperature and sales

Day 3 is below average in both temperature and sales

This already suggests a positive relationship

4. Step 3 – Calculate the Covariance

Covariance shows whether the two variables move together.

Multiply deviations for each day:
Day	X − X̄	Y − Ȳ	(X − X̄)(Y − Ȳ)
1	0	0	0
2	5	20	100
3	-5	-20	100

Sum of the products:

0
+
100
+
100
=
200
0+100+100=200

Divide by number of data points (n = 3):

Cov
(
𝑋
,
𝑌
)
=
200
3
≈
66.67
Cov(X,Y)=
3
200
	​

≈66.67

Conclusion:

Covariance ≈ +66.67

Positive covariance means temperature and sales move in the same direction

5. Step 4 – Variance & Standard Deviation

Standard deviation is needed to calculate the correlation coefficient.

4.1 – Square Each Deviation
Temperature squared deviations

0
2
=
0
0
2
=0

5
2
=
25
5
2
=25

(
−
5
)
2
=
25
(−5)
2
=25

Sum = 50

Sales squared deviations

0
2
=
0
0
2
=0

20
2
=
400
20
2
=400

(
−
20
)
2
=
400
(−20)
2
=400

Sum = 800

4.2 – Variance (Mean of Squared Deviations)
Temperature variance
𝜎
𝑋
2
=
50
3
=
16.67
σ
X
2
	​

=
3
50
	​

=16.67
Sales variance
𝜎
𝑌
2
=
800
3
=
266.67
σ
Y
2
	​

=
3
800
	​

=266.67
4.3 – Standard Deviations
Temperature
𝜎
𝑋
=
16.67
≈
4.08
σ
X
	​

=
16.67
	​

≈4.08
Sales
𝜎
𝑌
=
266.67
≈
16.33
σ
Y
	​

=
266.67
	​

≈16.33

Conclusion:

Standard deviation of Temperature ≈ 4.08

Standard deviation of Sales ≈ 16.33

These measure typical variation around the mean.

6. Step 4.4 – Correlation Coefficient

Correlation standardizes covariance and ranges from -1 to +1.

Formula:

𝑟
=
Cov
(
𝑋
,
𝑌
)
𝜎
𝑋
⋅
𝜎
𝑌
r=
σ
X
	​

⋅σ
Y
	​

Cov(X,Y)
	​


Substitute values:

𝑟
=
66.67
4.08
×
16.33
r=
4.08×16.33
66.67
	​


Compute denominator:

4.08
×
16.33
≈
66.67
4.08×16.33≈66.67

Final result:

𝑟
≈
66.67
66.67
=
0.9999999999999998
≈
+
1
r≈
66.67
66.67
	​

=0.9999999999999998≈+1

Final Interpretation:

Correlation coefficient ≈ +1

This means a near-perfect positive linear relationship

As temperature increases, sales increase almost exactly in sync

7. Visualization Interpretation

The provided graphs show:

Temperature and sales plotted across three days

Mean lines (dashed) for both variables

A scatter plot comparing temperature vs. sales

A linear trend line through the scatter plot

What the visualization proves:
✔ Both variables move together

Above-average temperatures always correspond with above-average sales.
Below-average temperatures correspond with below-average sales.

✔ Trend line slopes upward

This confirms the strong positive relationship.

✔ Data points line up almost perfectly

This matches the correlation of +1.

✔ Visualization supports the math

The graphs visually validate the numerical result.

8. Final Summary

Mean Temperature = 20°C

Mean Sales = 100 units

Covariance = +66.67

σₓ = 4.08

σᵧ = 16.33

Correlation r ≈ +1

Overall Conclusion:

There is a very strong positive linear relationship between temperature and ice cream sales.
As temperature increases, sales reliably increase as well.
Both the statistical calculations and the visualizations support this conclusion.
