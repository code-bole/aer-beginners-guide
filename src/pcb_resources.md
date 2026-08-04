# Anushree's PCB Tips
- I recommend just picking a board (RTM, BSPD, CCM, etc) and just diving right in → no better way to figure stuff out than looking through the schematic for yourself
    - Learn the acronyms for the boards and what they stand for (you’re going to be hearing them A LOT)

- Have AI explain things to you → can take screenshots of certain parts of schematics and have AI explain to you its functions
    - Make sure to ask it questions like: 
        - Why did they choose xyz part?
        - What does xyz part do?
        - What is the purpose of xyz part?
        - Could xyz part be replaced by something better/easier? Why?
    - Aim to dig as deep as possible: any knowledge is good knowledge!
- Remember, with AI: trust, but verify!

- Once you somewhat have a grasp on what your assigned/given board does, make a presentation on it (individually or with a partner)! Run through all parts of the schematic and explain its functions
    - [My example](https://docs.google.com/presentation/d/1mx0g-cAfGusMjqLGmFd5wtbL-ejqtgY_k79ct8G-RjY/edit?usp=sharing)
    - Once you have an idea of how the board works, make sure to read ALL of the rules related to that system
        - [Ruleset](https://www.fsaeonline.com/cdsweb/gen/documentresources.aspx)
        - Understanding how the boards are rules compliant is super important to understanding why logic was implemented a certain way or why certain components were chosen
    - Make sure to present! You always learn/remember better by explaining to someone else

- Now that you’re confident on how your board works, it’s time to brainstorm possible improvements. Make a presentation on ways you can possibly improve the given board
    - [My example](https://docs.google.com/presentation/d/1NY_Lc-AJDH_oXvvpEkqkMn0eifhq0QqDiTz7k-_WDgE/edit?usp=sharing)

- I heavily emphasize that learning/looking into the Embedded code base will really help you understand the FUNCTION of the board itself
    - May not necessarily teach you the nitty gritty of why certain components were picked for certain boards, but it’s super important to understand what the board is trying to achieve in the first place
    - Easier to get the bigger picture if you understand how the code interacts with the hardware and how it’s rules compliant

- Look at old boards! → go to ECT/KiloZott and physically look at the old boards
    - How are they harnessed together?
    - How are they soldered? Are they through-hole or SMD? Why?
        - Are there any specific reasons why one type of soldering might be better than the other for the specific board?
    - Do there seem to be size constraints for the old boards? 
    - What components on the board stick out to you/can you recognize?
    - What components are you seeing for the first time? → Ask someone about them!
    
- Most importantly: ASK QUESTIONS!!!
    - If you don’t understand something (no matter how small or seemingly insignificant), ask someone!
    - Remember, everyone has to start somewhere! :)

## General PCB Resources
- [Good starter pcb video](https://www.youtube.com/watch?v=3FGNw28xBr0)

- Use AI! It’s super helpful when learning the ropes

- **READ THE DATASHEETS!**
    - Especially helpful when you're making boards: you need to know the details of the parts you're using
    - They can tell you important information like:
        - Pinouts (Ex: On a MOSFET, which pin is the Gate, Drain, and Source)
        - Recommended operating voltage and current
        - Typical applications in circuits
        - Other electrical characteristics
    - You don't need to read the entire datasheet! Just start with the most relevant to what you're working on

- PCBs at AER are heavily tied to the embedded code, so it’s important to at least have a bit of background information on what the codebase looks like (not necessarily required, but I definitely found it helpful)
    - [Detailed documentation on everything embedded](https://github.com/Anteater-Electric-Racing/aer-documentation)
    - Follow the README in the repo to run the documentation locally, then go to localhost to view the rendered documentation
    - Read through any important parts of the documentation that relate back to the boards/how they work

- If you have more time, I’ve heard good things about [this course by Altium](https://education.altium.com/p/unit-1-introduction-to-pcb-design)


