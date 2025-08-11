# Simulating-Microbial-Growth-Curves
Simulated microbial growth curves using R with logistic modeling and visualization

I created a fake dataset based on a logistic model of growth for the fake microbes. I generated growth data for three temperature levels so that I could compare growth at each temperature. 

Once the dataset was generated, I was able to plot it using ggplot. Based on the results of the plot, the microbe density at the 25 second mark was the highest for the temperature of 35 degrees C, which was the highest temperature that microbe growth was simulated for. 

This practice project helped me better understand how to nest data within datasets and why we would use that tool. Nesting allows me to bundle the data by the temperature level, which then helps keep the data frame organized as I apply the nls function (nonlinear model fitting function). Using nesting enables me to efficiently apply the model fitting function to each temperature group without manually repeating the process multiple times or subsetting the data repeatedly.
