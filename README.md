# Your blog

This is the repository for your blog! Click *_config.yml* above to get started and fill in the details. Then click *index.md* and edit it to start creating your home page.  


here is additional content



<!DOCTYPE html>
<html>
<head>
  <script src="https://cdn.jsdelivr.net/npm/vega@5"></script>
  <script src="https://cdn.jsdelivr.net/npm/vega-lite@3"></script>
  <script src="https://cdn.jsdelivr.net/npm/vega-embed@4"></script>
</head>
<body>
  <div id="vis"></div>
  <script type="text/javascript">
    var spec = {
      "$schema": "https://vega.github.io/schema/vega-lite/v2.json",
      "config": {
        "view": {
          "height": 300,
          "width": 400
        }
      },
      "data": {
        "url": "https://vega.github.io/vega-datasets/data/cars.json"
      },
      "encoding": {
        "color": {
          "field": "Origin",
          "type": "nominal"
        },
        "x": {
          "field": "Horsepower",
          "type": "quantitative"
        },
        "y": {
          "field": "Miles_per_Gallon",
          "type": "quantitative"
        }
      },
      "mark": "point"
    };
    var opt = {"renderer": "canvas", "actions": false};
    vegaEmbed("#vis", spec, opt);
  </script>
</body>
</html>
