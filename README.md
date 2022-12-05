# Belly-Button-Challenge
The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.
 
 Step 1 : plotly 

1 Use the D3 library to read in samples.json.
   
2 Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

a:Use sample_values as the values for the bar chart.

b:Use otu_ids as the labels for the bar chart.

c:Use otu_labels as the hovertext for the chart.
 
 ![image](https://user-images.githubusercontent.com/111711194/205523640-307f8832-5854-4c1d-9ad3-80ef11504435.png)




3 Create a bubble chart that displays each sample.

 a: Use otu_ids for the x values.

 b: Use sample_values for the y values.

 c: Use sample_values for the marker size.

 d: Use otu_ids for the marker colors.

 e: Use otu_labels for the text values.
 
 ![image](https://user-images.githubusercontent.com/111711194/205523720-0c2c89b1-a033-454d-9635-df8f7a8e1fbd.png)

4 Display the sample metadata, i.e., an individual's demographic information.

5 Display each key-value pair from the metadata JSON object somewhere on the page.

![image](https://user-images.githubusercontent.com/111711194/205523798-c4b9314e-c866-404a-a0fe-cff1b45c04e5.png)

6 Update all of the plots any time that a new sample is selected.

![image](https://user-images.githubusercontent.com/111711194/205523962-0b01e709-af78-45be-8e34-b073ae38d139.png)

7 Deploy your app to a free static page hosting service, such as GitHub Pages. Submit the links to your deployment and your GitHub repo. Ensure that your repository has regular commits

8 Adapt the Gauge Chart from https://plot.ly/javascript/gauge-charts/ Links to an external site.to plot the weekly washing frequency of the individual.

 ![image](https://user-images.githubusercontent.com/111711194/205524411-f0c4bc36-5644-4712-a87e-e636ce8bfb24.png)

References

Hulcr, J. et al. (2012) A Jungle in There: Bacteria in Belly Buttons are Highly Diverse, but Predictable. Retrieved from: http://robdunnlab.com/projects/belly-button-biodiversity/results-and-data/

