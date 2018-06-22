# sideEffects
A meditation on confronting the side effects of medicine.
----------------------

## Start Up
npm install
yarn start

## Background

### All Hail Our Robot Overlords

Computers can do a lot for us humans. They solve complex problems that we could not unless given incredible teams and quantities of time. They allow for precision execution on a level that was unimaginable even in the mid-20th century. They can even keep us from making some of our most common and stubbornly persistent mistakes.

### That's a You Problem, Not a CPU Problem.

What they can't do is solve our human problems. There are some problems that people have that are strictly human, be they biological, emotional, or social. Computers can't stop us from becoming addicts, or from becoming anti-social. Computers can't stop us from being lazy when we have the opportunity to be, or to be quixotic when we have the impulse to be. On the contrary, we designed computers, so all of our human problems that we haven't confronted or "solved" over the course of the rise of humanity have been exacerbated by computers. Drugs that exploit our addictive tendencies are more available in more forms than ever thanks to computers. Distractions propagate to such an extent that distraction, not focus has become the social norm. Laziness has become a general feeling that people are just incompetent and it is the rare person who simply does their job well.

### This, Too, Shall Pass

To solve human problems using computers, you have to route the problem back through humans. We have to use computers to force us to solve our own problems. The reason "are you sure you want save" prompts appeared in Word for Windows in the first place was the fact that the programmers knew that if a user saved something they didn't want to, or quit without saving without realizing it, that that was actually the user's fault, but they would blame the computer.

One of these problems that mean nothing to computers is the fear of health decline and death. The biosphere's inevitable reclamation of our being is an underlying source of anxiety for most people. And the front lines of this anxiety is our ever-growing pharmaceutical/medical industry. Anyone who has watched TV and seen a batch of commercials in recent years has watched an add for a drug, and that ad, while never really being able to explicitly claim any positive side-effect for that drug, is legally obligated to feature a litany of potential side-effects caused by the advertised drug. So, if you experience forgetfulness, dyskinesia, sleeplessness, unexpected bleeding, hair loss, depressed thoughts, restless legs, twitches, warts, crossing of the eyes, or the rocking chair blues, please contact your doctor right away, or seek the help of a medical professional.

Every symptom is caused by something, and in the era of computers, we expect that every symptom has a root cause that can be accounted for, treated, and ultimately overcome with the help of an MD, or at least a Web MD. But perhaps the solution to our problems lies less in finding a cure for our symptoms and more in normalizing the symptoms themselves. The so-called failings of the body, might also be called side-effects of life.

## Project Goals
-----------------
- Create a database of side effects using the [FAERS API](https://open.fda.gov/data/faers/)
- Use the database to give people an opportunity to think about the symptoms described, separated from the context of the drug that caused them.
- Provide ways to play with and experience that data - aural, visual, literary, orthoganal, tangential, etc.

## Stack (Subject to change in early stages)
------------------------
- React - front-end for providing an extensible collection of ways for users to interact with the data.
- Redux - for maintaining state as the application grows and data interactions become more robust.
- NodeJS - for a simple backend that can be easily wrapped into the same task-runner deployed locally.
- ExpressJS - for a rapidly-deployable collection of endpoints for accessing and altering the data.
- DB (undecided)
- Heroku and/or AWS for storage and publishing when the time is right
- Gulp or Webpack - for a task-runner
