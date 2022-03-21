<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="My Site About Cats"
       author="Sherri Brown"
       banner="PandD2.jpg" 
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->

<param title="house cat" eid="Q146" aliases="domestic cat">
<param title="Felidae" eid="Q25265">
<param title="Gotthelf Fischer von Waldheim" eid="Q57802" aliases="von Waldheim">
<param title="name-used-in-essay" eid="digital-identifier-number" aliases="other-names-used-in-essay">

# So Many Cats 
This is a visual essay about cats in general as well as information about my own cats specifically. Additional [Documentation](https://github.com/JSTOR-Labs/juncture/wiki) and [examples](https://jstor-labs.github.io/juncture-examples) are available for reference.
<param ve-graphic label "Black cat" description="a close-up picture of a black cat" license="public domain" url="https://upload.wikimedia.org/wikipedia/commons/6/6d/Closeup_of_a_black_cat.jpg">

# Cats in art

## Impressionists 

_Julie Manet_ (Also known as _Child with Cat_) is an oil painting by French painter and sculptor Auguste Renoir, 
dated 1887. It is currently on display at the Musée d'Orsay in Paris. [^1] And here is some more information about cats that I want to cite. [^2]
<param ve-image 
       label="Julie Manet" 
       description="painting by Auguste Renoir" 
       license="public domain" 
       url="https://upload.wikimedia.org/wikipedia/commons/d/d2/Auguste_Renoir_-_Julie_Manet_-_Google_Art_Project.jpg">

## Map

Now I want to show you an example of how to put a map in your essay. Initially, I am going to share the location of the Musee d'Orsay in France.
<param ve-entity="Q23402">
<param ve-map center="Q23402" zoom="11" prefer-geojson>

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q36600" zoom="11">

# References

[^1]: [Musée d'Orsay](https://www.musee-orsay.fr/fr/oeuvres/julie-manet-100382)
[^2]: [Wikipedia: Cat](https://en.wikipedia.org/wiki/Cat)
