# Self-Driving Car
<!--- Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails! --->

Hello, I'm Omid and for my project this year I decided to build a self-driving car. I started out with a basic, two wheel chasis. With this design, I used Arduino to manipulate the car and benchmarked it in several races. After evaluating the car, I made some tweaks to help with performance in certain areas that were lacking before.

<!---      --->


<!---You should comment out all portions of your portfolio that you have not completed yet, as well as any instructions:--->
<!--- This is an HTML comment in Markdown -->
<!--- Anything between these symbols will not render on the published site -->

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Omid H | Dougherty Valley High School | Electrical Engineering | Incoming Sophomore

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)
  
# Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE



# Second Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone

## Summary

# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/syKjGWBMcLM?si=NhIhl2jI2TpljYSL" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

<!---For your first milestone, describe what your project is and how you plan to build it. You can include:
- An explanation about the different components of your project and how they will all integrate together
- Technical progress you've made so far
- Challenges you're facing and solving in your future milestones
- What your plan is to complete your project--->

## Summary
In my first milestone, I assembled the basic design for the self-driving car. The car is powered by a single 9V battery, which is connected to the Arduino R3 board by a 9V battery cable. The R3 board provides 5V of power to the mini-breadboard through a red wire and ground is connected by a black wire to the same mini-breadboard. The two yellow TT motors are connected by two wires each to the L9110 module. The module acts as a bridge between the TT motors and the R3 board, communicating the board's commands to the motors effectively. On the other side of the L9110 module, there are six wires in groups of two that connect back to the aforementioned mini-breadboard. Those outgoing wires from the R3 board that I mentioned before (5V and GND) connect to these and complete the link. The orientation of the six wires on the mini-breadboard from the module dictate which way the car will go. To the left and right of the mini-breadboard, there are two IR (Infrared) Object Avoidance Sensors. These sensors use Infrared waves to help avoid objects and prevent crashes. Located on the mini-breadboard, across the center ravine from the previous wires, there is an ultrasonic sensor that can track distance and can help to prevent crashes. Directly below the mini-breadboard, there is a line-tracking module. This module helps to keep the car straight when following a line. That is the detailed breakdown of the basic design for my self-driving car after completing my first milestone. 

# Schematics 
<!---Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser.--->


![Headstone Image](circuit_image.png)


# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```

# Bill of Materials
<!---Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs.--->

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| SunFounder Ultimate Starter Kit | Building the base car | $59.99 | <a href="https://shorturl.at/1DRoX"> Link </a> |
| Amazon 8-pack of 9V batteries | Power/battery | $12.69 | <a href="https://shorturl.at/HBrm5"> Link </a> |
| Digital Multimeter | Checking the voltage of batteries | $9.98 | <a href="https://shorturl.at/0CSOv"> Link </a> |
| Anker USB C to A adapter | Connecting the Arduino to my Macbook Air | $9.18 | <a href="https://shorturl.at/1uAjG"> Link </a> |
| IR Infrared Obstacle Avoidance Sensor | Rear sensors for self-driving car | $9.99 | <a href="https://shorturl.at/mRN3r"> Link </a> |

# Resources
<!---One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/) 

To watch the BSE tutorial on how to create a portfolio, click here. --->
