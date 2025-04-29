# Video Game Market Analysis
*This project was completed as part of the [CareerFoundry Data Analytics Program](https://careerfoundry.com/en/courses/become-a-data-analyst/).*

## Overview
A video game company’s board is preparing its 2017 marketing budget based on the assumption that regional sales trends and market shares have remained stable over time. This analysis challenges that assumption by examining how genre preferences, sales performance, and publisher dynamics have changed — and whether these patterns differ across regions.

## Tools
- **Excel** - Data Preparation | Visualisation | Analysis
- **KeyNote** - Presentation

## Process
- Data Description | Profiling | Exploration | Cleaning
- Descriptive Statistics | Trend Analysis
- Deriving Insights | Visualisation | Presentation

## Data
The original dataset was sourced from **VGChartz** that covers the period 1980 to 2020. A modified version was provided by **CareerFoundry** as part of their Data Analytics Course. 

- [**Video Game Sales**](https://coach-courses-us.s3.amazonaws.com/public/courses/intro-to-data/E4/vgsales_dirty.xlsx) - Number of units sold by title, release year, platform, genre, publisher, region.

***Note:** Sales figures prior to 2018 are based on extrapolated retail data and include estimates for digital sales. This introduces potential sampling and estimation biases, meaning figures may not fully represent actual market totals or digital performance.*

## Links
- [**Presentation**](https://github.com/davidgriesel/01-video-game-market-analysis/tree/main/deliverables/presentation.pdf)
- [**Presentation**](https://github.com/davidgriesel/01-video-game-market-analysis/blob/main/deliverables/presentation-with-notes.pdf) - Including presenters notes.

## Key Insights
### Insight 1: Apparent Market Contraction Reflects Estimation Bias During Digital Transition
<table>
<tr>
<td align="center" valign="top" width="100%">
    <img src="visualisations/sales-titles-over-time.png" ><br>
    <em>Sales and title output rose steadily until 2008, then declined sharply amid the rise of digital platforms, reflecting a structural market shift and estimation bias in the dataset.
</em>
</td>
</tr>
</table>
<br>

### Insight 2: Regional Market Dominance Shifted to Europe
<table>
<tr>
<td align="center" valign="top" width="100%">
    <img src="visualisations/shifts-regional-markets.png" ><br>
    <em>Europe gradually gained ground and overtook North America in 2016, marking a significant shift in regional market share, though likely influenced by the transition to digital distribution.</em>
</td>
</tr>
</table>
<br>

### Insight 3: Action Loses Global Preference but Gains Ground in Japan
<table width="100%">
<tr>
<td align="center" valign="top" width="50%">
    <img src="visualisations/shifts-total-america.png""><br>
</td>
<td align="center" valign="top" width="50%">
    <img src="visualisations/shifts-total-europe.png"><br>
</td>
</tr>
<tr>
<td align="center" valign="top" width="50%">
    <img src="visualisations/shifts-total-japan.png"><br>
</td>
<td align="center" valign="top" width="50%">
    <img src="visualisations/shifts-total-other.png"><br>
</td>
</tr>
<tr>
</table>

<table>
<tr>
<td align="center" valign="top" width="100%">
    <em>Shooter overtook Action in North America, while Shooter and Sports surpassed it in Europe and the Other region, reflecting evolving platform trends and player preferences. Japan diverged, with Role-Playing dominant until Action rose late in the period.</em>
</td>
</tr>
</table>
<br>

### Insight 4: Regional Genre Efficiency Shifted Over Time
<table width="100%">
<tr>
<td align="center" valign="top" width="50%">
    <img src="visualisations/shifts-avg-america.png""><br>
</td>
<td align="center" valign="top" width="50%">
    <img src="visualisations/shifts-avg-europe.png"><br>
</td>
</tr>
<tr>
<td align="center" valign="top" width="50%">
    <img src="visualisations/shifts-avg-japan.png"><br>
</td>
<td align="center" valign="top" width="50%">
    <img src="visualisations/shifts-avg-other.png"><br>
</td>
</tr>
<tr>
</table>

<table>
<tr>
<td align="center" valign="top" width="100%">
    <em>Genre efficiency shifted alongside sales trends, with Shooter overtaking Platform to become the strongest performer in all regions except Japan, where Role-Playing remained dominant. Action posted only moderate average returns despite high total sales volumes.</em>
</td>
</tr>
</table>
<br>

### Insight 5: The Competitive Landscape is Dominated by a Few Major Publishers
<table>
<tr>
<td align="center" valign="top" width="100%">
    <img src="visualisations/dominating-publishers.png" ><br>
    <em>Global video game sales are dominated by a few major publishers, with Nintendo leading at nearly 1.8 billion units, followed by EA and Activision with significantly lower totals. In contrast, the vast majority of publishers account for only a tiny fraction of total sales, underscoring the market’s extreme concentration.</em>
</td>
</tr>
</table>
<br>

### Insight 6: Publisher Dominance Evolved Globally and Diverged in Japan
<table width="100%">
<tr>
<td align="center" valign="top" width="50%">
    <img src="visualisations/shifts-publisher-america.png""><br>
</td>
<td align="center" valign="top" width="50%">
    <img src="visualisations/shifts-publisher-europe.png"><br>
</td>
</tr>
</table>

<table width="100%">
<tr>
<td align="center" valign="top" width="50%">
    <img src="visualisations/shifts-publisher-japan.png"><br>
</td>
<td align="center" valign="top" width="50%">
    <img src="visualisations/shifts-publisher-other.png"><br>
</td>
</tr>
<tr>
</table>

<table>
<tr>
<td align="center" valign="top" width="100%">
    <em>EA maintained dominance in Europe and Other, while Ubisoft surged late to top Activision in North America. Nintendo declined everywhere, and gave leadership to Namco Bandai and Square Enix in Japan</em>
</td>
</tr>
</table>
<br>

## Takeaways
### Successes
The project met its core objectives by revealing actionable insights into genre preferences, regional shifts, and publisher dynamics. It clarified executive questions and challenged assumptions about market consistency, while confirming the industry’s shift from physical to digital formats.

### Challenges
Managing scope was a key challenge. It was tempting to pursue additional lines of analysis, for example around per-title performance. Staying focused on the core objectives required discipline, prioritisation, and restraint. The experience reinforced the importance of addressing stakeholder questions first, before exploring adjacent insights.

### Way Forward
Future projects should begin with a more structured plan — outlining key questions, priorities, and intended deliverables — to maintain focus, prevent scope drift, and ensure that insights remain tightly aligned with project objectives.
