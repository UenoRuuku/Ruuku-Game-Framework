## Ruuku Game Framework

#### Introduction

Ruuku Game Framework is a framework encapsulated the origin application class provided by JavaFX. Program your scenes by create subclasses of View and apply them into your game application.

#### Structure

- Framework.java

The class that stores the static instance of the game application and the engine.

- Engine.java

The engine that maintains the main loop of the game.

- gameApplication.java

The class that stores the scene, the root pane and the panes(Views) that are used to demostrate the game content, and controls the overall life loop of the whole game.

- game.java

A simple example of how to apply gameApplication.java into normal works.

- VIew.java

A encapsulation of the javafx pane class. Provide life-cycle functions that used in  gameApplication.java

