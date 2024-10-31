# F1 Race Start Simulator
Mobile application about reflexes test (as some F1 and MotoGP athletes already [played](https://www.youtube.com/watch?v=BhLr43elNCE)).<br>
This app is about a game simulation with a reaction time, all based on the starting conditions of an F1 race.
It's based on [this web application](https://f1-start.glitch.me/).

## 📝 Table of Contents
- [Languages](#-languages)
- [📱 Gameplay & screenshots](#-gameplay--screenshots)
    - [Game view](#1-game-view)
        - [Use cases](#use-cases-)
    - [Performances views](#2-performances-views)

## <img src="https://www.pngall.com/wp-content/uploads/13/Country-Flags-PNG-Images.png" height="20" alt="langs"> Languages
The app is available in the following languages :
<ul style="display: grid; list-style: none; grid-template-columns: repeat(3, 1fr);">
    <li>🇬🇧 English</li>
    <li>🇫🇷 French</li>
    <li>🇪🇸 Spanish</li>
    <li>🇩🇪 German</li>
    <li>🇵🇹 Portuguese</li>
    <li>🇳🇱 Dutch</li>
</ul>

## 📱 Gameplay & screenshots
### 1. Game view
<div style="display: flex; gap: 10px; align-items: center; justify-content: center;">
    <img src="./Screenshots/GameView.png" width="150" style="border-radius: 25px;" alt="Game">
    <div>
        In this view, the user can play the game by tapping on the "START" button.<br>The five lights will turn on one by one and the user has to tap anywhere in the empty zone when the lights turn off to start.<br>If the user taps too early, he will have to restart again.
        <br><br>
        Finally, the user will see his performance (should be broken) and can choose to play again or to go back to the performances view.
        <br><br>
        As far as the other buttons are concerned, the one at the bottom left is for showing all the user's performances and the one at the bottom right is for exiting the application.
    </div>
</div>

#### Use cases :
|                                                 Normal start                                                  |                                                       Jump start                                                       |
|:-------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| <img src="./Screenshots/StartSimulation.gif" width="150" style="border-radius: 25px;" alt="Start simulation"> | <img src="./Screenshots/JumpStartSimulation.gif" width="150" style="border-radius: 25px;" alt="Jump start simulation"> |

### 2. Performances views
#### Lists
<div style="display: flex; flex-wrap: wrap; gap: 10px;">
    <img src="./Screenshots/ListPerfsBestOrder.png" width="150" style="border-radius: 25px;" alt="List perfs order to best">
    <img src="./Screenshots/ListPerfsDateOrder.png" width="150" style="border-radius: 25px;" alt="List perfs order to date">
    <img src="./Screenshots/ListPerfsMenu.png" width="150" style="border-radius: 25px;" alt="Perfs filter menu">
</div>
<p>In this view, the user has access to all the reaction times taken since installing the application.
It's possible to sort this data in order (ascending or descending) of reaction time or the date on which the reaction time was established.
To do this, simply click on the buttons representing the filters.</p>

<div style="display: flex; gap: 10px; align-items: center; justify-content: center;">
    <img src="./Screenshots/NoPerfYet.png" width="150" style="border-radius: 25px;" alt="None perf listed">
    <div>If no reaction time has been set, this view asks the user to play with the simulator at least once.</div>
</div>

#### Evolution of performance
<div style="display: flex; gap: 10px; align-items: center; justify-content: center;">
    <img src="./Screenshots/PerfsEvol.png" width="150" style="border-radius: 25px;" alt="Evolution of the performances">
    <div>It's also possible to view the evolution of reaction times established to date. The user's average and best reaction times are also shown.</div>
</div>
