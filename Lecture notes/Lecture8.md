### Activity diagrams

Represents the flow of control in a system
    - Parallell processes are denoted by a black rectangle with two (or more) lines coming out from it, usually called a fork. You can do both, or either/or
    - Where two (or more) activity edges meet, this is usually called a join, and the previous steps must be fulfilled in order to go to the next step
    - Decisions where one or the other activity must be done are denoted by a diamond
    - If your diagram require two or more actors, you can separate which activity belongs to which actor with vertical "swim lanes" and the name of the actor on top. Alternatively, horizontal swim lanes also work

### Sequence diagrams

Goes into the details of the activities within a system, interactions between elements
Represented in a step-by-step manner. They are 'almost' self-explanatory (to the software engineers)
    - Describes the timeline of an action (hence sequence)
    - A participant is denoted by a rectangle with a name
        - A participant can be an object, instance, etc
    - The lifeline is denoted by a dotted line and represents the individual participant in the interaction
    - An activation is denoted by a rectangle, and represents the period during which an element is performing an operation
    - Call messages is a message representing an invocation to a lifeline target belonging to a participant
        - Denoted by an arrow pointing to an activation box on another lifeline
    - Return message is the return of information from a call message
        - Denoted by a dotted line pointing back to the original call message of a participant
    - Self-message is a message that represents the invocation of the message of the same lifeline
        - Denoted by an arrow pointing to the participant itself
