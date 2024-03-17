# Sorting-Visualizer-using-ReactJs
Sorting-Visualizer : Try at: https://crazydjp.github.io/Sorting-Visualizer/
We can comprehend algorithms considerably better thanks to the idea of visualising them.

We're using ReactJS to build this project. A few traditional sorting algorithms, including Bubble Sort, Selection Sort, and Insertion Sort, are visualised in it.

Use this link to experiment: crazydjp.github.io/Sorting-Visualizer

(NOTE: For a seamless transition effect, use hardware acceleration in Chrome.)

Components
There are four primary parts to it.

Header: "Sorting Visualizer" is all that is animated in this component. Header

Buttons Bar: This part has a few buttons that you may press to begin visualising algorithms. Buttons Bar

Array Bar: This part is where we use 3D Vertical Bars to visualise the process. Array Bar

Range Slider: Real-time adjustments to the animation speed and array size may be made with this component's range sliders. Range Adjuster

How do animations operate?
We put certain array indices and boolean values into the animations array while the array is being sorted. The boolean values doSwap and isFinal indicate whether the element is being compared or whether it is in its final location. These indices correspond to the comparing element and the final positioned element. The animations array is now provided to a different function, which modifies the colour and size of the bar representing each index in the animations array. The setTimeout() method is being used to implement these modifications, allowing them to be delayed and visible.
