  storyboard: true
    social: menu
    source: embed
---

```{r setup, include=FALSE}
library(flexdashboard)
```
https://people.highline.edu/mgirvin/excelisfun.htm
### The Final Project will represent an accumulation of what you have learned during this semester. This research project uses all the tools, skills, and knowledge applied in your statistics class.

```{r}
library(leaflet)
leaflet() %>%
  addTiles() %>%
  addMarkers(lng=-93.0913, lat=44.9537, popup="Saint Paul College")
```

***

https://rstudio.github.io/leaflet/

- Interactive panning/zooming

- Compose maps using arbitrary combinations of map tiles, markers, polygons, lines, popups, and GeoJSON.

- Create maps right from the R console or RStudio

- Embed maps in knitr/R Markdown documents and Shiny apps

- Easily render Spatial objects from the sp package, or data frames with latitude/longitude columns

- Use map bounds and mouse events to drive Shiny logic


###  You will analyze the data and draw a conclusion or prediction based on statistical significance testing to support your proposed hypotheses.

***

https://github.com/rstudio/d3heatmap/

- Highlight rows/columns by clicking axis labels

- Click and drag over colormap to zoom in (click on colormap to zoom out)

- Optional clustering and dendrograms, courtesy of base::heatmap


### Motivation: State the motivation and research question of your project? The must be an unambiguous question that can be answered with data analysis and a statistical regression model.


```{r}
library(dygraphs)
dygraph(nhtemp, main = "New Haven Temperatures") %>% 
  dyRangeSelector(dateWindow = c("1920-01-01", "1960-01-01"))
```

***

https://rstudio.github.io/dygraphs/

- Automatically plots xts time series objects (or any object convertible to xts).

- Highly configurable axis and series display (including optional second Y-axis).

- Rich interactive features including zoom/pan and series/point highlighting.

- Display upper/lower bars (e.g. prediction intervals) around series.
- Various graph overlays including shaded regions, event lines, and point annotations.


### Be sure to state the null and alternative hypotheses and the alternative hypothesis. Do the hypothesis testing to find the P-value and interpret it. Make decission based on test value.

```{r}
library(plotly)
p <- ggplot(data = diamonds, aes(x = cut, fill = clarity)) +
            geom_bar(position = "dodge")
ggplotly(p)
```

***

https://plot.ly/ggplot2/

If you use ggplot2, `ggplotly()` converts your plots to an interactive, web-based version! It also provides sensible tooltips, which assists decoding of values encoded as visual properties in the plot.

plotly supports some chart types that ggplot2 doesn't (such as 3D surface, point, and line plots). You can create these (or any other plotly) charts using `plot_ly()`.


### For multiple regression and logistic regression, list models of regression, compare them, and indicate why you chose the models that best fit and give your rationales on why you selected them.

```{r}
library(metricsgraphics)
mjs_plot(mtcars, x=wt, y=mpg) %>%
  mjs_point(color_accessor=carb, size_accessor=carb) %>%
  mjs_labs(x="Weight of Car", y="Miles per Gallon")
```

***

https://hrbrmstr.github.io/metricsgraphics/

Building metricsgraphics charts follows the “piping” idiom made popular through the magrittr, ggvis and dplyr packages. This makes it possible to avoid one giant function with a ton of parameters and facilitates breaking out the chart building into logical steps. 

While MetricsGraphics.js charts may not have the flexibility of ggplot2, you can build functional, interactive [multi-]line, scatterplot, bar charts & histograms and + even link charts together.
