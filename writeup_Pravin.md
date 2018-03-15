## On Text Games and Augustan Rome

If there's one thing I learned in Classics 20, it's that game development is an invlved process.

Our group for the creative project consisted of two people - myself (Pravin Visakan), and a friend from another section (Kirill Shumilov). I knew from the moment I saw the guidelines that we would try some sort of interactive text story. Robigalia, from lecture, seemed to be the perfect setting for a story - an irate deity of wheat rust seemed both comical and dangerous at the same time.

We hashed out the basic outline of the plot and locations together. Our primary ssource at this point was a [page](http://penelope.uchicago.edu/~grout/encyclopaedia_romana/calendar/robigalia.html) on Robigalia put up by the University of Chicago. Specifically, they have an excerpt from Ovid's *Fasti*, in which he describes tagging along with a couple of flamen and the details of ritual. 

This is where the gathering of ritual ingredients comes from - Ovid lists wine, dog entrails, and incense. But, of course, every game has a lose condition.

Through a few iterations, our plot developed. Basically, the player would gather the three ingredients, though this is not normally their job (our initial justification for this was fun - we were going to have the flamen fall down a well). These ingredients were scattered throughout Rome, in shops and various mini-puzzles. However, alongside them were "bad versions" of the same. For the wine, there was grape juice; for the incense, there was some used up incense left behind at te temple; and for the dog entrails, there was some older refuse lying around. If the player wasn't careful, they could lock themselves off from getting all the good ingredients, and be forced to substitute it with the bad.

Some spoilers ahead. Getting all "bad" ingredients results in a bad ending - the gods are angry, Rome is poised to starve, and a riot begins to brew. Getting all good results in the "good" ending - the gods are pleased, and send an omen showing that you are to be granted manumission. Some combination of the two results in a "meh" ending, somewhere between the two. 

The game renders using stock web technology. I made many of the original graphics, most of which remain as the "item portraits" the player sees when acquiring an item. However, much of the typesetting, CSS, and overall aesthetic of the game was thanks to my partner. Our inspiration was largely in popular media involving Romans - the frescos, the mosaics, and pictures of engravings.

We ended up dividing the writing between us in terms of "episodes" - I took over the episodes involving the Butcher and the dog, the Villa and Ovid, and the overall exposition and ending. My partner wrote out a few store scenes, the "hub" areas (Subura, the Fora descriptions), the Ager Romanus, and the brothel. We wrote the game using Twine, in which the basic unit of story is called a "passage". Each of these scenes could take one to several passage, and each required both writing and a bit of Javascript to keep everything ticking.

We drew upon class and other resources to try and paint an accurate picture of Rome. A big help was Diane Favro's *The Urban Image of Augustan Rome*, suggested by the professor. I found the opening and ending chapters - "A Walk Through Republican Rome" (before Caesar's time), and "A Walk Through Augustan Rome" (after the death of Augustus), especially helpful. We decided to set our game in between the two, a period of transition that had aspects of both.

In the Butcher and dog bit, I tried to capture the hectic, crowded, grimy image of streets that Favro portrays. The butcer (and many other shopkeeps) are a little intense, eager for a sale. Stray animals lurk in the corners of alleys, and these too are willing to give a lot of trust for a little in the way of material goods, like meat. A slave rifling through garbage doesn't get looked at twice, though this last is more due to convenient game logic.

The Villa on Palantine Hill, and the encounter with Ovid, draw heavily on our readings. I set the Villa as it is, blocking the wind into the city, as a reference to Seneca's *Moral Epistles*, Letter 55, in which Vatia's villa does the same. The guard at the door, the party, and the later interaction involving grape juice or wine, are more anachronistic.

The Orator's speech, at the Forum, is based on the opening to Cicero's Pro Caelio - both invoke the idea of a holy festival. The meeting with Ovid is based entirely on the character he embodies in *The Art of Love*, Book One, where one of his tips involve women in the Forum. The guard's high appraisal of him can be assumed.

With the game, I tried to shape our main character with with the facts of Augustan slaves, as related in lecture and other readings. My initial conception of him was heavily influenced by the comedies, *The Haunted House* by Plautus (as well as the *The Brothers Menaechmus*)and *The Satyricon*. I wanted someone a little lazy, a little clever, sarcastic, and in the end, vying for his freedom. 

Throughout the game, the player needs to be little tricky, too. They need to lure a dog with meat, or give the name of a sketchy person to a guard. In one of the stores, they drive home a bargain by pretending to leave. Sex and violence (the brothel, the leering Ovid, and the butchering of the dog) appear throughout.

The endings all involve vultures bearing signs, in one way or the other. This is from Livy's telling of Rome's founding.

There are places, where in collaboration, some of these impressions get muddied. My own cultural biases and perceptions no doubt affect things - I usually imagined Gaius with a wise-cracking, almost gangster-esque manner of speech. I believe my partner may have had in a main character with a more philosophical, more thoughtful, bend. I did my best to reconcile all of these qualities in our work.

