# learningGame
Game Design: Parts of Speech

Goal:<br />
     As a Player
     I would like to learn the Parts of Speech
     while enhancing my grammar skills
     though an interactive game

Influence:<br />

     Grammar Gorrilas: https://www.funbrain.com/games/grammar-gorillas<br />	

The Elevator Pitch:<br />
     Player selects what type of part of speech is highlighted which will allow them to accumulate points.

Project Description:<br />
     Mini-game addition

What sets this project apart?<br />
     It is different enough and can be reused for other games.

Core Gameplay Mechanics:<br />

     - <Core Gameplay Mechanic #1> Select Part of Speech
		- <Details>
                    Player selects the part of speech that is selected
		- <How it works>
                    if (answer == user_answer) {
                        correct = true;
                    } else {
                        correct = false;
                    }

     - <Core Gameplay Mechanic #2> Collect Points
		- <Details>
                    Accumulate points for selecting the right answer
		- <How it works>
                    Add a counter then store value in a data structure

     - <Core Gameplay Mechanic #3> Multiplayer
		- <Details>
                    Compete against friends by way of the leaderboard
		- <How it works>
                    Compare scores on a list (best score = most points)

Story and Gameplay:<br />

     Story<br />

     Gameplay<br />
          Choose correct part of speech as indicated. Doing so accumulates points.

Assets Needed:<br />

     - Content<br />
          
          An array of sentences to be randomly selected for the Player to interact with

          SENTENCES
 
                    He screamed at the top of his lungs. Verb
 
                    The wolf stealthily hunted the rabbit. Adverb
 
                    The Ojibwe lived in domed structures called wigwams. Adjective
 
                    Her jingle dress made a twinkling noise as she danced. Verb
 
                    My mom says my room is messy. Adjective
 
                    A baby deer is called a fawn. Noun
 
                    The Ojibwe used nets – called dipnets – to fish. Verb
 
                    After 500 years, the Ojibwe completed their journey. Noun
 
                    A small stream wove through the wood.  Adjective
 
                    The average male black bear weighs between 150 to 300 pounds. Verb
 
                    The Ojibwe hunted buffalo, dear and rabbits. Verb
 
                    The horse ran rapidly through the plains. Adverb
 
                    She carefully sewed neat rows of beads on her moccasins. Adverb
 
                    The children listened closely as the elder told the story of their tribe’s history. Noun
 
                    The water in the river was cold, but had not yet frozen over. Adjective

     - 2D<br />

          - Textures
               - Environment Textures
          - Characters List
               - Character #1 (Player)
          - Environmental Art Lists
               - Example #1
               - Example #2 
               - Example #3
               - etc.

     - Sound<br />

          - Sound List (Ambient)

     - Code<br />

          - Character Scripts (Player Pawn/Player Controller)
          - Ambient Scripts (Runs in the background)
          - Example

     - Animation<br />

          - Environment Animations 
               - Example
               - etc.
          - Character Animations 
               - Player
                    - Example 
                    - etc.
               - NPC
                    - Example
                    - etc.
