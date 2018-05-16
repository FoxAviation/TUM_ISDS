# Storyline #
1. Opening scene: Waking up
    * Setting
        * In front of a house/building
        * Early morning
    * Camera
        * Perspective view on building
    * Story
        * Fade in from black
        * Sound: Atmo: Early morning nature
        * Sound: alarm ringing
        * Sound: Pistol reloading, pistol shot and flash in window, alarm silent
        * Fade out to black
    * Alternative story
        * Fade in from black
        * Sound: Atmo: Early morning nature
        * Sound: Alarm ringing
        * Sound: Alarm being dropped into cup of water
    * Sound
        * Atmo: early morning nature
        * Effect: Alarm ringing
        * Pistol shot
2. Entering office
    * Setting
        Inside office, door
    * Camera
        * UCU of door handle from side
    * Story
        * Handle beeing pushed down
        * Door opening
        * Actor enters office
3. Making coffee
    1. Selecting coffee
        * Setting
            * Coffee machine in office
        * Camera
            * UCU on selector panel of coffee machine
            * UCU on display of coffee machine
        * Story
            * Actor pushing button on coffee machine
    2. Coffee brewing
        * Setting
            * Coffee machine in office
        * Camera
            * UCU on coffee outlet of coffee machine, upper part of coffee cup visible, narrow focus
        * Story
            * Coffee beeing dispensed into cup until stop
            * Actor removing cup from coffee machine
4. Todo-List
    * Setting
        * View onto a whiteboard, showing a todo-list containing only "Install mysql"
    * Camera
        * MCU on whiteboard
        * Zoom-in on "Install mysql"
    * Story
        * Fade in from black
        * Actor walks to whiteboard with cup of coffee and looks at the todo list
        * Actor feels like this is going to be an easy day
        * Fade out to black
    * Sound
        * Early morning music, maybe radio news
5. Failing hard
    * Setting
        * Daylight
        * Office with table and laptop or stationary computer, showing a command line
        * Actor sitting at the desk
        * Cup of coffee on the table
        * One stack of coffee cups
    * Camera
        * Static: MCU: Actor and table from side view, some background
        * CU: Person typing
        * CU (screencast): OS showing a console
    * Story
        * Actor walks to table with cup of coffee in his hand
        * Actor sits down on chair
        * Actor starts typing, thinking, obviously trying to get the computer to do something
        * CU (screencast): OS showing a console
            * Typing the command to install mysql
            * System showing dependency errors, ...
            * Stackoverflow, ...
     * Sound
        * Music (Record atmo anyways)
6. Timelapse clock
    * Setting
        * Clock running
    * Camera
        * Frontal view on clock, timelapse
    * Story
        * Clock ticking though 12 hours
        * Fade-out to black
    * Sound
        * Clock ticking
7. 11 hours later
    * Setting
        * Black screen, center text "11 hours later"
    * Story
        * Fade-out to black
    * Sound
        * Distinct gong
8. Working at computer at night
    * Setting
        * Night-time scene
        * Same setting as before...
        * Multiple stack of coffee cups
    * Camera
        * Static: Actor at table, some background (dark)
        * CU (screencast): OS showing a console
    * Story
        * Fade in from black
        * Actor typing, frustrated and tired, still tries to get the computer to do something
        * Actor attempts to drink coffee, but cup is empty. Actors frustrated/angry
        * CU (screencast): OS showing a console
            * Typing the command to install mysql
            * System showing dependency errors (ideally different to scene 2)
        * Actor standing up, walking away
    * Sound
        * Music (Record atmo anyways)
9. Title screen
    * Setting
        * Computer console
    * Camera
        * CU (screencast): OS showing a console (large font!!)
    * Story
        * Typing: "Configuration management" (Enter)
        * Console output: "A movie by: Daniel Federschmidt and Felix Wieser
    * Sound
        * Typing sound (live recording of typing?), mono
10. Introduction: How is computer configuration done in computing centers?
    * Setting
        * Same setting as scene 1
    * Camera
        * Static: MCU: Two actors and table front view, some background
        * Static: MCU: Two actors and table; side view
    * Story
        * Dialog: Discussion
            * Installation of software on a computer is a tedious process
            * Discussion: Using scripts to configure nodes
            * Imagine having not just one but many computers
            * How do computing centers maintain thousands of computers?
    * Sound
        * Voices of the two actors, stereo
11. Introduction to the LRZ
    * Setting
        * Daylight
        * Outdoor in front of the LRZ
        * One actor standing in front of the camera
    * Camera
        * MCU: Frontal to actor
        * MCU: Perspective
    * Story
        * Actor informs the viewer, that he is in front of the LRZ
        * total number of clients, clients are called nodes
        * "Take a look inside to find out how they manage all these nodes"
        * Actor goes to and opens the entrance of the LRZ, disappears inside
    * Sound
        * Actor voice, mono
