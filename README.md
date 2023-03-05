# Description
**"Hangman"** is a guessing game. Goal is to guess a correct word randomly chosen by app.

**[Game's Wiki Page here](https://ru.wikipedia.org/wiki/%D0%92%D0%B8%D1%81%D0%B5%D0%BB%D0%B8%D1%86%D0%B0_(%D0%B8%D0%B3%D1%80%D0%B0))**

## Usage
1. Required Ruby (v. 3.1.2) installed on your PC.
2. Clone application to local PC:
```
git@github.com:Godlikefreq/hangman.git
```
4. Open app's folder through command console.
5. Run
```
bundle install
bundle exec ruby main.rb
```

## Settings
By default game allows 7 errors to guess word. To increase/decrease errors count change `lib/game.rb`:
```ruby
class Game
  TOTAL_ERRORS_ALLOWED = 7
```
You can add your own words into the game by adding them into this file. Game gives you 7 
tries to guess the correct word by entering lessons one by one and shows a current status (hangman's picture, 
guessed lessons or errors) in console.


