class: center, middle

# Physical Computing 
## Traffic Lights
### with
## Crumble, CodeBug, or Arduino - 18:24 Thu 27 Aug

## David Roberts
### STEM Ambassador, Code Club Volunteer, Tinkerer
#### (Space, Page Down or Arrow keys to advance... )
---
# Session aims

## In a nutshell -

## There's more to Computing than Screens and Apps!

---
# Session aims

## This session is __NOT__:
- A lesson plan
- A programming lesson
- A Computer Science lecture
- The only or best way to do it

## This session aims to be:
- An example of 'decomposing' a problem
- A demonstration of cheap ( less than £30 ) hardware controlling physical systems with LEDs and switches
- A source of information and ideas
- Fun!
---

# Traffic Lights
## UK Traffic Lights, described in the Highway Code

## .red[RED], .amber[AMBER], .green[GREEN]

## Exercise 1 -
- How many discrete phases (settings) of the 3 lights are there in the Highway Code sequence?
- Describe and/or record them


---
# Traffic Lights
UK Traffic Lights are described in the [The Highway Code](https://www.gov.uk/government/publications/the-highway-code-light-signals-controlling-traffic "Highway Code link")

![UK Traffic Light Sequence](images/hctls.jpg "UK Traffic Lights")

---
# Traffic Lights
## Overall Sequence -
| Lamp\Phase  | Green | Amber | Red | Red/Amber | Green |
| :--:| :--:| :--:| :--:| :--:| :--:|
| .red[RED  ]| - | - |ON|ON| - |
| .amber[AMBER]| - |ON| - |ON| - |
| .green[GREEN]|ON| - | - | - | ON |

---
# Traffic Lights
## Exercise 2a -
- Start with the .green[GREEN] (traffic flowing) phase
- What 'steps' move from the GO phase to the STOP phase?

---

# Traffic Lights
## Exercise 2b -
- Start with the .red[RED] (traffic stopped) phase
- What 'steps' move from the STOP phase to the GO phase?

---

# Traffic Lights
## To change from .green[GO] to .red[STOP]: 
| Lamp\Phase  | Green | Amber | Red |
| :--:| :--:| :--:| :--:|
| .red[RED  ]| x | x |ON| 
| .amber[AMBER]| x |ON| OFF |
| .green[GREEN]| x | OFF | x |
## To change from .red[STOP] to .green[GO]: 
| Lamp\Phase  | Red | Red/Amber | Green |
| :--:| :--:| :--:| :--:| 
| .red[RED  ]| x | x |OFF| 
| .amber[AMBER]| x |ON| OFF|
| .green[GREEN]| x | x |ON|

[ x indicates No Change ]

---
# National Curriculum 
## Computing KS2

Pupils should be taught to:
* design, write and debug programs that accomplish specific goals, including controlling 
or simulating physical systems; solve problems by decomposing them into smaller 
parts

---
# National Curriculum 
## Computing KS2

We have an __Abstraction__ of a set of Traffic Lights - no need for a pole to mount them 2 metres up in the air. Not counting passing or approaching vehicles.

We have used __Decomposition__ to turn the sequence into a small number of steps.

Now we can __Simulate__ our Traffic Lights by designing, writing, and debugging programs

If we can turn __ONE__ light On and Off, we can probably manage three...

---
# Crumble

---
# Crumble
## One light

---
# Crumble
## Three lights

---
# Crumble
## Traffic Light sequence

---
# Crumble
## Sequence, switch controlled

---
# CodeBug

---

# Arduino

---
#Ardunio
## One light

---
# Acknowledgements/Credits

---
class: right, bottom

The End!

---

