<!--
  PATH-4.MD: one teammate's part of the story.

  Put your name after by: below. It's shown at the end of your endings.

  Your first scene must be called path-4. The crossroads scene in start.md
  links to #path-4, so that's how players get here. Everything else in this
  file is yours: rewrite it, add scenes, add endings.

  Cheat sheet:
    ## scene-name                  starts a new scene (lowercase letters,
                                   numbers and dashes, no spaces)
    Any text you like.             a blank line starts a new paragraph
    **bold**   *italic*
    ![What the picture shows](images/my-picture.png)
    get: lantern                   the player picks up a lantern
    [Open the door](#hall)         a choice: leads to the scene called hall
    [Unlock it](#vault) if key     a choice that only works if you have a key
    THE END                        this scene is an ending

  Lines inside these comment marks are notes. Players never see them.
-->

by: Ryan Garcia

## path-4
At the door of the light house, you begin to gaze up words in pure shock of the size of the lighthouse.

[Unlock the door](#stairs) if iron key
[Knock and hope someone answers](#knock)
[Go back to the crossroads](#crossroads)

## path-4
At the edge of the crossroads, you spot a tall lighthouse standing near the ocean. Its light has stopped shining, and a thick fog is beginning to cover the water.

You realize that a ship could crash into the rocks if the lighthouse stays dark.

[Search the nearby beach](#key-shore)
[Walk toward the lighthouse door](#lighthouse-door)
[Go back to the crossroads](#crossroads)

## key-shore
You walk down toward the beach and begin searching through the sand and rocks.

Something shiny catches your attention. You reach down and discover an old iron key.

get: iron-key

You now have the key that might unlock the lighthouse.

[Head back to the lighthouse](#lighthouse-door)

## lighthouse-door
You arrive at the lighthouse entrance. The wooden door is old, and a rusty lock holds it shut.

[Unlock the door with the iron key](#lighthouse-stairs) if iron-key
[Knock and hope someone answers](#lighthouse-knock)
[Go back to the beach](#key-shore)

## lighthouse-knock
You knock on the wooden door. The sound echoes throughout the lighthouse, but nobody answers.

You wait a few seconds before realizing that nobody is coming to open the door.

[Step away from the door](#lighthouse-door)

## lighthouse-stairs
The iron key turns, and the door slowly opens.

Inside, you discover a spiral staircase that leads to the top of the lighthouse. It is extremely dark, and you can barely see the steps.

[Climb the staircase carefully](#lamp-room)
[Turn back and leave](#lighthouse-door)

## lamp-room
You finally reach the top of the lighthouse. In front of you is a large lamp surrounded by glass prisms.

You open the small door at its base and turn the brass valve. The lamp slowly begins to glow.

Suddenly, the light shines across the ocean, cutting through the thick fog.

Far away, you hear a ship's horn blow twice. The ship has safely found its way around the rocks.

You have successfully saved the ship!

THE END

## lighthouse-ending
You decide that entering the lighthouse is too dangerous and return to the crossroads.

As you walk away, you hear a loud crash in the distance. The ship was unable to see the rocks through the fog.

You realize that you should have tried harder to restore the lighthouse.

THE END
