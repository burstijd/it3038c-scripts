Lab 7 Code

For Lab 7 I researched the package matplotlib

import matplotlib.pyplot as plt is used to import the mapping module.

This part of the code creates a line graph:

x = [1,2,3,4]
y = [1,2,3,4]
plt.plot(x,y)
plt.show()

This part of the code creates a bar graph:

plt.bar([1,2,3],[5,2,1])
plt.xlabel("This is x-axis label")
plt.ylabel("This is y-axis label")
plt.title("Simple Bar Chart")
plt.show()

This part of the code creates a pie chart:

percentage = [60,30,10]
language= ["Python","Java","C++"]
plt.pie(percentage,labels=language)
plt.title("Simple Pie Chart")
plt.show()
