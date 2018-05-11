Development of functions to interrogate/filter the output of the lstm model so we can do things like:
- Do basic things like confusion matrices on binary classifications
- Examine broader, multi-classifier aggregate confusion matrices
Then use the things we see there to:
- Look up all behaviors having the same label or the same predicted classes
- Look up the behaviors that have specific combinations of label sets, to examine why '0000' may keep being predicted as '0011'
- Set up these filters for further analysis
The next step would be to develop functions to:
- Get the exact behaviors that are misclassified a certain way, for pattern examination
