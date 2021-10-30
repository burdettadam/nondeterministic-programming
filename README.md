# Nondeterministic Programming

This project explores the idea a program could nondeterministic replicate
itself iteratively towards an ambiguous goal.

## Causal Loops

“So there’s this man, he has a time machine. Another thing he has is a
passion for the works of Ludwig van Beethoven. And one day he thinks,
“What’s the point of having a time machine if you don’t get to meet your heroes.”
So. Off he goes to 18-century Germany. But he can’t find Beethoven anywhere.
No one’s heard of him. Not even his family have any idea who the time traveller
is talking about. Beethoven literally doesn’t exist. This is called the bootstrap paradox.
The time traveller panics. He can’t bear the thought of a world without the music of
Beethoven. Luckily, he’d brought all of his Beethoven sheet music for Ludwig to sign.
So he copies out all the concertos and the symphonies and he gets them published.
He becomes Beethoven. And history continues with barely a feather ruffled. My question is this:
who put those notes and phrases together? Who really composed Beethoven’s Fifth?”" - The Doctor

## An observers Response of Causal Loop

Suppose Ludwig van Beethoven never did exist, but the culture of the 18-century was very
interesting to this man with a time machine. You see he found historic notes of that era
and was compelled to visit. During his travels he made friends, learned traits and changed
the original historic notes that attracted him in the first place to enhance his travel.
The changes in these notes in turn changed his own history he had no memory of. The very
history of this mans travels produced notes that initiated his trip. Watching this circular
dependent history play out, the man changes historic notes to attract himself to music,
he starts publishing his notes in names that attract him and assist his travels. Each change
of history causes him to edit those notes until finally, this man no longer see’s himself in
Ludwig Van Beethoven so he preserves Beethoven legacy by creating him and his publications.
The man fears the loss of Beethoven and does not change the notes that lead him there. Watching
the bootstrap of Beethoven’s Fifth leads one to think that history itself was the true composer.

## Nondeterministic Program theory

Nondeterministic Programming is the result of many different nondeterministic programs interacting
with each other to generate new versions of themselves from those interactions.
each individual program contains notes for different goals which are subject to change at every iteration.
Each individual goal will produce novel code with notes which is not expressed in normal execution. The exchange
of this code to other individual programs with different goals will produce new optimal code and refinement of goal.

### individual

A nondeterministic program contains code for:

- validation
  - code to validate replicated code.
validation code has inputs for source code and notes about validation. checks that the replicated
program compiles and executes
- attraction
  - validated code is executed for attraction. Only the most attractive replicated
programs are traversed in future iterations. Each program contains source code that is
commented out. not expressed. Attraction has inputs for validated code with notes that are inputs
for the code to be run with. Most performant code is not always the most attractive, source code which has valid
code in comments, which when run aids or un-effects performance is more attractive. This mechanism allows nondeterministic
programs to continue to optimize optimal code.
- replication
  - code must replicate itself with new changes from previous programs.  Replication takes a list of
source code and notes from each source code executions. Generating new code composed of itself and other programs.
