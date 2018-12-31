# Power BI Custom Visuals
**Developed by**: Nate Muth ([@analyticsNate](https://twitter.com/analyticsnate))<br>
 <br>
The inspiration for this project comes from this post on Tableau Public: [Link](https://public.tableau.com/en-us/s/gallery/20-ways-visualize-kpis?utm_source=Hootsuite&utm_medium=Social&utm_campaign=TableauSocial)
 <br>
#### 1. BAN KPI Multi Card
Many organizations need to see current period metrics compared to a previous period, whether that's yesterday, last month, or last year. The BAN KPI Multi Card was developed to give report developers more options for displaying KPI Metrics compared to a previous period.

The two inputs for the BAN KPI Multi Card are simple measures, a current metric value and a previous metric value, giving the report developer a lot of flexibility to define these values using DAX calculations.

The difference between the input values drive the colors of design elements included in the visual. The colors of the metric value, big triangle, small triangle, and color box are all dynamic based on whether the current metric value is greater than the previous metric value. These colors can be changed in the formatting pane - along with many other useful formatting options. Download pbiviz file: [Link](https://github.com/analyticsnate/power-bi-custom-visuals/blob/master/packagedVisuals/BANKPIMultiCard.pbiviz) <br>
