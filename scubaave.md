## Calculate weighted average depth of a scuba dive that has multiple descents

![scubave](https://github.com/carolynvlasveld/resources/blob/main/ewensponds.jpg)

Sometimes a dive computer records average depths of multiple ‘subdives’ from a dive event involving multiple ascents to the surface (e.g., if you dive through [Ewens Ponds](https://www.parks.sa.gov.au/parks/ewens-ponds-conservation-park) in the image above, you have to pass through some very shallow channels and avoid disturbing the fragile vegetation underneath).

If you want to log an accurate average depth from all descents, you can use the [weighted arithmetic mean](https://en.wikipedia.org/wiki/Weighted_arithmetic_mean).

<br>**For a dive with two ‘subdives’:**

Let:

$d_{\text{total}} = \text{average depth weighted by subdiving time}$

$t_1 = \text{duration of descent 1}$

$t_2 = \text{duration of descent 2}$

$d_1 = \text{average depth of descent 1}$

$d_2 = \text{average depth of descent 2}$<br>

<br>Formula:

$d_{\text{total}} = \frac{(t_1 \times d_1) + (t_2 \times d_2)}{t_1 + t_2}$

<br>**A working example for a dive involving three ‘subdives’:**

Descent one: 6 mins, average depth of 3.1 m\
Descent two: 5 mins, average depth of 2.6 m\
Descent three: 18 mins, average depth of 12.0 m<br><br>

$d_{\text{total}} = \frac{(t_1 \times d_1) + (t_2 \times d_2) + (t_3 \times d_3)}{t_1 + t_2 + t_3}$

$d_{\text{total}} = \frac{(6 \times 3.1) + (5 \times 2.6) + (18 \times 12.0)}{6 + 5 + 18}$

$d_{\text{total}} \approx \text{8.5 m}$

---

Written by [Carolyn Vlasveld](https://carolynvlasveld.github.io/)

