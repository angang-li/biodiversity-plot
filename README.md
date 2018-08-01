# Belly Button Biodiversity

Build an interactive dashboard to explore the [Belly Button Biodiversity DataSet](http://robdunnlab.com/projects/belly-button-biodiversity/).

Check out the application [here](https://biodiversity-plot.herokuapp.com/)!

## Step 1 - Plotly.js

Use Plotly.js to build interactive charts for your dashboard.

* Create a PIE chart that uses data from your samples route (`/samples/<sample>`) to display the top 10 samples.
* Create a Bubble Chart that uses data from your samples route (`/samples/<sample>`) to display each sample.
* Adapt the Gauge Chart from <https://plot.ly/javascript/gauge-charts/> to plot the Weekly Washing Frequency obtained from the route `/wfreq/<sample>`
* Display the sample metadata from the route `/metadata/<sample>`
* Update all of the plots any time that a new sample is selected.

## Step 2 - Heroku

Deploy the Flask app to Heroku.

- - -

### Copyright

Data Boot Camp © 2018. All Rights Reserved.
