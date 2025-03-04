# An Optimistic Nihilist rstheme
A custom R Studio theme based on [Material Darker](https://github.com/lusignan/RStudio-Material-Theme) and [Chaos](https://github.com/rstudio/rstudio/blob/main/src/cpp/session/resources/themes/chaos.rstheme). 

I wanted a dark, yet colorful theme. I've changed most of the colors to match the default rainbow parentheses available RStudio. To enable rainbow parentheses go to Tools > Global Options > Code > Display > Use rainbow parentheses. A list of the hexidecimal color codes are available in the [reference_files](https://github.com/liz-muehlmann/rstheme_an_optimistic_nihilist/tree/main/reference_files) folder > [colors.css](https://github.com/liz-muehlmann/rstheme_an_optimistic_nihilist/blob/main/reference_files/colors.css) file. You can also change these to be any color you want. Paul Rubin's [blog](https://orinanobworld.blogspot.com/2021/01/rainbow-parentheses-in-rstudio.html) has more information.

I have heavily commented the theme for easy editing. I have made notes where I am unsure what the code changes. In these cases, I have left the lines in as they appear to be common throughout R themes. For example, the line: `.rstudio-themes-flat.ace_editor_theme .profvis-flamegraph` should change the color of the benchmarking panel, but it does not. 

**this theme is a work in progress. I am not finished updating it.**

# why optimistic nihilism?
An optimistic nihilist is someone who believes there is no objective meaning or purpose to the universe or human existence. Despite this, the optimistic nihilist believes that joy, happiness, and fulfillment are possible by creating a world that reflects their values. In the face of nothingness, choose joy.

# to install
1. download the `an_optimistic_nihilist.rstheme` file.
2. tools > global options > appearance > add 
3. find and select the `.rstheme` file from step 1
4. click ok

# to do
- [ ] finish updating comments and colors
- [ ] figure out the profvis-flamegraph line

