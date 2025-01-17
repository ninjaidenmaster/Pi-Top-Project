# Pi-Top-Project

# Summary
For this Pi-top project, I created a fan powered by a pi-top motor. This fan is able to swap between three different modes: Slow, Fast, and Still. Depending on how fast the fan is moving, The LEDs on the fan would either turn Yellow (Slow), Green (Fast), or both unactive (off). The fan will only take the speed inputs if the fan power button is on (Red LED).

# Why a Fan?
This idea was created in my digital electronics class when I was thinking of something to code a build that is both simple and not so big. The idea was also influenced by the hot weather and how I needed to cool myself down without needing to do much other than pressing a couple of buttons. A fan would also be very useful in both convenience and portability.

# Images
Doc: https://docs.google.com/document/d/1oQsu7zgdsUsb6iGbRqz2KnkHp3aw4QqCX2iOjJFKy3c/edit?usp=sharing

# Video Demonstration


# The Sketch
When I thought of the idea of the fan, I needed to think about how it would look like in general, so I created a sketch of the fan. I decided that I would have a three bladed fan connected to a motor on the top of a tall box. On the left side of the box, there would be two buttons attatched, one for power and one for speed. On the right side, I would attach three LEDS to indicate its power and speed. Red would corralate to the power and Yellow/Green would corralate to speed. This box would also be hallow, so it could fit the Pi-top inside along with all of the wiring inside of it.

# Cardboard Layout
Once I had the sketch done, I would create a cardboard layout of the fan in order to see if my sketch would be able to work in reality. Cutting out several pieces of a cardboard box and piecing it together, I created a model that kind of resembled the sketch that I made. Because of how it turned out, it helped me realize that my sketch would actually be possible to make. So I took the measurements of the cardboard layout for later use.

# Coding the Mechanics
When I started coding my project, I had to figure out where I would assign the motor, buttons, and LEDs to on the Pi-Top, once I figured it out. I created the if-statement for the LEDs first, making it so that if the count (goes up by one every time speed button is used) reaches beyond 2, it would reset the count back to 0. This would help with changing the speed since 0 would be off, 1 would be slow (yellow), and 2 would be fast (green). For the power LED, I just made it toggle on or off whenever the power button was pressed. For the motor, I just inserted the speeds into the previous if statements, with slow belonging in the yellow LED statement and fast belonging in the green if statement. Like the LEDs, all I had to do was make the motor toggle whenever the speed button was pressed.

# The Actual Box

Once the coding process was complete, I started on making the actual fan frame. Originally, I was going to carve wooden slabs in order to make the box, but then me and my dad found a small white box that could perfectlly fit the Pi-top. Once we drilled holes accordingly into the box, we started to assemble the pieces. The LED lights would be attatched to the right side while on the left side, the buttons would be placed. At the top, the motor would be placed on the cover of the box. To prepare if the fan was too large, we found a block of wood and duct taped it in order to give it a more minimalistic look, then placed it on the bottom of the fan. After plugging in the wires through the holes, we then plugged them into their respective outlits in the Pi-top. Once putting in the Pi-Top, the fan was complete.

# Testing Problems
1. The LEDs would not turn on sometimes and would turn on to the wrong speeds
2. The Pi-Top would sometimes just not work.
3. The motor had a set speed of 114 and couldn't go any higher, limiting the speed more than I had hoped.
