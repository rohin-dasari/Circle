# Circle
Circle is an interactive iOS game that allows for increased accessibility by using a custom microcontroller. This page contains the code itself and general algorithmic information needed to understand how the controller works.
The device used is an Adafruit Flora with a Bluefruit Low Energy BLE transmitter. 
The input device is made up of 4 buttons. Two for player 1 and two for player 2. Each player has 3 possible interactions with their two buttons. When one of the possible interactions are detected, a unique key press is sent to the iOS device, which will trigger some action in the game. The game is built using unity, but the game is a standard iOS game, meaning that no configuration was required to make the arduino and Unity programs compatible. 
