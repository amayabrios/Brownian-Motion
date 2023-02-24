# Brownian Motion

## Background
Named after botanist Robert Brown who was the first to observe this odd behavior, Brownian Motion describes how particles move when suspended in a medium. In 1827, Brown had observed pollen seeds moving at seemingly random patterns when suspended in water that was otherwise stationary and undisturbed. About 80 years later, Einstein reasoned that it must be the "atoms" (this was before everyone agreed atoms are real) in the water pushing the seeds around. The particles of water although observed having moved macroscopic objects around, can also be observed displacing microscopic particles around when we zoom in. That brings us to this lab...
###### credits: [APS, "This Month in Physics History"](https://www.aps.org/publications/apsnews/200502/history.cfm)

## The Lab
Truthfully, I can't recall what particles were suspended in the water, but the details of that aren't actually that important. Let's instead be general about it. Let's say we have particles suspended in water. We place a droplet of that water onto a glass slide, place a plastic cover over it, and slide it under a microscrope. Now let's say we can record what we see under the microscope. We watch and wait as the microscope records these suspended particles *wooshing* around in the water. We take that raw video footage (~10 minutes worth) of this water sample and process it using a collection of nifty Python libraries. What we will observe of the individual particles? How about their collective behavior?

## Walk Through of the Jupyter Notebook
1. Import the video and convert it to a grey color scale for contrast and accessibility purposes. 
2. Extract the position and other features of the sample from each video frame and store in dataframe. 
3. Visualize their paths to see how they have been displaced by the water particles.
4. Export the data of the net displacements of the particles as a new dataset.
