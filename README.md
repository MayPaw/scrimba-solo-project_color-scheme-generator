# Scrimba Solo Project: Color Scheme Generator
The repository contains simple color scheme generator project from Scrimba's "The Frontend Developer Career Path". <br> To see the app please visit: https://maypaw.github.io/scrimba-solo-project_color-scheme-generator/
### What's a "solo" project?
A "solo" project on Scrimba is a kind of task that students complete by themselves, with basic reqirements <br> and Figma design provided. The teachers always encourage students to make improvements to the project.

### Requirements
* choose "seed color" with an <input type:"color">
* choose color scheme mode in a select box
* clicking button makes request to The Color API to get a color scheme
* display the scheme colors and hex values on the page
* stretch goal: click hex values to copy to clipboard

### Functionality
My Color Scheme Generator meets all basic requirements of the project. I also added some improvements:
* color in rgb format in addition to the hex code (since some browsers use a input type="color" picker <br> with color code in rgb format only)
* loading spinner displayed when data is being fetched from The Color API
* error message displayed for the user if fetch promise is rejected for some reason

### More ways to improve
Even though I improved basic project a bit, there is more that can be done. Here are some ideas for further development:
* allow user to choose quantity of displayed colors
* generate an additional shade of colors already displayed on the page
* add opacity slider for each displayed color (and display it in rgba code)
