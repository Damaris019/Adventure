<!--
  PATH-3.MD: one teammate's part of the story.

  Put your name after by: below. It's shown at the end of your endings.

  Your first scene must be called path-3. The crossroads scene in start.md
  links to #path-3, so that's how players get here. Everything else in this
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
by: Miguel Torres

## path-3
A torn fishing net washes onto the beach as you reach the shore. Farther out, a wreck leans against the rocks. Something inside flashes whenever the waves lift it.

Near your feet, a wooden sign reads: "Danger. Rising tide."

[Wade out to the wreck](#wreck)
[Build a sand signal for the ship](#sandcastle)
[Go back to the crossroads](#crossroads)

## sandcastle
You pile wet sand into a tall mound and plant a piece of driftwood at the top. You tie your jacket to it, hoping the ship's crew will notice it.

But the fog hides your signal. A wave knocks down the mound, and you spend the rest of the night trying to rebuild it.

At sunrise, you see the ship anchored offshore. The crew stayed away from the island, but your signal never reached them.

THE END

## wreck
You climb onto the tilted deck and follow the flashing light. It comes from a metal box swinging beneath the steering wheel.

Inside, you find a heavy iron key attached to a tag that says "Spare lighthouse key."

get: iron key

A smaller silver key is tucked beneath the tag. An anchor is stamped into its handle.

get: silver key

A wave hits the wreck, making the floor shift beneath you.

[Take the keys back to shore](#path-3)
[Search below the broken deck](#wreck-deeper)

## wreck-deeper
Through a hole in the deck, you spot a chest caught between two beams. Its lock has the same anchor symbol as the silver key.

Water pours through the damaged hull. You have time to try the lock, but staying much longer would be dangerous.

[Open the chest with the silver key](#wreck-treasure) if silver key
[Leave the chest and swim to shore](#swim)

## swim
You jump clear of the wreck and swim toward the beach. A strong wave pushes you sideways, but you grab a rock and pull yourself into shallow water.

You reach the sand, coughing and exhausted. Anything you were carrying is still secured in your pockets.

[Rest on the beach](#path-3)

## wreck-treasure
You unlock the chest and find a sealed pouch of coins beside a delivery note. The money was meant to buy a rescue boat for the village, but it never arrived.

You tuck the pouch and note inside your coat and escape through the hole in the deck.

By morning, you reach the harbor office and hand over what you found. The harbor master reads the note twice.

"We thought this was lost forever," she says. "Now we can finally replace our rescue boat."

THE END
