---
title: "make"
---

Use these instructions to make essential components of a darkroom. I address darkening, ventilation, and plumbing issues for both regular and remote locations. Please send improvements and new designs (see "open source" section in [introduction](/introduction/). 

#### metric

An American designer abroad and in recovery from the Imperial measurement system, I am giving all measurements in metric. Get a handle on this brain-descrambling system of measurement in 10 seconds using my favorite _near_-equivalents:

- 25mm = 1 inch
- 10cm = 4 inches
- 4 liters = 1 gallon

Find a few more at the end of the chapter. Again, these are rough conversions, good for understanding what I'm talking about and working with small quantities.

#### ventilation

The tricky part of making a darkroom is not darkening but ventilating it. After all, now the windows and doors are sealed! Fresh air is always important. We breathe twice as much air per day by mass as the food we eat. If you don't usually pay attention to air quality, you will in a darkroom, with little more to do all day than breathe. Poor air quality nullifies the benefits of darkness. Go out of your way for fresh air.

The tricky parts of ventilating it are doing it quietly, comfortably, and economically. If you already have mechanical ventilation in your house, with both supply and return vents in your darkroom, then thank your lucky stars. Just turn the manual fan switch on so it is on all the time. Likewise, if your darkroom has a supply vent and is attached to a bathroom with a quiet exhaust fan, your ventilation is handled. Check out the heat recovery section.

However, most dwellings are ventilated otherwise. Supply vents are in bedrooms and living rooms, exhaust vents in kitchens and disconnected bathrooms. This means air exits bedrooms around the door, usually at the bottom. So you will need at least an underdoor lightproof vent, described below.

If your darkroom has passive or no ventilation, then it calls for ways the air can travel in and out of the room. This entails vents, maybe ducting, and a fan.

##### vent

Where possible, put the air supply vent near the head of the bed and opposite the entry, toilet, and air return (exhaust) vent. Sometimes rooms have lightproof and sound-dampened holes built into them in unexpected places:

- unused holes for pipes, wires, chimneys, and ventilation. 
- behind a cupboard or inside a closet
- a panel covering something up that could be temporarily replaced with a same-size panel with a hole in it, like a trapdoor. 

I once found a cosmetically damaged door in a dumpster exactly the same size as my darkroom's door. So I stored the good door and cut holes in the damaged door for ventilation. 

Another darkroom had no door, ventilation, or suitable holes. So I built a frame inside the doorway with a narrow door one one side and a panel with holes on the other. _Note to renters:_ I attached the frame to the doorway with metal straps screwed into old hinge holes. So it left no trace when we dismantled the darkroom. Similarly, we hung a silencer, 7m of ducting running through two walls, and installed window inserts without putting even a single new screw hole in that rented house. Imagination conquers all obstacles (and imagination renews itself in darkness).

Sewage pipes are ventilated upward. Once, friends and I replaced a flush toilet with a composting toilet. The exposed toilet drain pipe, being oversize and in a single-story house, wasn't subject to backflow. So it proved a perfect exhaust duct for a case fan. 
 
<!-- {pagebreak} -->

###### drawings

**elevation**  
![vent 3d drawing](/img/plans/vent.jpg)  
&nbsp;  
**plan** ([enlarged image here](/img/plans/vent-plan-large.jpg))  
![vent plan](/img/plans/vent-plan.jpg)  
&nbsp;  
**underdoor** ([enlarged image here](/img/plans/vent-underdoor-large.jpg))  
Wavy line: darken ends with black marker or crayon.  
![underdoor vent 3d elevation and plan](/img/plans/vent-underdoor.jpg)
&nbsp;  
 
The first vent can go anywhere. For example, as a supply vent, attach it to a window insert and crack the window behind it. The other vent is for under a door. 

- materials:
    - thin cardboard (1-3mm) or posterboard (like a cereal box)
    - black velvet
    - wood glue
    - masking tape. 
- essential characteristics
    - matte black lining
    - zigzagging air channel
- assembly
    - principles:
        - one square=2cm
        - cut solid lines 
        - fold dotted lines and reflatten
        - join pairs of lettered points in alphabetical order 
        - affix fabric inside vent but not on margin flaps, which are for joints. 
    - sequence
        1. fold vent together once without glue to see how vent assembles. Temporarily tape joints
        2. slit flaps where necessary to join pieces
        3. where flaps have nothing to attach to, fold and glue them back to reinforce edge
        4. plan order of joint and fabric gluing
        5. cut fabric
        6. then glue everything 
    
##### fan

The quick and dirty solution is a 12V DC case fan, also known as a squirrel cage fan. 120mm is a common size. Salvage it from a discarded desktop computer tower, or buy it used for $1 at thrift stores or flea markets or new for $5-50 at a computer or electronics store. Power it with an AC/DC universal adapter with variable voltage for speed control ($1-5 at thrift or discount stores).

If you do not have electricity, and you just want to try this for a night or two, power the fan with AA batteries. You will only need 4-8 of them for one night. Tape them together in series, positive end of one to negative end of the next, with one fan wire at each end of the series. No fan movement? Switch the positive and negative wires.

Constantly changing the batteries quickly gets to be a pain. I got a proper solar power system for less than $100:

* solar panel: 12V. Size depends on location: 10W in Guatemala, 40W in rainy Oregon winter. ($10-$100 on eBay)
* charge controller: 12V, 4 or 6-pole ($35 on eBay)
* battery: 12V 7A, lead acid ($30 at a motorcycle shop)
* wire, 20 AWG, enough to connect everything ($0-10 from a dumpster, yard sale, or hardware store).

Once set up, just keep the panel clean.

###### noise

Using such a small fan for more than a few days at a time raises the noise issue. These fans run at high speed, so they hum and develop harmonics. This can get irritating. 300-400mm case fans are available. The bigger a fan is, the more slowly and quietly you can run it, and the longer you can retreat without irritation. 

But case fans are axial fans. These cannot efficiently generate pressure to overcome resistance in ventilation systems (long or narrow pipes, heat exchanging cores, filters). Centrifugal fans can. However, motors of both case and centrifugal fans are usually integrated with the fan blades. This puts the motors in the airstream, so they cannot be fully silenced. 

A truly silent fan is the last problem to be solved for an ideal darkroom. I have conceived a design for a 700-900mm, low-RPM [homemade centrifugal fan](http://gingerybookstore.com/product36.html), with a soundproofed motor _outside_ the airstream. The fan's metal or plastic parts would be lasercut at a sign shop according to an open-source, electronic design file. Please write me for details.

Ventilation silencers are also available. They work like a gun silencer and have DIY potential.

###### heat recovery

If you live in a cold place, I highly recommend buying and installing a [Heat Recovery Ventilator (HRV)](http://en.wikipedia.org/wiki/Heat_recovery_ventilation). It conducts heat from outgoing stale air to incoming fresh air, keeping the airstreams separate. 

Fine wire heat exchange (fiwihex) technology is my favorite. It is 10x more efficient than conventional plate exchangers. Fiwihex cores are available for $150 from [Viking House](http://vikinghouse.ie) and [Vision4Energy](http://vision4energy.ne). These companies' "Breathing Windows" are interesting designs for a complete ventilation system. But I lived with one for six months and found it too loud due to its small fans with integrated motors. Thus all my thinking about silent fans.

The most interesting plate exchanger is the Mitsubishi _Lossnay_core, found in Energy Recovery Ventilators such as [Renewaire's](http://www.soundgt.com/recvent.htm). Made of high-tech paper, the Lossnay recovers heated water vapor as well as heat from air. Lossnay's principle has DIY-potential, using 25m<sup>2</sup> of non-siliconized parchment paper ("sandwich paper" in supermarkets). I have conceived a design for it. Please write me for details.

Both these cores would take the truly silent fan concept mentioned above. 

#### darken door

**door seal** cross section  
![door seal cross section design](/img/plans/door-seal.jpg)

1. Affix 50mm wide strips of black fabric to door with masking tape _or_ white school glue. Fabric should bend around one edge of the door when it closes and fill the gap between the door and jam. 
2. Where an underdoor vent is necessary, put strips to its sides.
3. If gaps on sides and top leak light, affix another strip to trim so door bends it closes with fabric between jam and door.
4. To remove glued-on fabric, wet it. This will dissolve the glue and the strips will fall off. As this happens, wipe off the rest of the glue with a wet rag.

#### darken window

To darken windows, use one of the three methods I have come up with---insert, plastic, and foil---or have blackout blinds made with side rails.

Problem: many blackout blinds are not completely lightproof and some have toxic plastic coatings like polyvinyl chloride (PVC). Get full disclosure of material content (I saw "polymer" on a material data sheet recently, which can mean any plastic, including pvc). Get a guarantee of absolute lightproofness of the entire installation. Tell them you will be testing it with high-tech equipment (eyes that have had three days to adjust to darkness). 

I found PVC-free shades listed here: [Draper Inc](http://www.draperinc.com/windowShades/PVCfreeShadeFabrics.asp). 

Of the three homemade methods, described in detail below, the insert is best because it is easily removed, non-toxic, sound-dampening, decorable panel. It has three variations. Plastic can be reused, perhaps traveled with. It is easier and quicker than the insert. It smells a little. Foil is for one-time use, and the PVC tape is toxic, so avoid if possible.

##### insert 

**elevation**  
![insert design](/img/plans/insert.jpg)

This is like a stretched canvas for painting, but with lightproof padding around the frame and maybe paper instead of canvas. A smart, creative friend, [Hannah Torres](https://www.facebook.com/bodyalkforbalance), gave me the idea. Read through instructions to understand the process and make an exact parts list. The instructions are long because I've broken the process into tiny steps. All figures are metric. As always, feel free to write me with any questions you might have.

The insert will fit inside the window opening and against the window frame. The insert makes space for window handles that stick out beyond their frames. 

If your air supply comes through your window, attach a lightproof vent to the insert on the back near the top so it does not stick out into the room. Test position of vent before gluing to make sure it clears the window frame, handles, etc. If your supply and return air pass through your window, you will need two lightproof vents, one near the top and one near the bottom of the insert.

###### parts list 

1. dimensional lumber: 18-24mm x 35-50mm x 15% more than enough length to get around the insides of your window openings
2. deck screws: 40mm, 8-12
3. strap: webbing or strap sewn of fabric, ~25mm wide x 200mm
4. cover
    1. fabric: lightproof (black, heavy, tightly woven, and thick: two layers of 12oz canvas, or dense wool blanket)
    2. paper: heavy kraft
5. wood glue (for paper cover)
6. cardboard (for paper cover): clean and odorless, from furniture and appliance stores. Use double-layer cardboard or two sheets of single-layer to ensure lightproofness
7. light seal (for paper cover):
    - fabric
        - black fabric: jersey knit, khaki twill, or canvas 
        - open cell foam, 6mm thick
    - felt
        - felt carpet padding, ~5mm thick
        - thumbtacks

###### frame 

1. Measure the window opening---all four sides as they are rarely identical.
2. Determine lumber orientation (which way the wide and narrow sides should face) to accommodate handles, blinds, hooks, etc. If possible, the wide sides of the boards should face the room and window rather than up, down, left, and right. To gauge this, hold a short piece of lumber up to the window frame.
3. Subtract 8mm from the two long measurements and cut two boards of lumber this length. Mark each board as left, right, top, or bottom.
4. Mark one end of each board. Put the marked ends together depending on orientation (wide to wide side or narrow to narrow side). Measure thickness of two boards together at each end. Subtract these measurements from the short window opening measurement taken in step 1. Then subtract 8mm more. Cut two more boards these lengths.
5. Screw the frame pieces together, using pilot holes to prevent the wood from splitting.
6. Using wedges or folded paper, wedge the frame into a bottom corner of the opening.
7. Cut four more pieces of wood about half the length of the short sides for temporary angle stabilizers.
8. Screw two of them diagonally to the front of the frame in opposite corners. This stabilizes the angles of the frame.
9. Mark the top board in the middle of the underside.

###### cover

**fabric cover**  
This is a quick, non-permanent method. If you need a lightproof vent in your window, this method is incompatible with it, so use paper cover instead.

1. Get a piece of thick, lightproof fabric (eg, a heavy quilt or wool blanket) bigger than the window opening by 20cm on all four sides.
2. Drape it over back of frame
3. Push frame (with fabric) into the window opening. 
4. Use extra fabric to seal any light leaks around the edges. Stuff extra fabric back into the crack between the frame and window opening with a dull knife (like a table knife).
5. Ignore remaining steps. You're done!

**paper cover**

1. Remove frame from opening and place front side down on a clean floor.
2. Screw two more stabilizing boards diagonally to the back of the frame behind the first stabilizers.
3. Remove the front stabilizers.
4. Put down enough clean cardboard to fit inside the frame.
5. If it is more than one piece, butt and glue the edges together with strips of cardboard and wood glue. Allow the glue to dry for 30 minutes.
6. Lay the frame over the cardboard (always front side down).
7. Mark the cardboard along the inside of the frame with a sharp pencil, taking care not to bump the frame out of place.
8. Mark the cardboard where the top of the frame is marked.
9. Remove the frame and cut the cardboard along the marks.
10. Lay the frame back over it to check how well it fits inside the frame. Trim cardboard as necessary.
11. Remove the frame. Turn the cardboard over onto its other side, next to where you have been working.
12. Put down something soft and flat that is bigger than the frame, like a blanket, towel, or piece of foam.
13. Lay down the fabric or thick kraft paper that will cover the frame, visible side down. Use a medium weight tightly woven, natural fabric like twill or canvas. Do not use common blackout blind fabric. Besides being expensive and toxic like all vinyl products, it is ineffective: light seeps through it.
14. Lay the frame over it so the cover extends beyond it 15mm to make sure where it will end up.
15. Mark two inside corners at the ends of a long side.
16. Remove the frame and apply a 6mm bead of interior wood glue all the way around its front side.
17. Lay the frame back onto the cover where you marked the corners.
18. Press the frame into the cover all the way around to distribute the glue.
19. Scrape up any glue that has squeezed beyond the frame.
20. Wipe around the outside with a wet rag where there was glue.
21. Weight the board with stacks of books.
22. Let the glue dry for 4-24 hours.
23. Apply glue to the edge of the cover and wrap it around the edges of the boards.
24. Use tape to hold it down if necessary.
25. Lay the frame down
26. Remove the stabilizers.
27. Put the cardboard back into the frame, aligning the marks on the cardboard and the frame.
28. Apply an 8mm bead of black acrylic caulk where the cardboard touches the wooden frame.

<!-- {pagebreak} -->

###### light seal 

**fabric seal**  
![insert seal, fabric design](/img/plans/insert-seal-fabric.jpg)  
**felt seal**  
![insert seal, felt design](/img/plans/insert-seal-felt.jpg)

<!-- {pagebreak} -->

**fabric seal**

1. Cut 6mm thick open cell foam into 15mm strips, enough to go around the outside of the frame twice.
6. Cut 80mm wide strips of black fabric, enough to go around the outside of the frame once
2. Apply a 4mm bead of glue to the back of the frame near the outside edge on one board. Spread the glue with your finger. 
3. Affix a strip of foam at the edge. Repeat for the other three boards. There should be no gaps between the foam strips.
4. Apply a 4mm bead of glue to the outside of the frame near the back edge on one board. Spread the glue with your finger. 
5. Affix a strip of foam at the edge. Repeat for the other three boards. There should be no gaps between the foam strips.
7. Apply a 4mm bead of glue to the back of the frame, next to the foam, on one board. Spread the glue with your finger.
8. Affix a strip of fabric so that it covers the foam and extends outward beyond the frame. 
3. Affix additional strips as necessary, closely butting the ends together to leave no gaps.
9. Upon reaching a corner:
    1. wrap the fabric toward the front of the frame so it lays on the outside
    2. wrap the outside part of the fabric around the corner of the frame
    3. wrap it back over the back of the frame and continue gluing
    4. This leaves a folded triangle of cloth sticking out from the back of the corner.  Once you have gone around the frame like this, use scissors to neatly trim off triangles
10. Glue fabric strap, 25mm x 200mm to top outside of the frame so it hangs over the front and does not interfere with the foam and fabric light seal. This is the handle for removing the insert from the window.

**felt seal** 

1. Cut 50mm wide strips of felt carpet padding, enough to go around outside of insert once
2. Apply a 4mm bead of glue to the back of the frame on one board. Affix a strip of felt so that it extends outward beyond the frame. 
3. Affix additional strips as necessary, butting the ends tightly together to leave no gaps.
3. Upon reaching a corner:
    1. since glue is wet, secure the felt at the corner with a thumbtack
    2. wrap the felt toward the front of the frame so it lays on the outside
    3. wrap the outside part of the fabric around the corner of the frame
    4. apply a short bead of glue in the corner
    5. wrap it back over the back of the frame
    6. glue and secure felt with another thumbtack in the back of the frame
    7. This leaves a folded triangle of felt sticking out from the back of the corner. Use scissors or razor knife to neatly trim off triangle so edges of felt butt against each other, not overlap
    8. Add a bit of glue under the edges and secure them with thumbtacks
4. Glue fabric strap (see step 10 of fabric method above).
5. When glue is dry (2-4 hours), remove thumbtacks.

Put the insert into your window opening to test for lightproofness. Add felt or fabric as necessary.

##### plastic 

1. Cover windows with .2mm / 6-10mil (.006-.010″) black polyethylene plastic sheeting, found at building supply houses in rolls or off a roll by the meter. Multiple layers of black garbage bags would work, too.
2. Measure and cut it to extend 100mm beyond window frame because light and air often leak between the frame and wall.
3. Tape plastic to the wall. Use 25mm black masking tape. It is effective, cheap, sticks and conforms well to irregular wall surfaces, yet comes off easily without residue (unless you leave it up a long time). Not perfectly lightproof, it works with the plastic. Local art and professional lighting supply stores carry it. [lightsonretail.com](http://lightsonretail.com) sells Intertape PF3. If masking tape is not sticky enough on your surfaces, use black kraft paper tape. It is thicker (more lightproof), stronger, more expensive. Look for ProGaff (formerly Permacel) 743, Shurtape 724, and 3M 235.
4. Avoid electrical and gaffer's tape. They are made of soft vinyl and especially obnoxious adhesives and are thus extremely toxic in their manufacture, handling, use, and disposal.
5. If the room gets too hot from direct sun, then before taping up the black plastic, cut a piece of cardboard the same size as the window opening. Tape or glue aluminum foil to one side of it. Leave 15mm spaces between the strips of foil to allow moisture to pass through. Set the cardboard in window opening, foil facing outward.
6. If it is a cold room, do exactly the same thing as for a hot room, but with the foil facing inward. If the room gets hot and cold with the seasons, open up the plastic on one edge and switch the cardboard around every six months.

##### foil

1. Buy heavy duty aluminum foil and black vinyl electrical tape, 19mm wide.
2. With scissors, cut several 3cm pieces of tape and hang them within reach of the window. Keep scissors handy, too.
3. Remove roll of foil from box. You will unroll it directly onto the glass and cut it with scissors in place. If you unroll foil from the box, away from the window, then move it to the glass, it will crease slightly. This breaks the foil and creates light leaks you can't see till the middle of a retreat. Bummer.
4. The other part of the basic method is to tape the foil directly to the glass. If you tape it to the frame, suspended in midair away from the window, it will rattle as air pressure changes near the window. 
5. Starting at top left of window pane, unroll foil downward 10cm. Tape foil at top with small piece of tape.
6. Continue unrolling to bottom. Cut a little longer than the glass.
7. Unstick tape at top and position foil against frame.
8. With small pieces of tape every 50 cm, tape left side of foil to frame and right side to glass (or overlapped foil).
9. Repeat steps 5-8 starting at top right of window pane. Then fill in the middle.
10. Tape foil seams, where the foil sheets overlap. As you pull out a length of tape, it will stretch. Let it relax before applying it
11. Tape the foil to the frame (it's a bit tricky to bend the tape into the corner of glass and frame; please improve this method).
12. Hang dark blankets over the windows to catch any leaks.

#### bathroom & kitchen

Here are designs for quick, cheap, portable fixtures you can incrementally improve as you find out the value of retreating for yourself. 

For a 4-day retreat in a building without plumbing, improvise like this: 

- toilet: a 20-liter bucket with a toilet seat on top. No kidding!
    - put 2 liters of sawdust in the bottom
    - put 15 liters more sawdust in another bucket by the toilet
    - put a half-liter of sawdust in toilet after each use
    - place toilet away from bed and close to exhaust vent
    - dispose of waste in a covered compost pile that is going to sit for a year
- bathing
    - washcloth or sponge for a sponge bath
    - upgrade 
        - on waterproof floor (or covered with large plastic sheet) make a 2m diameter border of towels or bedsheet and sit in the middle 
        - put shower water in two 1.5-liter bottles with drinking spouts
        - hold a bottle above yourself with one hand and wash yourself with the other
- sink
    - basic
        - 20-liter bottle with valve-cap
        - on 20cm-high stand
        - above rectangular plastic tub (like a restaurant bus tub)
        - on a table
    - upgrade
        - salvaged sink set in a counter-height table
        - drains directly into waste bucket
        - upgrade again by adding a drain tube to outside. 
- drinking water (if separate from wash water): in 20-liter bottle with valve-cap
- waste (water and food): two, 20-liter buckets with lids

Voila.
 
Too punk rock for you? Upgrades below.

<!-- {pagebreak} -->

##### composting toilet

![composting toilet top design](/img/plans/toilet-top.jpg)  
![composting toilet liner design](/img/plans/toilet-liner.jpg)  
![composting toilet frame design](/img/plans/toilet-frame.jpg)

Basically, a 20-liter bucket sits inside a solid box with a hole in the top. The return duct attaches to a hole in the side of the box. So all air exits the room through the toilet, containing all odor. Bucket also collects pee, so empty it every 3-5 days. Making a urinal or a toilet that separates pee from poop is possible, too. 

###### construction

- top
    - made of 15-20mm tongue and groove boards or 12mm plywood
    - front and back boards, ~25mm x 37mm, fit on top of front and back frame pieces and between frame legs
    - hole is slightly smaller than bucket 
    - attach toilet seat & lid to top
    - reinforcer only for tongue and groove boards, directly behind toilet seat mounts
- liner
    - liner goes inside frame
    - toilet bucket goes inside liner
    - liner made of 0.2mm plastic sheeting, folded into open box. Do not cut. Fold triangular flaps, _A_, outside box
    - 15mm minimum space between bucket and toilet top
    - cut hole, _B_, 3cm small for snug fit on return duct
    - top edges fold over horizontal frame pieces and get thumbtacked in place
- frame
    - joint is extra strong, non-planar joint
    - dots, _C_, indicate heads of screws. Always drill pilot holes for screws
    - dimensions: 35-40cm high x 60cm wide x 60cm deep

##### portable shower

**exploded view**  
![shower design, exploded](/img/plans/shower.jpg)

A simple shower which requires no plumbing pipes uses (from top down):

- hook (in ceiling, 30mm)
- bucket (4-liter, hangs from hook)
- siphon tube (polyethylene, 4mm ID x 50cm, bent close to the middle with heat, hooked over the rim of the bucket)
- 4 cords (hang from hook, tie to curtain rod, maybe through holes in the curtain)
- shower curtain rod (circular, 120cm diameter, made of 30mm OD (outside diameter) black poly pipe, wood dowel joint)
- shower curtain (polyester, attach hooks to top edge to hang on rod OR put rod in top hem and make holes for cord, 5cm bottom hem with small river rocks inside to weight it down)
- large tub (90 liters or more, round or rectangular, from garden supply store, catches everything at the bottom)

Water heating methods:

- solar: use two, clear 2-liter bottles with small sheets of black plastic inside to act as elements. 
- electric tea kettle with indicator lights covered. Obviously this is a little dangerous, so practice it before retreating to get measurements and procedure right.
	
When ready to bathe, suck on the tube to start the siphon action. Water flows for eight minutes. Not bad. Larger bucket=longer showers=more water needed. Dump used water into a 20-liter bucket with a lid for disposal later.

~~

I assume you will find simpler, more adaptable ways to make darkrooms in a variety of settings. Please share your methods!

~~

More metric near-equivalents:

- 1m = 40" 
- 1m<sup>2</sup> = 10.75ft<sup>2</sup>
- 4' x 8' sheet = 120cm x 240cm (3m<sup>2</sup>) 
- 1 kg = 2 pounds

[&lt;](/design/)&nbsp;&nbsp;&nbsp;[`^`](/)&nbsp;&nbsp;&nbsp;[&gt;](/faq/)
{:.arrow}