12. Sweep though the computer cube
    * Setting
        * Inside the computing cube of the LRZ
    * Camera
        * Tracking shot though the corridors of the computers
        * Tracking shot cables
        * Static: Blinking LEDs
        * Static: Low: Walking
    * Story
        * Actor walking though corridor, trying to figure out how the computer infrastructur works
    * Sound
        * Music or ambient sound (Record anyways)
13. Transition to explanatory part
    * Setting
        * Inside the LRZ, maybe on the bridge or in the colored corridor
        * One actor frontal to the camera
    * Camera
        * Static: MCU and frontal to actor
    * Story
        * <TODO: Explain everything required to understanding the concepts of configuration management>
14. What is configuration management?

    Alternating shots from __14.1__ and __14.2__

    Dynamic, alternating switches between interviewer, Niels and greenscreen footage

    1. Interview LRZ (Niels Fallenbeck)
        * Setting
            * Room
            * Two interview partners sitting on one side of a table
        * Camera
            * MCU: Frontal, both interview partners in view
            * CU: Interview partner
        * Story
            * __lrz_interview_fallenbeck.md__
        * Sound
            * Both actors, stereo
    2. Greenscreen footage
        * Setting
            * Greenscreen
            * One actor
        * Camera
            * MCU: Frontal
            * CU: Frontal
        * Story
            * <TODO>
        * Sound
            * Actor, mono
15. Outro/Transition to presentation
    * Setting
        * Office
        * "Many" stack of coffee cups
    * Camera
        * MCU: Frontal, two actors, sitting at a table
    * Story
        * In-Transition: After last greenscreen, physically remove greenscreen
        * Actor 1: "Actor 2, we should think about proper configuration management"
        * Actor 1: Configuration management is complex and challenging, but there are tools out there to help you manage critical infrastructure
        * Actor 2: Lets take a look at two popular configuration management tools: Puppet and Chef
---- Presentation ----
99. Credits
    * Setting
        * Credit roll left + outtakes right
    * Camera
        * none
    * Story
        * Left: Credit roll
        * Right: Outtakes
    * Sound
        * Music + audio from outtake as partial fade-in


# Abbreviations
Abbr.|Description
-----|----
CU   | Medium close-up
MCU  | Medium close-up
UCU  | Ultra close-up

# General notes (do not pay too much attention to this) #
* What is the problem? Why configuration mangement?
    * Situation: Not just a single computer, but entire set of computers to initialize, configure, update, ...
    * How would the world look like without configuration management?
        * Writing scripts
    * Motivation according to intruduction in paper
    * Pictures
        * Sweep though LRZ [~1 min material]
        * Somebody typing on a computer (CU: keyboard, entire table with actor and computer [15 sec material])
        * On-screen footage: Writing a traditional script
        * Matrix-like numbers... (   cmatrix screen recording) [5 sec material]
        * Interview outtake for motivation [~ 3 min material]
* How does configuration management work?
    * Features according to report
    * Many animations and pictures will be needed!
    * Shoot part of the explanation at the LRZ (nice background) ?
* Conclusion and transition to presentation


# TODO #
- [X] Zeitplan festlegen
- [X] Interview-Partner festlegen
- [ ] Fragen für Interview
- [X] Weitere Kameras notwendig?
- [ ] Tontechnik ausleihen (Tonstudio)
- [ ] Lichttechnik organisieren & ausprobieren
- [X] Drehorte festlegen (Wie sind die Rahmenbedingungen?)
- [ ] Welche Animation, etc. notwendig?
- [X] Sprecheraufnahmen im Studio möglich?!
- [ ] Kameras & Zubehör durchklingeln

# Equipment #
## Kameras ##
 Camera  | Use
---------|--------------------------
Legria HF G40 | Primary cam
Sony EOS | Static scenes, Interview: Secondary cam
GoPro    | Landscape, action, ...


## Tontechnik ##
Tontechnik steht voraussichtlich uneingeschränkt zur Verfügung und kann jederzeit abgeholt werden. Das Setup besteht aus zwei Richtmikrofonen, die an an einem Galgen befestigt werden und so ideal für Interview-Situation genutzt werden können. Außerdem habe ich ein speziell für die Aufnahme von Umgebungsgeräuschen entwickeltes Mikrofon, falMCU wir mal keine Hintergrundmusik haben. Die Aufnahme erfolgt mit einem transportablen Aufnahmegerät, dass die beiden Mikrofone in zwei seperaten Tonspuren aufnimmt.

## Licht ##
* min. 2x Tageslicht-Leuchten
* 1x warm
* Reflektor Tages-/Kunstlicht 1x1 m
* Diffusor 1x1 m

# Animationen #
_TODO_
