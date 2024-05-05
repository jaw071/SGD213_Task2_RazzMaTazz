# Architecture Options


### Option 1

 - architecture will consist of several unique game objects that make
   use of the component design pattern.
 - The game objects will include the player, a stationary enemy, a   
   patrolling enemy, and the game camera.
 - Movement for both the player and patrolling enemy game objects will  
   be provided by a movement component that interacts with the   
   rigidBody2D component of the objects.
 - A player controller component will listen for inputs from the user   
   and communicate with the movement component whenever it reads any.
 - An abstract base collision class will provide a template for   
   components that handle any logic for when its parent game object   
   collides with or enters another game object, for example, the player 
   interacting with pick-ups and when an enemy damages the player.
 - The main camera game object is controlled by the following player   
   component, which tracks the player game object’s position and moves  
   the camera relative to it.
 - This type of architecture allows for a greater degree of flexibility 
   and modularity compared to object-oriented programming. By reusing   
   the same components with different game objects redundancy and the   
   need to rewrite code are reduced. The use of decoupled components   
   allows for modular game objects as components can easily be changed  
   without creating conflicts with other components.
   
### Option 2
 - Architecture uses object-oriented programming and inheritance trees
   as a way to reuse code. Game objects inherit methods and attributes
   from a superclass to avoid rewriting code.

 - An abstract object class is created, including variable declarations
   for RigidBody2D, SpriteRenderer, and boxCollider2D.

 - Player class inherits from the actor class and implements methods for
   movement, input, and death.

 - The pickup class inherits from the actor class and includes methods
   for handling the player interacting with the pickup.

 - The stationary enemy class inherits from the actor class and
   implements a method for handling player collision.

 - The patrolling enemy class inherits from the stationary enemy class
   and includes methods for movement.

 - The camera class is written as a base class and includes code for
   following the player as they move.

 - This architecture provides a simple and easy-to-understand way for   
   reusing code but includes flaws as object-oriented programming does  
   not allow for sideways inheritance, this means that code for the
   movement cannot be reused for the player class and the patrolling
   enemy class. Likewise, the collision code for the pickup and enemy
   cannot be reused as well.
