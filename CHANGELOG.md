# Changelog
All notable changes in this project will be documented in this file.
The format is based on [keep a Changelog](https://keepachangelog.com/en/1.0.0)

## [Unreleased]

## [1.0.0]2020-6-14
### Changed
-Since I have found that the idea of my privous project isn't quite effecient, after learned from the other project on github,I started a brand new project.[-defense.zip]
-Enemy moving part: remove the method which get an random move(just "up" "down" "left" "right") for the player in the file of
"Qmap" given by the professor since I think enemy travalling with the voyage is a more effecient way.[-game.h/Game::Game&&Game::createRoad]
-Changed a new map (the one used before is not very beautiful and painting it need alot of time).[-game.h/Game::Game]

### Added
-"magictower" is available now attacking enemy with little magicballs.[-firsttower.h]
-enemy "Dragon" is available which now worth 1 gold if killed and this kind of enemy is not aggressive.[-enemy.h]
-Gold system is established. player are originally given 500 gold. magictower need 200 gold to be bought.[-gold.h]
-Health system is built, too. Originally 10 point of health, One Dragon gets in cost 1 point of health.[-health.h]
