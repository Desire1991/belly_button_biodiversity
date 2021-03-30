# Belly Button Biodiversity


Overview:


For this project, I helped Roza to visualize the bacterial data for each volunteer. Specifically, her volunteers should be able to identify the top 10 bacterial species in their belly buttons. In order, if Improbable Beef identifies a species as a candidate to manufacture synthetic beef, Roza's volunteers will be able to identify whether that species is found in their navel.

To achieve that, I utilized Plotly.js, a JavaScript data visualization library, to create an interactive data dashboard for the web. Then, I deployed the project onto a GitHub public server so I can share the project with others.

![weboverview](https://user-images.githubusercontent.com/74233163/112948523-cb7ca000-90fd-11eb-9a0f-4692096e6257.png)


Horizontal Bar Chart

First thing, utilize JavaScript, Plotly, and D3.js, I created a horizontal bar chart to visualize the top 10 bacterial species (OTUs) when a person’s ID is selected from the dropdown menu on the webpage. The horizontal bar chart will display the sample_values as the values, the otu_ids as the labels, and the otu_labels as the hover text for the bars on the chart.

Bubble Chart

Secondly, using JavaScript, Plotly, and D3.js, I created a bubble chart that displays the otu_ids as the x-axis values, the sample_values as the y-axis values, the sample_values as the marker size, the otu_ids as the marker colors and the otu_labels as the hover-text values when an individual’s ID is selected from the dropdown menu webpage.

Gauge Chart

Thirdly, using JavaScript, Plotly, and D3.js, I created a gauge chart that displays the weekly washing frequency's value, and displays the value as a measure from 0-10 on the progress bar in the gauge chart when an individual ID is selected from the dropdown menu.

Customized Dashboard and Deployment

Lastly, I used HTML and Bootstrap to customize the webpage for your dashboard and deployed an interactive chart to GitHub Pages for others to reference. The completed dashboard can be referenced in GitHub Pages under the Environments section of my belly_button_biodiversity repository.


 


