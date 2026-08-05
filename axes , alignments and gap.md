---
created: 2026-08-06
topic: "[[The Odin Project]]"
source:
tags:
  - learning
category: "[[Study notes]]"
related-notes:
  - "[[CSS]]"
  - "[[HTML]]"
  - "[[The Odin Project]]"
---
## axis
axis is the direction in which an element is oriented towards, 
horizontally(row) and vertically(column).
the main axis is where the element is currently oriented towards and the cross axis is the other one.

in [[Flexbox]] , changing the axis will affect the elements' base size when growing or shinking (flex-basis) . If the elements main axis is horizontal(row) , flex-basis : auto will think an elements base size is its width but if its main axis is vertical(column) , flex-basis:auto will look at its height.


## alignment


<iframe sandbox="allow-downloads allow-forms allow-modals allow-pointer-lock allow-popups-to-escape-sandbox allow-popups allow-presentation allow-same-origin allow-scripts allow-top-navigation-by-user-activation" allow="accelerometer; bluetooth; camera; clipboard-read; clipboard-write; display-capture; encrypted-media; geolocation; gyroscope; language-detector; language-model; local-network-access; microphone; midi; rewriter; serial; summarizer; translator; web-share; writer; xr-spatial-tracking" allowpaymentrequest="true" allowfullscreen="true" allowtransparency="true" class="cp_embed_iframe " frameborder="0" height="400" width="100%" name="cp_embed_1" scrolling="no" src="https://codepen.io/TheOdinProjectExamples/embed/MWoyBzR?height=400&amp;default-tab=html%2Cresult&amp;slug-hash=MWoyBzR&amp;editable=true&amp;user=TheOdinProjectExamples&amp;name=cp_embed_1" style="width: 100%; overflow:hidden; display:block;" title="CodePen Embed" loading="lazy" id="cp_embed_MWoyBzR"></iframe>
"justify-content" aligns the content of a container along its main axis while "align-items" aligns the contents in the cross axis. this mean if the "flex-direction" was "column" , justify-content would work in horizontally while the opposite would be for "align-items"
there are many values I can put here like "space-between" , "space around" ,"center"


	/* justify-content values */
	
	flex-start;    /* Start */
	flex-end;      /* End */
	center;        /* Center */
	space-between; /* Equal space between items */
	space-around;  /* Equal space around items */
	space-evenly;  /* Equal space everywhere */
	start;         /* Logical start */
	end;           /* Logical end */
	stretch;       /* Stretch (Grid only) */



## Gap

gap is a property that will give a gap(duh) of space in between the elements 
ex:

<iframe sandbox="allow-downloads allow-forms allow-modals allow-pointer-lock allow-popups-to-escape-sandbox allow-popups allow-presentation allow-same-origin allow-scripts allow-top-navigation-by-user-activation" allow="accelerometer; bluetooth; camera; clipboard-read; clipboard-write; display-capture; encrypted-media; geolocation; gyroscope; language-detector; language-model; local-network-access; microphone; midi; rewriter; serial; summarizer; translator; web-share; writer; xr-spatial-tracking" allowpaymentrequest="true" allowfullscreen="true" allowtransparency="true" class="cp_embed_iframe " frameborder="0" height="300" width="100%" name="cp_embed_2" scrolling="no" src="https://codepen.io/TheOdinProjectExamples/embed/qBjZyea?height=300&amp;default-tab=html%2Cresult&amp;slug-hash=qBjZyea&amp;editable=true&amp;user=TheOdinProjectExamples&amp;name=cp_embed_2" style="width: 100%; overflow:hidden; display:block;" title="CodePen Embed" loading="lazy" id="cp_embed_qBjZyea"></iframe>