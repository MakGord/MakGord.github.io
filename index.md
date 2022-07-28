## My Projects

---

### Project: Price Probability Plot 
---

[Full Project Link](https://makgord.github.io/Price_Probability_Plot/)

This project aims to create a statistical model that allows to visually estimate a potential level of magnitutde and direction of the price movement for a given security over a specified interval of time based on the historical data.

Below is the resulting plot for the following inputs: 

```
ticker="XBI"
start_date="2010-01-01"
end_date=date.today()
time_interval="1wk"
rounding_base=1
```
<img src="https://github.com/MakGord/Price_Probability_Plot/blob/main/price_probability_plot_XBI_2010-01-01_2022-07-28.png?raw=true"/>

Horizontal axis marks every dollar price-point visited by "XBI" index since 2010. Price resolution can be modifed by adjusting the rounding_base variable.
Vertical axis represents the percentage of period time the index price has spent at that price point. 
Normal Distribution is overlayed with red-dotted lines, where mu is last available price and sigma is standard deviation of 1-wk log return.

Interpreation Example: 
Since 2010 the price of XBI has touched $20 price mark nearly 7-times more than $17 price mark.
As of 07-28-2022 the price is at $83.40. By 08-04-2022 (1 week time frame), there is approximately a 68% chance for the price to stay between $79.76 and $87.04.


---


