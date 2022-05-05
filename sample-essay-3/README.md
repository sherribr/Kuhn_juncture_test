<a href="https://juncture-digital.org"><img src="https://juncture-digital.org/images/ve-button.png"></a>

<param ve-config 
       title="Gustave Doré's Gothic Art"
       author="Sherri Brown" 
       banner="https://upload.wikimedia.org/wikipedia/commons/c/ca/Gustave_Dor%C3%A9_-_Loch_Lomond_-_88-1913_-_Saint_Louis_Art_Museum.jpg" 
       layout="vertical">

<!-- Entities discussed throughout the essay are typically defined before the essay text and
     are thus available in all text.  Entity identifiers (QIDs) can be found in either
     Wikipedia or Wikidata (https://www.wikidata.org)> -->
<param title="Gustave Doré" eid="Q6682" alias="engraver">
<param title="Strasbourg" eid="Q6602">
<param title="Romanticism" eid="Q37068">
<param title="Lord Byron" eid="Q5679" alias="Byron">


# Doré's Illustrations 

Here I'm going to put some basic information about Doré and my essay. I can add a [University at Buffalo Gustave Doré illustrations site](https://digital.lib.buffalo.edu/collection/LIB-SC001/) for more examples. 
<param ve-image 
       label="Gustave Doré" 
       description="photograph by Félix Nadar" 
       license="PD" 
       url="https://upload.wikimedia.org/wikipedia/commons/7/7e/F%C3%A9lix_Nadar_1820-1910_portraits_Gustave_Dor%C3%A9.jpg">

## *The Rime of the Ancient Mariner*

Doré created illustrations for several Victorian editions of Samuel Taylor Coleridge's *The Rime of the Ancient Mariner*. [^1]
<param ve-image 
	label="The Mariner up on the mast in a storm"
	description="Illustration for *The Rime of the Ancient Mariner*" 
	license="PD" 	
        url="https://upload.wikimedia.org/wikipedia/commons/8/80/Gustave_Dore_Ancient_Mariner_Illustration.jpg">
	
## *The Raven*
Here I put some information about Dore's edition of Edgar Allan Poe's The Raven. And now I want to show a picture of the cover. 
<param ve-image 
	label="Cover of *The Raven*”
	description="Dore’s cover illustration for Edgar Allan Poe’s *The Raven*" 
	license="PD" 	
	rotate="90"
	url="Dore_Raven.jpg">


## Map of Birthplace 

Gustave Doré was born in the city of Strasbourg in eastern France, blah blah . . .
<param ve-map center="Q6602" zoom="11">
				      
## Map of Harrison-Small Special Collections
				      
Now I want to show you how to map something that does not have a Wikidata entry. You can do this using latitude and longitude coordinates in decimal. 
<param ve-map center="38.0360825,-78.5080211" zoom="11" show-labels marker-type="circle" radius="8">
  				      			   

## Multiple viewers

Multiple viewers may be defined for a single paragraph of text.  The first viewer defined is displayed as the default viewer.  
Others are selectable using icons displayed in the top right margin of the paragraph.
<param ve-image 
       manifest="https://iiif.juncture-digital.org/manifest/6dd738aed85597cac540ad31dd5818e86ef7f2918c7b43a9eb3123d5538e6e4c">
<param ve-map center="Q36600" zoom="11">

## Curtain Object 				       
Multiple viewers may be defined for a single paragraph of text. The first viewer defined is displayed as the default viewer.			       
<param ve-compare curtain url="https://stor.artstor.org/stor/f5acfe60-3c2c-4d9e-979f-2ec2896ebb2d" label="St Augustine's College, Canterbury (2021)">
<param ve-compare url="https://stor.artstor.org/stor/deb8a6fd-bc51-42fb-8ac2-28b556c482ab" label="St Augustine's College, Canterbury (1905 or earlier)">			       

# References

[^1]: [Wikipedia: The Rime of the Ancient Mariner](https://en.wikipedia.org/wiki/The_Rime_of_the_Ancient_Mariner)
