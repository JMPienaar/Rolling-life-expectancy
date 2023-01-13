# Rolling-life-expectancy

Refer to sheet "Method" in LE Method.xlsx			
			
Col. M 	Age-bands: Age bands identified by age at start

Col. N	Mx: Mortality rate for each age band for a period derived from real world data

Col. P	Interval: Interval calculated from Col M. Intervals can be any size and different sizes up to max 19 intervals in this implementation

Col. Q	l(x): Calculate proportion of initial population surviving at start of age band

Col. R	Lx: Average years survived by end of interval

Col. O	e(x): Expection of remaining life at start of interval: sum of Lx with adjustment for final open ended age band

			
The result of this calculation at age 0 is implemented in a single cell (C19)	

Compared to the stepwise result (C18)	

The results for 2015-19(C3:C7) are plotted against the WHO annual published LE (Sheet:WHO LE) for selected countries (Sheet:Mortality rates)) 	

Sheet:Plot shows R^2 for each country. Also displayed in Sheet:Method by selecting a country in B1			
