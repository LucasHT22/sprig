# Introduction

It's crazy, but we are a Customs, everything we approve can affect the project, so we need to be careful. It is not because you know the person that you are going to evaluate with less care, with everyone we must always be as careful.

# Sumary 

* Introduction
* Sumary
* Triage
   * PR Template
   * GitHub "Tags"
   * GitHub Profile
   * Code
* Run
   * Solve all levels
* Review itself
   * Very similar or plagiarism
   * How to detect
   * Plagiarism suspect
      * Examples
   * Normal
      * Types
* Approve exceptions
* Tutorials

# Triage

First, add "submission" if it's a game submission or "update" if it's a game update.

> ![](https://cloud-gjdjlpoh4-hack-club-bot.vercel.app/0image.png) 
><br />
> How to add a tag?
> Click in "Labels" and choose the label.

The triage is just a brief analysis, see some interesting items:

## PR Template

In cases of game submission, the PR Template must have all questions answered, if not, add a revision of the "request changes" type and ask the unanswered questions

## GitHub "Tags"

![](https://cloud-k1l9o641e-hack-club-bot.vercel.app/0image.png)
"First time" person's first game

![](https://cloud-9vnz6tbjg-hack-club-bot.vercel.app/0image.png)
Usually, without "First time" has more than 1 game

## GitHub Profile

A quick look at the README doesn't take long and it's good to know who you're talking to.

## Code

At first just look if there isn't a link redirecting to something that could be malicious.

Interesting fact: a game 100% based on the tutorial will have around 230-250 lines.

# Run

It's not running away from the code but making the code run, alright, bad pun. 

## Solve all levels

It's normal in games with many levels to have unsolvable levels, so solve the levels until "you win!" (or something like this) to appear.

But you are error prone, so when you come across unsolvable levels, ask with a screenshot how to solve that level.

# Review itself

Some cases:

## Very similar or plagiarism

As much as it makes you very angry, don't lose your education, our template for that is this:

```
Thanks for PR! But this game is VERY similar to [LINK HERE], you're welcome to remix games, but please make sure to state the original author and modify it moderately.

If you need help, feel free to ask:)
```

Thank you [Kara](https://github.com/karamassie) for the template.

### How to detect

The only way is to play and look at the code of existing games in the Gallery and do something like [CodeGuessr](https://codeguessr.vercel.app/), I confess that I have created a fork many times just to change the name and try to guess which game it was.

An important detail: every code has some "signatures", variable names, code layout, sprite style and comments are some "signatures".

## Plagiarism suspect

The easiest way to find out if the person copied a game engine from another game, ask if they used any game inspiration (Example 1),

**if the person answers yes...** ask which game it was and see if it's just a function (case 1) or if the person just changed the sprites (case 2), 
* Case 1: just say to add credits in the code header
* Case 2: proceed as plagiarism.

**if the person answers no...** do a brief check on similar games, if you find a game that is very similar,
* Case 3: Function
    * Step 1: explain that it has a very similar function ask more specifically if the person used the specific inspiration game (Example 2)
    * Step 2: If the person says he forgot and you're right, great, just ask to add credits in the header, otherwise the person says no, let it go, it's better to avoid confusion and it's just a function, it's within tolerable.
    
* Case 4: All
    * Step 1: Capture the screen of an excerpt that is very clear in the copy and proceed as plagiarism.

💡Tip: Use (Example 1) at random, for bad intentions not to be able to "escape"

### Examples

1: Did you use any game for inspiration?

2: Did you use `GAME NAME` for inspiration?

## Normal

First understand the types of Review

### Types

![](https://cloud-4uiwovbdz-hack-club-bot.vercel.app/0image.png)

* Comment

We usually don't use it in PR reviews (of games), we use it when we want to comment on PRs outside that we are allowed.

* Request Changes

Most commonly, any changes or questions should be done in this type.

* Approve

Only when everything is right, here's how to compose your Approval message:

**Required items** 

1. The link to order: https://sprig-order.hackclub.dev/ NOTE: always accompany the link with a message like `If you're a teen, you can get your sprig here!`
2. The #ship message:
  ```
  Hack Clubbers would love to see this! Just post a link and 1-2 sentences talking about your game to our [#ship](https://hackclub.slack.com/archives/C0M8PUPU6) [channel](https://hackclub.com/slack/):)
  ```

Thank you [Kara](https://github.com/karamassie) for the template.



**[Lucas](https://github.com/LucasHT22) tips**

1. Compliment

Start with something like `Great game!` + when possible add a unique compliment, like: `sprites so beautiful!` or `nice dodge mechanism!` + a `Congrats:)`.

2. No interpretation gap

Always use exclamation points and `:)` because it doesn't sound like you're mad.

# Approve exceptions

* Case 5: Same game

   If it's the same game but with a different code, no problem at all, you can approve it with peace of mind.
   See this example:
   * https://sprig.hackclub.com/gallery/2048_Alphabet_Edition
   * https://sprig.hackclub.com/gallery/3072_A_2048_Spin-Off
   
* Case 6: Less than 5 minutes

   It's usually applied in maze games because there are bad people who make a game completely based on Sokoban with 3 levels just to get a console (Tip: A maze game with a 5 minutes gameplay usually has 5 levels.

   Other types of games often don't apply this requirement, for example it's so hard to play [Tunnel](https://sprig.hackclub.com/gallery/tunnel) for 5 minutes.

# Tutorials

It's super normal that you have to do tutorials, you can screen shot the steps and add in the comment.


---
   
<sub>Text written by <a href="https://github.com/LucasHT22">Lucas</a></sub>
