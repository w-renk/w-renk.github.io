# HypWitchBot

HypWitchBot lives in the chat for HyperionWitch's Twitch stream. It responds to certain words said in chat and provides a fun little game for viewers to play with certain perks that can be purchased with channel points (not yet implemented).

## Non-Exhaustive List of Commands

### Command format
All commands must be preceded by an exclamation point (!).

Extra arguments need to be provided for some commands; e.g., `!select PET_NAME` takes one argument, the name of one of your pets. If I wanted to select my pet named Charles, I would run the command `!select Charles`.

Arguments that are inside square braces ([ ]) are optional; e.g., in `!give ITEM_NAME [ PET_NAME ]`, *PET_NAME* is optional and the command will still run if it isn't present.

### !help
Responds with a short description and a url to this page.

### !hunt
Prints a fun message in chat.

#### **The following gameplay related commands are in TESTING (but you're free to use them with the understanding that any channel points spent will not be refunded and gameplay progress may be lost)** 

### Buy a Pet (Channel Points Reward)
Spend some channel points and get a pet! The first time you do this, HypWitchBot will enroll you in the game. You will be asked for a name for your new pet. Names can only be one word long, but can contain most punctuation except `, \\, ', and " (illegal punctuation will be stripped from the name). Also, when choosing a name for your pet, don't be an asshole.

### !pets
HypWitchBot will respond with a list of pets you own.

#### **The following gameplay related commands have not been implemented yet**

### !delete
HypWitchBot will delete your game progress. It will ask you if you are sure you want to proceed and give you a message you will need to respond with. Your progress can not be restored and your channel points can not be refunded. If you want to start playing again, you will need to spend channel points to purchase a new pet.

### !select *PET_NAME*
Switches your active pet to the one named *PET_NAME*.

### !stats *PET_NAME*
HypWitchBot lists the stats for the specified pet.

### !battle or !fight
Your active pet fights a random battle to win prizes

### !rename *OLD_NAME* *NEW_NAME*
Renames your pets. If you have pet a named *OLD_NAME*, it will change its name to *NEW_NAME*. You can't have multiple pets with the same name. Please don't name your pet something offensive or inconsiderate. Will doesn't want to have to ban people for silly reasons like that. Names can only be a single word, but they can include numbers, hyphens, underscores and probably most other punctuation except for backticks (`), backslashes (\\) and double quotes/inch marks (").

### !give *ITEM_NAME* *\[ PET_NAME \]*
Gives the named item (if you have one) to your active pet, or to the pet specified by *PET_NAME* if present. All items are consumables. Even if you give your pet a piece of equipment, it can't be retrieved and it will be lost if you combine that pet with another.

### !combine *FIRST_PET_NAME* *SECOND_PET_NAME*
The specified pets fuse to create a new pet (if you have selected a valid combination), or into a more powerful version of the first pet specified in the command

## The Game

**Very little of this has been implemented yet. This is only a tentative overview.**

Any viewer can play, there is nothing you need to do to start playing beyond purchasing a pet with channel points. If you haven't yet purchased a pet, HypWitchBot will not respond to any game-related commands you use in chat.

Once you purchase a new pet, HypWitchBot will give you a random one and tell you its name. If you would like to rename it, just type `!rename *OLD_NAME* *NEW_NAME*` in chat. You can purchase as many pets as you like (for now, limits may be placed eventually).

Fight battles with your pets to win coins that you can spend on various items and upgrades for you pets.

Combine pets to make stronger versions or entirely new pets.

Gloat to other viewers about how much more awesome your pets are than theirs.