# Data-Science-Workbook

2.2.5 Exercises
How many rows are in penguins? How many columns?

What does the bill_depth_mm variable in the penguins data frame describe? Read the help for ?penguins to find out.

Make a scatterplot of bill_depth_mm vs. bill_length_mm. That is, make a scatterplot with bill_depth_mm on the y-axis and bill_length_mm on the x-axis. Describe the relationship between these two variables.

What happens if you make a scatterplot of species vs. bill_depth_mm? What might be a better choice of geom?

Why does the following give an error and how would you fix it?

ggplot(data = penguins) + 
  geom_point()

What does the na.rm argument do in geom_point()? What is the default value of the argument? Create a scatterplot where you successfully use this argument set to TRUE.

Add the following caption to the plot you made in the previous exercise: “Data come from the palmerpenguins package.” Hint: Take a look at the documentation for labs().

Recreate the following visualization. What aesthetic should bill_depth_mm be mapped to? And should it be mapped at the global level or at the geom level?
