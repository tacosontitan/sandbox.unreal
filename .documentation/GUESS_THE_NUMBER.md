# 🔢 Guess the Number

This basic game is the very first game added to this repository. When the game loads, a random number between `1` and `100` is chosen and the player must guess the number within 10 tries. There's a lamp in this level that indicates how close the player's current guess is to the target number. It does this by using a blue color to represent "cold" guesses and an orange color to represent "hot" guesses.

## 📢 How to Play

> [!IMPORTANT]
> Coming soon...

When the correct number is guessed, the lamp turns green; then, the player is given the option to play again or navigate to the main menu.

## 💻 Implementation

The implementation for this game was rather rushed as I was going through issues with a molar at the time. I didn't start documenting until I had already complete the first few steps.

### ✨ Creating the Level

The first step with every game in this repo is to create it's level. For me, this entails creating the level asset itself and coming up with a basic design on how I want it to work. This level was intended to be incredibly simple with a light and a textbox for input. It grew a little from there for an improved user experience based on my personal experiences with testing the level and feedback from members of a few Discord servers I participate in actively.

After a good amount of tweaking the level looked like you see it today:

![A bright blue cube glows in the distance of a dark environment with the phrase "Guess the Number" printed at the bottom of the screen and a text block input just above it containing the number 42.](https://github.com/tacosontitan/sandbox.unreal/assets/65432314/f939fab6-ad5a-49ef-b47b-414a5a4578cc)

### ⌨️ Handling Input

The next step I took was to handle user input. I had a few things to address:

- The user wants to leave the level.
- The user submits a guess with the enter key.
