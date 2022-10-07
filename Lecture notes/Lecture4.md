#### I have no idea why the notes look absolutely clapped on github, they look normal in my text editor. It's to do with when I moved all my files into a new directory, but I don't know how to fix it. Oh well. 

Lecture 4 - UML II

Use Case Diagram
    - High level function
        - Define the behavior of a system/software without revealing internal details of it.
    - Show the observable functionality
        - Don't crowd the diagram
    - Actors act on the use case
        - "Set of actions" are the use cases
    - Can represent software and systems
    - Visualise functional requirements
        - Non-functional requirement are requirements that do not affect a system
            - Color, aesthetics
        - Functional requirements are the bare necessities of a system in order to work
            - Username, password, etc...
    - System boundary
        - The system boundary is defined by a rectangle, everything inside the rectangle tell us about the structure and behavior of a system
        - Actors are placed outside of the system boundary
            - Actors can be other systems outside of the boundary acting with another system: A system is unaware that a conscious being or a robot is acting with it.
        - Use cases are defined as oval-shaped
    - Generalisation
        - The functions of one actor can be inherited from other actors
    - Associations
        - A line between actors and use cases
    - Extensions
        - A line from child class to superclass that extends a use case, but is not "necessary": Sorting a search is an extension of searching, but is not inherently necessary to the concept of searching
    - Inclusions
        - A line from one function to another that necessitates a use case, and shows a sequence of necessary actions: Buying a product is necessitated by adding a product to the cart. Buying a product cannot exist without having the product in a cart

