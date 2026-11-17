<!--
  PATH-1.MD: one teammate's part of the story.

  Put your name after by: below. It's shown at the end of your endings.

  Your first scene must be called path-1. The crossroads scene in start.md
  links to #path-1, so that's how players get here. Everything else in this
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

by: Miguel Manfre

## path-1
You reach the village as a ship's horn sounds through the fog. Nobody is outside, but you smell fresh bread coming from a small bakery.

Next door, an old man watches the dark lighthouse from his window. A faded sign above his door says KEEPER.

[Knock on the bakery door](#bakery)
[Knock on the keeper's house](#old-keeper)
[Go back to the crossroads](#crossroads)

## bakery
Rosa opens the door before you can knock twice. "I heard the ship too," she says. "You won't get far out there without a light."

She takes a brass lantern off a hook, lights it, and hands it to you.

get: lantern

On the counter sits a freshly baked apple pie. You haven't eaten since leaving the mainland.

[Stay for a slice of pie](#pie)
[Thank her and head back out](#path-1)

## pie
You sit down and promise yourself you'll only stay a minute. After eating, you lean back beside the warm oven and fall asleep.

A loud knock wakes you at sunrise. The ship's captain has reached the village after spending the night anchored offshore.

"We waited all night for a light," she says. You look down at your empty plate, wishing you had kept moving.

THE END

## old-keeper
The old man introduces himself as Abernathy. A chart of the island covers his kitchen table.

"I can't climb those lighthouse stairs anymore," he says. "But we can still warn that ship."

He gives you a brass key and points through the back window.

"My emergency flare is in the shed. Get it and fire it toward open sky where the captain can see it."

get: brass key

[Go to the keeper's shed](#keeper-shed)
[Go back to the crossroads](#crossroads)

## keeper-shed
You follow a muddy trail behind the house. The shed door rattles in the wind, but a brass padlock holds it shut.

Through a gap in the boards, you spot a red flare case on a shelf.

[Unlock the shed and take the flare](#flare-ending) if brass key
[Return to the keeper's house](#old-keeper)
[Go back to the crossroads](#crossroads)

## flare-ending
You open the padlock and take the flare outside. Following the instructions on its case, you launch it into the sky.

A bright red glow spreads above the village. Moments later, the ship sounds its horn and turns away from the dangerous shoreline.

Abernathy reaches the gate just in time to see it.

"You gave them the warning they needed," he says.

THE END
