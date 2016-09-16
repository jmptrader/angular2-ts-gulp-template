The vendor directory is for third-party CSS like Bootstrap, jQueryUI, FancyCarouselSliderjQueryPowered, and so on. 
This is handy when using prepackaged components developed by other people (or for your own components that are maintained in another project). 
jQuery UI and a color picker are examples of CSS that you might want to place in the vendor directory. 
As a general rule We make it a point not to modify files in my vendor directory. 
If we need to make modifications we add those after the vendored files are included in my primary stylesheet. 
This should make it easy for me to update my third-party stylesheets to more current versions in the future.