# Data Analysis Report

## Introduction:
<p style="text-align: justify;">This report delves into the fascinating world of red wine, employing a data-driven approach to analyze its composition and characteristics. Utilizing a variety of visualizations and statistical methodologies, we unveil the intricate relationships between key parameters such as acidity and quality ratings. Through meticulous examination, we uncover hidden patterns and dependencies, thereby illuminating a deeper understanding of red wine's complex nature.<p>



## Analysis

### Figure 1:
![Figure 1](C:\Users\ASARE\Desktop\11296641\Figure1.png)
<p style="text-align: justify;">
This 1st figure, displaying a pie chart, shows the distribution of the quality rating of all red wine instances recorded in the dataset. Most of the red wine had a rating of 5.0(ie having a 42.6% distribution), followed by the 6.0 rating with a 39.9% distribution. Red wine instances having quality ratings of 3.0 had the least distribution with 0.6%.<p>


### Figure 2:
![Figure 2](C:\Users\ASARE\Desktop\11296641\Figure2.png)

<p style="text-align: justify;">Figure 2 is composed of 25 individual plots. Each row corresponds to a certain column in the dataset, being plotted against other columns of the datasets using different graphs.<p>
	<p style="text-align: justify;">The first row consists of 1 histogram, and 5 heatmaps of other columns plotted against fixed acidity. The aim of these 5 plots is to show the behaviour as well as how fixed acidity changes with respect to other parameters ie. volatile acidity, citric acid, residual sugar, and chlorides respectively. The first plot, which is the histogram, is a repetition of figure 1. The second plot shows how fixed acidity changes with respect to volatile acidity. It can be observed that red wine instances in the dataset with fixed acidity values from 5 to 10 have volatile acidic values around the 0.5 mark(ie. close to 0.5), and values above 10, having sparsely distributed volatile acidic values.Also from the heatmap of citric acid plotted against fixed acidity, it can be seen that fixed acidity increases with increasing citric acidity. For the last 2 heatmap plots, it can be observed that red wine instances with fixed acidity values around 7 with 7 inclusive have a higher frequency at residual sugar and chloride values greater than 0 but less than 4, and a constant linear relationship between each of the paramters plotted.<p><p style="text-align: justify;">
	The second row consists of a scatter plot, a histogram, and 3 heatmaps. The scatter plot shows no defining pattern, but implies that red wine with fixed acidity values from 5 to 15 have occurences spread out across volatile acidity values from 0 to 1.5. This shows that the fixed acidity of red wine isn't heavily dependent on volatility. The histogram for the frequency of volatility shows that there is a very low availability of wine having values greater than 1.0. The frequency red wine increases steadily, and then declines again to the near zero mark. Hence most of the wine instances have volatile acidity values around 0.5, with 0.5 inclusive. The heatmap showing a plot of citric acid against volatile acidity implies that there is an inverse relationship between the two. The fourth and last heatmaps show that volatile acidity does not depend on residual sugar and chlorides present in the red wine, but most of the values around 0.5 have residual sugar values less than 2.5 and chloride values less than 1.0.<p><p style="text-align: justify;">
	The third row shows behaviour of citric acidity relative to other measurements(parameters). The first plot informs us that the citric acidity of red wine is directly proportional to its fixed acidity. Fewer occurences of wine with fixed acidity values of 15 or around that value exist, and exist in the range of 0.50 to 0.75. The second plot, also a scatter plot, shows that citric acid is indirectly proportional to volatile acidity, and a small number of the red wine has volatile acidity greater than 1. The histogram implies the fact that the frequency of red wine decreases as the citric acidity content increase, meaning citric acid content red wine were collected and are available. The heatmaps in that row also show that the data contains red wine with values from the range of 0 to 1, and there isn't much dependency of citric acid on residual sugar and chlorides respectively.<p><p style="text-align: justify;">
	The fourth row shows the behaviour of the residual sugar content with respect to other contents of the wine. The first plot, which is a scatter plot of residual sugar agianst fixed acidity, shows that most of the wine had fixed acidity and residual sugar both values ranging from 5 to about 15, with few occurences of the residual sugar greater than 10. No clear linear relationship exists between residual sugar and volatile acidity, but it can be observed that most of the red wine had volatile acidity values ranging from 0 to 1, with a higher percentage of this range(group) having fewer occurences of residual sugar values above 10. The scatter plot showing the graph of residual sugar against citric acid proves that most of the red wine had values ranging from near zero to about 0.8, with this range having a higher frequency of residual sugar values between 0 and 5. The bar chart shows a sharp rise, followed by a sharp decline in the number of red wine instances, indicating that most of the red wine instances have values in the range of 0 to 5. The last plot, which shows a scatter plot of chlorides against residual sugar shows no clear relationship.<p><p style="text-align: justify;">
	The last row consists of 4 scatter plots and a single histogram. It can be seen that most of the red wine instances have their chloride values existing between 0 and 0.2(ie. from the histogram).<p>



### Figure 3:
![Figure 3](C:\Users\ASARE\Desktop\11296641\Figure3.png)

<p style="text-align: justify;">Figure 1 shows a graph(histogram) containing information on the frequency of the fixed acidity levels of the various instances of red wine collected in the dataset. From the dataset, it can be observed that red wine instances with fixed acidity values near 7 (specifically 7.2) have a higher occurence. Starting from 0, the frequency of the fixed acidity increases proportionally with fixed acidity till the fixes acidity value of about 7, and then the frequency decreases to near zero from the highest point(to the fixed acidity mark of 16). It can be observed from here that most of the red wine instances have a value at or near 7.<p>


### Figure 4:
![Figure 4](C:\Users\ASARE\Desktop\11296641\Figure4.png)
<p style="text-align: justify;">
The last figure, shows summary of the behaviours of each parameter against every other parameter, by plotting a correlation heatmap. The squares with colors closer to red show that those 2 parameters are directly proportional to each other, whiles the squares with colors closer to blue imply an inverse proportionality. Squares with colors nearer to white have values closer to 0, and this implies a very weak dependency on those 2 parameters eg. the relationship between volatile acidity and residual sugar. The red squares which also contain values equal to 1, show parameters plotted against itself.<p>

## Conclusion:

To conclude, this analysis has yielded a multifaceted understanding of red wine characteristics, drawing upon a diverse range of parameters. By exploring the relationships between factors like fixed acidity distribution and quality ratings through compelling visualizations, we have significantly enhanced our comprehension of red wine's defining attributes. These valuable insights serve as a rich resource for enthusiasts, researchers, and industry professionals alike, fostering a deeper appreciation for this enduring beverage.