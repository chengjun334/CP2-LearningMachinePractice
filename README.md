# CP2-LearningMachinePractice

 - **Assignment**: Make an object counter.
   
   First, choose a few objects and train a new image classifier using Teachable Machine. In addition to recognizing the objects themselves, you'll want to include an "empty" class, when there isn't any object visible.
   
   Use the default "p5.js Web Editor" export (don't forget to copy your model ID over!) and modify the sketch to count and display how many times your sketch sees each object. (Get creative with your display here!)
   
   One complexity is that your code will be tempted to count every *frame* that an object is visible, but we don't want this -- you'll need some way to track when the classification switches back to "empty" and then another object. Consider using a variable that tracks whether you were *just looking at* empty.
   
 - **Challenge**: Instead of counting, just show a list of the 10 most recent classified objects.
 
