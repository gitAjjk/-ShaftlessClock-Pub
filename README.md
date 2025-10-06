# ShaftlessClock
Clockwork with no axis / shafts  
Started on [hackaday](https://hackaday.io/project/196036/details/), but further maintained here.

## Version Hollow 
This is a set of large inside gears with small centre gears to next stage.   
Each wheel is an hollow/inner gear; I used old vinyl LongPlayrecords (cheap and abundant available material) and this sets the max size I use.  
The small gears are rigid and concentric mounted on another LP, with decorative pockets, with a litle distance and flanges.  

<img src="https://github.com/gitAjjk/Klok/blob/main/img/ratiosHollow.svg" width="250">  ![Hollow](https://github.com/gitAjjk/Klok/blob/main/img/Hollow.png)  <img src="https://github.com/gitAjjk/Klok/blob/main/img/assyTDside.jpg" hight="6550">  <img src="https://github.com/gitAjjk/ShaftlessClockV1-Pub/blob/main/img/ratios.jpg" width="250">  

See ??TODO?? for templates.  

# Drive
## The outer-ringdrive couldn't be a motor because it has a shaft ;).  
To thrive the wheel each second, I expirimented with (ax-less):  
- A plane pendulum of about 30 cm (swing time: 1 second).  
- ["Conical pendulum"](https://en.wikipedia.org/wiki/Conical_pendulum)<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/5/53/Conical_pendulum.svg/375px-Conical_pendulum.svg.png" alt="Conical pendulum" width="100">   
- Electromagnetically driven mechanism (todo).  
- Wobble (investigating)

Any (better) idea or variant, please make an issue or contact me.  

## Easy cheat:  
- Cheap dc motor from China
- microcontroller driven motor

# Faces; templates for wheels
See [pdf for higher resolution ](https://github.com/gitAjjk/ShaftlessClockV1-Pub/blob/main/img/faces%20NL.pdf)  
<img src="https://github.com/gitAjjk/ShaftlessClockV1-Pub/blob/main/img/faces%20NL~.jpg" width="500">

# Construct
Use files in [repo](https://github.com/gitAjjk/ShaftlessClockV1-Pub/tree/main/techDraw) for lasercutting.   
- Make sure enough flanges and distancekeepers are produced.  
- Use flanges as template for drilling the three holes in the LP's.  
- Use distancekeepers to glue/screw the ring-segments to stirdy, solid, complete ring.  

e.g.:  
<img src="https://github.com/gitAjjk/ShaftlessClockV1-Pub/blob/main/techDraw/sm.jpg" width="500">

# 3D example of one stage:
<img src="https://github.com/gitAjjk/ShaftlessClockV1-Pub/blob/main/SingleStageExploded.png" width="300">  

Check this:  
- [3D .stl example](https://github.com/gitAjjk/ShaftlessClockV1-Pub/blob/main/SingleStage.stl)
- [3D exploded view](https://github.com/gitAjjk/ShaftlessClockV1-Pub/blob/main/SingleStage%20exploded.stl)

Shown here is one stage: 
- Wheel N-1 : plate + gear + flange; inbetween 2 x ±0,1 mm distance washer
- Wheel N   : Ring + 4 x distancekeepers + plate; inbetween ±0,5 mm distance washer. (Centre gear + flange of stage N are omitted)

External render on e.g. [3dviewer.net](https://3dviewer.net)

# Extra
This is version 1 of my shaftless clocks; v2 and 3 are more nifty, but not (yet) public available.
