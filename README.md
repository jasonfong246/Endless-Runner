Endless Runner game
 By: Da Wei Lau, Jason Fong
 Video Link: https://www.youtube.com/watch?v=JDijKYI0XnE
 This is an endless runner game. The goal of the game is to avoid all the obstacles and survive as long as possible to
 achieve a high score. The character can run in one of the three lanes. The game is implemented by using things that
 we have learned and implemented in previous labs and lectures such as Unity new input system, camera follow with
 offset, displaying text in game and finite state machine. We also have a tutorial series for an endless runner game on
 Youtube, which will be talked about more later on. Here is a scene from the game.
 Completed Functionality
 First of all, we used the new Unity input system to implement being able to control a character and make it move left
 and right and jump. One of the problems we faced was how to ensure the character stays in one of the three lanes
 when the user presses left or right. We also need to ensure the character can jump and land after a certain amount of
 time. The next functionality we have is how to generate an endless level. We achieved this by having three separate
 sections and every 2 seconds it will duplicate one of the sections randomly by instantiating a new section at the
 position we want. We also added character models and animation (jumping, running and falling backwards when
 colliding). Next thing we implemented is the collision of character with obstacles. The character will stumble
 backwards and the game will end and return to the main menu after colliding with an obstacle. We also implemented
 a main menu and scoring, so the further you run, the higher the score.
 Workload Distribution
 Jason came up with the left and right control for the character, which includes the right and left control script and the
 handler script for both of those controls. Jason also worked on the camera follow with offset script. Da Wei worked
 on the jump control and jump control handler script. Da Wei also designed and built the scene by adding all the
 prefabs. Da Wei also wrote code for generating the level endlessly. Da Wei also added the running, jumping and
 stumbling backwards animation for the character. Da Wei also wrote the script for obstacle collision. Jason wrote
 code to keep track of the score and came up with a separate scene for the Main menu. Jason is also responsible for
 the scene transition script.
Techniques used
 Weimplemented this game using a lot of concepts we learned from previous labs and lectures. We will talk about
 techniques that we implemented first before talking about the techniques we brought into the project. First of all, we
 used the new input system from Unity to move the character around, we used code from Lab 1 as reference but had
 to make some modifications. We also used Lab 1 as reference for the camera follow with offset script. We also used
 Lab 3 as reference for our collision of obstacles with the character. Lab 3 was also used to help implement the Main
 Menu and implementation of the text mesh pro for the scoring.
 Next, I want to talk about the technique we brought into the project. We used Jimmy Vegas tutorial series on
 Youtube as reference for how to generate the level infinitely. We also learnt about animation and importing character
 models from Mixamo from that tutorial. The animation of the character is done through the unity animator system
 which uses the finite state machine concept, which is something we learned in lectures. The character transitions
 from one state to another when an input is detected.
 Illustrations
References
 Our main reference is a Youtube tutorial series by Jimmy Vegas on Youtube. Here is a link to the tutorial.
 HOW TO MAKE A 3D ENDLESS RUNNER GAME IN UNITY FOR PC & MOBILE - TUTORIAL #01 - I…
 Weimported the characters and animation from Mixamo. The character is called “Aj” and the animation we used are
 called “Standard run, Jump and Stumble Backwards”
 Wealso imported an asset from the unity asset store.
 https://assetstore.unity.com/packages/3d/environments/landscapes/lowpoly-environment-pack-9947
