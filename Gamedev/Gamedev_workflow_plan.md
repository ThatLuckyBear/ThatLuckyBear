## Workflow Plan:
What does making a game look like? What are the steps you'll take and tools you'll use? How is it best to chop up so that each can be worked on seperately while contributing to the greater whole. This also includes breaking down the learning process and adding new skills to your repetoire.

### Organizing Git as a workspace:
  - Use Projects to seperate out differnt parts of the process
    - Game features gets a board
    - Game Story Writing gets a board
  - Use Documents to work on things like story and gameplay ideas
    - prototyping is important so don't overplan start small and branch out from the ideas that work

### Gamedev Workflow
Identifying the different silos of work and separating them is going to be essential. Generally a good rule is "each new program is it's own silo" although that gets a bit confusing because of the massive overlap between each as the game comes together.
  - Silos
    - Assets
      - includes 3d modelling, fonts and textures
    - Writing
      - not only the story or arch but also the literal typing of things
    - Programming
      - coding that defines look, feel, and features of the game
      - code that implements and controls assets
Getting 

### Programming Workflow
##### Apps: Godot, Git
This flow is specific to the act and steps of creating a video game within Godot.
  - Define the project outline in a readme
    - What will the game be when it's finished
    - essential details only, keep complexity to other documents
      - "stretch" ideas don't exist. Either its in or it goes in the ideas bin for a future project.
      - essential can include gamefeel. having menus behave a certain way or a certain graphical trick can be core to the experience you're going for
  - Create a Git project for the game and use a Kanban to define the "essential" parts that would make the game "finished" 
    - Large parts are fine at first as you can break those parts down further as you hit obstacles
    - "menu" can be an item but "what items need to be in menu" can be a subitem if you need it to be more granular
  - Start working keeping track of sticking points and using that as a jumping off point to learn something new
  - Prototype often (within the essential ideas) to ensure things are working the way you intend

##### Coding
Expressing an idea for a function as code:
  - Take an idea and break it down into its parts until it can be expressed "as code" that is with individual pieces that can be coded separately without any code running underneath
    - ie: "Jump" (big idea) BECOMES > "player + y.velocity=UP + button press"
    - "button press" and "player" can be broken down further if not already implemented
Making code clean:
  - Redundancy should be eliminated as much as possible
  - Use global variables
  - Use classes and States

### Story and Writing Workflow
##### Apps: ??? (I need spellcheck), Github
This flow is specific to creating narrative and physical writing of needed text
  - Writing The Story
    - Start with "what feeling(s) do I want my player to experience as part of the narrative
      - be as specific as possible ie: "how it feels to be helpless in the face of adversity, but overcome it anyway"
    - Write out the general arc (this is flexible but a general start)
      - write as many ideas as you can and use the 7 point story structure as scaffolding to help keep ideas within 
    - Consider how the gameplay will impact the story and it's pacing
      - how will information be given to the player, passive? active?
      - how much does the player interact with the story (many choices, illusion of choice?)
      - where will the player be when things happen and how do we get them there?
    - Refine ideas into a more cohesive outline and start to weave it into gameplay to see if any programming needs to be done to make the narrative function

kiloheart bit crush - makes quality lower to give retro feel to audio: https://kilohearts.com/products/bitcrush
