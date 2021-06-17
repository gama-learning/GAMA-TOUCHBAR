# GAMA-TOUCHBAR
Creator: Srirama Bhamidipati

Date: 17 June 2021



![](relaxing-3943354.svg){:height="50%" width="50%"}









GAMA-TOUCHBAR is a BTT preset for GAMA. This preset helps GAMA users to quickly write code by adding GAML templates with the touch of a finger. The idea is to help beginners with GAML templates and advanced users tomodify it themselves or contribute  to this project. 



Please post issues to request for new features.



## Motivation 

- To remove fear in beginners to remember all the required GAML code
- To help intermediate users to speed up writing code.
- To push developers to think in the direction of "touch friendly" design of GAMA.





## Requirements

1. Apple laptops with a Touch Bar and running macOS 
2. BetterTouchTool (BTT) https://folivora.ai/ 
3. GAMA installed https://gama-platform.github.io/





## Installation 

1. Open BTT
2. Presets> Import Presets
3. Browse to the folder where you saved **GAMA-TOUCHBAR.bttpreset**, select and click OK



## Quick Walkthrough 



#### Mandatory

Mute and Esc button exist at all levels of the GAMA-TOUCHBAR, this is to help you mute your system volume in an urgent or unexpected situation without having to quit GAMA-TOUCHBAR; same for esc, if you wish to cancel any menu operations while using GAMA, esc acts as the default esc key on a keyboard. 



#### Root

At the top level (root level) you will see the bar as below. The left most blue set is for code navigation. 

- If you want to search for occurences of a variable in a model, you can search in forward (:fast_forward:  ) or backward (:rewind: ) direction. 

- The magnifying glass (:mag: )is used for looking for a variable in the model outline. 
- **aA** helps you refactor a variable in the entire model and 
- the anchor button (:anchor: ) looks for the declaration of a variable (object).

![root](root.png)



#### Quick Syntax

The quick syntax toolbar gives you access to all the basic templates you need to build a simple model. The orange buttons with two parallel lines || indicate that you have more options to explore, so touch them to see further options. You will find:

- reflex

- species/ grid 

- action

- loops

- experiment

- :chart_with_upwards_trend: series chart

- monitor

- parameter

  

![quick](quick.png)



#### Simulation 

This toolbar gives access to run your simulation. This has been deliberately made to mimic GAMA toolbar, therefore buttons are self-explanatory 

![simulation](simulation.png)



#### Templates

This bar gives you access to many GAML templates or code blocks that are difficult to remember. These templates are now available at the touch of a finger.

![templates](templates.png)



#### Templates> Experiments

This bar gives you access to the experiment templates

![experiments](experiments.png)



#### Templates> Charts 

This bar gives you access to the chart templates. This is under development. A series chart is however available in the quick syntax bar. 

![charts](charts.png)
