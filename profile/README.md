# Automated Scrabble Game Capture System for Alchemist Cup 2024
This organisation contains all of the code created to develop an intelligent scrabble system to facilitate the broadcast of Alchemist Cup 2024. It is currently broken down into the following repositories:
- [scrabble](https://github.com/AlchemistCup/scrabble) contains the pure Python Scrabble game logic package developed to maintain the internal match state
- [EmbeddedSoftware](https://github.com/AlchemistCup/EmbeddedSoftware) contains the software to run on the Raspberry Pis to capture game data and publish it to the server
- [QRDetectionTestbench](https://github.com/AlchemistCup/QRDetectionTestbench) contains the tooling used to test the various detection algorithms considered for game state capture on the Raspberry Pis
- [MatchDataServer](https://github.com/AlchemistCup/MatchDataServer) contains the central server software which handles all match data
- [CompanionApp](https://github.com/AlchemistCup/CompanionApp) contains the Android application used to obtain player input.
For more detailed information or setup instructions, please visit the relevant repository.
