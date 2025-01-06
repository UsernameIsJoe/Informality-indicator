# Informality-indicator

## Intro
The project delves into the intricate urban landscape of Mumbai, spotlighting squatter spaces as informal urban entities that contribute significantly to the city's vibrancy and cultural identity. Unlike slums, these scattered spaces serve as bustling hubs of local commerce and labor, painting a vivid picture of Mumbai's dynamic essence. Employing image segmentation scripts trained in formal urban contexts, the script categorized building facades that were identified as indoor elements, such as doors and fabrics, as unconventional facades and further evaluated the score of its informality by the percentage of the indoor objects collected. Leveraging certain results, the project maps out the density and locations of these informal settlements in southern Mumbai, aiming to capture their rich cultural fabric and historical significance in shaping the city's identity.

## Setup

The script was previously developed inside Google Colab. Please follow the instructions within the file step by step, and all the necessary libraries and datasets will be installed along the way. It is also suggested to run the script on your Colab since the ML models might take some time to set up for the first time.

## What's Next

While challenging the model to identify elements that are not clearly defined, this pipeline helps designers reinterpret images. To push the concept forward, the next steps would focus on training the model with more keywords and more diverse images. Although this might compromise the precision of the segmentation, it would help the model identify more elements from the imagery.
