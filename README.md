# d3_wip_map
Improving Tableau and Power BI multiple pie charts in interactive map for future adaptation to a free addon in Power BI.
This is still a work in progress.

## Power BI D3.js Limitations
Unfortunately the following limitations are valid for this visual:

* Available D3.js version is v3.5.17
* Maximum amount of datapoints is: 30,000
* Due to the way of the visual is rendered the main SVG element must be selected via the id, e.g. d3.select("#chart") and should not be created via code
* The JavaScript code should be ES5 code as that is the supported version by Power BI

## Obs.
* If you want to make adaptations to a Power BI D3.js custom visual right off the bat, please note that you can't change styles on css or any of the html properties, you can only change svg attributes
* You're welcome to contribute, the code is fully commented for beginners in front-end (like myself)

## Sources
* [D3.js v3 API Reference](https://github.com/d3/d3-3.x-api-reference/blob/master/API-Reference.md)
* [SVG Documentation](https://developer.mozilla.org/en-US/docs/Web/SVG) - to understand and change attributes of styles, etc
* [Power BI D3.js Visual Documentation](https://azurebi-docs.jppp.org/powerbi-visuals/d3js.html?tabs=docs%2Cdocs-open)
* [D3 Gallery](https://d3-graph-gallery.com/index.html) - it's in d3 v4, so to actually use it, it must be adapted
* [Observable](https://observablehq.com/@d3) - Some code must be adapted to work in v3

## Next Steps
[Add find behaviour in pie charts](https://observablehq.com/@d3)
