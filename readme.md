# US Heart and Stroke Atlas Visualization
###Author: Om Gaikwad

## Motivation
The motivation behind this application is to provide a user-friendly and interactive tool for exploring factors that impact the health of counties in the USA. By visualizing various attributes such as economics, environment, behavioral factors, demographics, healthcare, and health outcomes, users can gain insights into the relationships between these factors and understand their spatial distribution across the country.

## Data
The data used in this project is sourced from the US Heart and Stroke Atlas. The dataset contains information on various attributes related to county health, including economic indicators, environmental factors, behavioral characteristics, demographics, healthcare resources, and health outcomes. [Download Dataset](national_health_data.csv)

## Visualization Components
1. **Attribute Selection**: Users can select two attributes from dropdown menus to compare their distributions and correlation.
2. **Distribution Comparison**: Visualizes the distribution of selected attributes using histograms.
3. **Correlation Analysis**: Displays a scatterplot to examine the correlation between the selected attributes.
4. **Spatial Distribution**: Shows the spatial distribution of attributes across the US using choropleth maps.

### Interaction:
- Users can select attributes from dropdown menus to update visualizations.
- Brushing functionality enables users to select a set of counties in distribution visualizations, scatterplot, and maps. Selected counties are filtered in all visualizations.

## Discoveries
- Through the application, users can discover correlations between different health-related attributes.
- Spatial distribution visualizations highlight geographical patterns and disparities in health outcomes and risk factors across the US.

## Process
- **Libraries Used**: D3.js for data visualization, HTML, CSS for layout and styling.
- **Code Structure**: The code is structured into separate files for HTML, CSS, and JavaScript. Data processing and visualization logic are encapsulated in JavaScript functions.
- **Access and Run**: The code is available on [GitHub](https://github.com/omgaikwad99/Health-in-USA). To run the application, simply clone the repository and open the HTML file in a web browser by clicking on the 'Go Live' option.
## Future Works
- Incorporate additional interactive features such as tooltips for detailed information on data points.
- Enhance the brushing functionality to allow for more advanced selection and filtering options.
- Improve the layout and design for better usability and aesthetics.

## Challenges
- One of the main challenges was implementing the brushing functionality across different visualizations and ensuring consistent updating of views.
- Integrating color schemes effectively to highlight data while maintaining visual clarity posed another challenge.
- Time constraints limited the scope of the project, but valuable lessons were learned in managing complex interactions and data visualization techniques.

## Demo Video
A 2-3 minute demo video showcasing the application in action has been recorded. The video provides an overview of the project components, including attribute selection, distribution comparison, correlation analysis, and spatial distribution visualization. It explains how users can interact with the application to explore different health-related attributes and discover insights into county-level health factors across the USA.

To view the demo video, please download the attached video file:
- [Demo Video](link-to-attached-video)

Note: If you cannot access the demo video, please feel free to [contact me via email](mailto:gaikwaot@mail.uc.edu) at gaikwaot@mail.uc.edu.
