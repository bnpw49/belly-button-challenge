# belly-button-challenge

## Instructions
Complete the following steps:

1. Use the D3 library to read in samples.json from the URL https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.1/14-Interactive-Web-Visualizations/02-Homework/samples.json.

2. Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.

    * Use sample_values as the values for the bar chart.

    * Use otu_ids as the labels for the bar chart.

    * Use otu_labels as the hovertext for the chart.

    <p align="center"> 

    ![alt text](https://lh3.googleusercontent.com/zIaS79CqfAaJJwYKEKUjTOOvfqns6R7tX1n-lUMfd6ReSUJtkEVru53osNnsw006HyDnn7q4Fk-ZnQGETRtUpRpKjClOZvKs75v_KRjP6w)

3. Create a bubble chart that displays each sample.

    * Use otu_ids for the x values.

    * Use sample_values for the y values.

    * Use sample_values for the marker size.

    * Use otu_ids for the marker colors.

    * Use otu_labels for the text values.

      ![alt text](https://lh3.googleusercontent.com/tcjOghAgOSlgREXbfOJi3ZTJmDo2tpWwmpOs9aVYuBe5b8zrpMOhGOMs-U_LYzspaJZ7aUom3dxHNqD7_s5ksYFvHi-HtXmhleyIoKquow)

4. Display the sample metadata, i.e., an individual's demographic information.

5. Display each key-value pair from the metadata JSON object somewhere on the page.

    
  <img src="https://static.bc-edx.com/data/dl-1-2/m14/lms/img/hw03.jpg" alt="alt text">

    
6. Update all the plots when a new sample is selected. Additionally, you are welcome to create any layout that you would like for your dashboard. An example dashboard is shown as follows:

 
  ![alt text](https://lh3.googleusercontent.com/VpbEK3FoaTteZ2cmYGH9LxMmRJY4ktsoBR2ipaV0Ld6nmN5bBRhOyp5CKsh_-1rI94uIESrf2gtUcXMx4pe_G8Szp1KPSvbNGZ_JeokSg)


## *Bonus* 
The following task is advanced and therefore optional.

Adapt the Gauge Chart from https://plot.ly/javascript/gauge-charts/Links to an external site. to plot the weekly washing frequency of the individual.

You will need to modify the example gauge code to account for values ranging from 0 through 9.

Update the chart whenever a new sample is selected.

![alt text](https://lh3.googleusercontent.com/Dm9DHp8LOjyqewSOh0XF_faRE6fyPLwkvKBa8EQWEx0ZwOK3tZkxkKpoK3UNiofWN5-iozU8SqWy_aDl7CHTLEYm5Ql3ZXoJhIqOl75mNw)
