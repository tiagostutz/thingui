
<p align="center">
  <img height="300" src="http://res.cloudinary.com/stutzsolucoes/image/upload/c_scale,h_320/v1531080322/thingui-logo.png">
</p>

## Ok, what's the main idea?
The idea is to build, organize and compose the UI component as if they were IoT devices. For example, think of a stream feed page like the ones you see in Twitter, Facebook, Pinterest, etc as if it was an analogic panel with devices plugged into it. Each feed item would be a device containing a display with feed information, a speaker to play its sound - if may -, buttons to do actions like filter, sort, star, like and so on. 
In fact, the HTML components were inspired by real world analogic compoenents, like `button` and `select(or)`.

## Hum... why?
In IoT world you have some serious constraints when building devices and components, like: 
- extremely component specialization so you can produce components at large scale and use them combined to make lots of different devices
- energy efficiency
- low lattency and feedback
- deeply simple state management and store (on/off, ready/busy, single integer,...)
- formal interface specification and known inputs and outputs domains
- heavy component independency because the are manufactured at scale separatedly by different manufecturers
- event driven communication instead of imperative communication due to async nature
- ...
If you think about the constraints that nowdays applications faces, you will notice some of those characteristics, like: low lattency and feedback, usage of components from differentes manufacturers (aka OpenSource), async nature of the workflows, energy efficience (mobile data usage) and so on. So, the IoT world could teach us some lessons on how to achieve great results designing chaotic systems.

## Real world example please.

-----

### Credits
Logo made with <a href="https://www.designevo.com/en/" title="Free Online Logo Maker">DesignEvo</a>
