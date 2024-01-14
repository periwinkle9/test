# Booster Tech

The Booster v2.0 works by instantly setting the player to the maximum possible speed,
which is almost double the normal walking speed. Because it is so much faster than normal
movement, you'll usually want to be boosting as much as possible.
However, the Booster has limited fuel, and when you run out of fuel (or let go of the boost button)
while in the air, your speed is instantly halved, thereby killing all of your Booster momentum
until you have a chance to land on the ground to refuel and start another boost.

However, there is a way to avoid this instant speed loss: If the player
**touches the ground while boosting**, the game cancels the boost without triggering
the speed-halving logic, leaving it entirely up to friction to slow you back down.
If the player were to leave the ground immediately after cancelling the boost like this,
they will preserve most of their original Booster momentum despite not actively boosting.

This is the idea behind **machine boosting**, a set of techniques for touching
the ground and immediately leaving the ground to preserve Booster momentum. With the
Level 3 Machine Gun, this speed can then be carried across long distances.

There are several different machine boosting techniques that can be applied in different
scenarios. Understanding where, when, and how to apply each one will save you a lot of time
in the speedrun.

*(Note: The following video clips all have an added horizontal speed display at the top right corner, for those curious.)*

## Boost Jumping

This is the oldest and arguably simplest form of Booster speed conservation.
As the name suggests, this technique involves boosting into the ground and then jumping to preserve
the momentum.

There are several ways to perform a boost jump:
1. Boost into a sloped surface, then jump:  
   {% include video-embed.html src="general/boost_jump_slope.mp4" alt="slope boost jump" %}
2. Walk off of a ledge, boost onto another ledge at the same height, then jump:  
   {% include video-embed.html src="general/boost_jump_across.mp4" alt="boost across boost jump" %}
3. Walk off of a ledge, immediately boost back onto that ledge, then jump:  
   {% include video-embed.html src="general/boost_jump_back.mp4" alt="walk off boost jump" %}

```tip
Make sure you are releasing and repressing the jump button *after* you 
touch the ground. If you release the booster before you touch ground, 
you will lose all of your Booster momentum. 
(Conversely, if you're not getting speed when you jump, it's because you 
released the jump button too early.)

The timing for the jump is not precise at all, but to get the most amount 
of speed, you should aim to jump as soon as possible after touching the 
ground.
```

## Using the Machine Gun to Boost Jump

This is a special form of boost-jumping, where instead of boosting directly
onto a ground surface, you use the Machine Gun's recoil to push you onto the ground.
I don't know of a specific name for this technique, but since the other ones all have
their own names, I'm just going to refer to this one as "machine boosting" even though
that's supposed to be the collective name for this whole set of techniques (yes, it's confusing;
I didn't make up these names).

{% include video-embed.html src="general/machine_boost.mp4" alt="machine boost" %}

To perform a machine boost:
1. Start boosting sideways (do *not* hold up here or you will boost upwards
   instead!)
2. While boosting, hold up and then start shooting the Machine Gun upwards.
   This will push you back onto the ground.
3. Immediately upon touching the ground (but not before!), release the jump
   and shoot buttons and jump again as soon as possible to conserve the speed.

```tip
If you need to descend very quickly (for instance, after exiting Cthulhu's Abode? 
in the ruined Egg Corridor), be careful that you face up *before* you 
start shooting, otherwise you'll shoot the first shot to the side and it'll 
take until the next shot 6 frames later before you actually start descending.
```

```note
The fastest way to move across flat ground once you have the Booster v2.0 
is to repeatedly chain machine boosts, as shown in the GIF below.

This is better than just repeatedly doing normal boosts because it avoids the 
dramatic speed loss you get from releasing the Booster mid-air or running out of fuel. 
Chaining machine boosts allows you to refuel your Booster without losing too much speed 
each time.

![machine boosting]({{ site.baseurl }}{% link /assets/general/machine_boosting.gif %})
```

## Corner-boosting

Corner-boosting is the fastest method for preserving Booster speed. It is done by using the
Machine Gun to boost upwards at a diagonal, and brushing up through a corner
while doing so. If positioned correctly, Quote will touch ground for exactly
one frame, allowing you to keep the maximum amount of Booster speed.

```danger
The positioning and timing for this technique is much tighter than the previous 
two techniques (in some cases, it is frame-perfect). 
However, in return it is extremely fast, so it's worth at least trying to learn. 
Don't give up! You can do it!
```

Corner-boosts can be performed in a few ways:
1. Walk off of a ledge, boost towards another ledge at the same height (as
   if you were going to boost-jump), but instead of waiting to touch the
   ground, start shooting down with the Machine Gun shortly *before* reaching
   the ledge:  
   {% include video-embed.html src="general/corner_boost_level.mp4" alt="corner boost 1" %}
   *(Note: Although Quote appears to stop looking down, you do not actually 
   need to release the down button. That's merely the frame that Quote touches the ground 
   to cancel the boost.)*

   ```tip
   **Troubleshooting Tips**

   The timing for when to start shooting also depends on your vertical 
   position. Here's how to correct your timing when your corner-boost fails:

   **Issue:** Quote continues boosting up at a diagonal (the boost does not cancel).  
   **Diagnosis:** You went too high and boosted over the corner.  
   **Solution:** Start shooting the Machine Gun later, **or** fall a 
   couple pixels lower when you initially walk off the edge before you 
   start boosting.

   **Issue:** Quote hits the side of the corner and stops moving horizontally.  
   **Diagnosis:** You were too low and collided with the wall instead of 
   the floor.  
   **Solution:** Start shooting the Machine Gun earlier, **or** start 
   boosting sooner when walking off the edge, so that you boost at a 
   higher altitude.
   
   **Issue:** Quote slides onto the ledge and doesn't gain any height.  
   **Diagnosis:** You shot the Machine Gun way too late, when you were already on the 
   ground.  
   **Solution:** Start shooting the Machine Gun earlier, before you reach the ground.
   ```
2. Walk off of a ledge, then simultaneously press **jump**, **shoot**,
   **down**, and \[the direction back towards the ledge\]:  
   {% include video-embed.html src="general/corner_boost_walkoff.mp4" alt="corner boost easy" %}

   ```tip
   This is the easiest method of corner-boosting (although these inputs may 
   be difficult to execute if you are playing on controller). 
   Although this setup is rarely the fastest for most situations, it can be useful 
   as a safety strat and/or a backup if you fail one of the other methods.
   ```
3. Position yourself next to a corner, slightly under ground level, then
   simultaneously press **jump**, **shoot**, **down**, and \[the direction
   towards the corner\]:  
   {% include video-embed.html src="general/corner_boost_yolo1.mp4" alt="corner boost 3" %}
   
   ```warning
   Depending on the situation, the timing for this may end up being frame-perfect or close to it.
   ```
4. If the corner is up at a diagonal relative to where you are: Boost sideways
   and shoot the Machine Gun downward so that you travel diagonally upwards,
   and just barely graze the corner while doing so.  
   {% include video-embed.html src="general/corner_boost_yolo2.mp4" alt="corner boost 4" %}

   ```warning
   The Machine Gun timing for this is usually frame-perfect.
   ```
