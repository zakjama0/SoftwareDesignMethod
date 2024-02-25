### Software Design Methodologies
## 1. What do we mean by coupling and cohesion when discussing structured design?

# Cohesion:
Cohesion refers to the ability of the class, the range of actions the class could do. For high cohesion, the class is focused on specific methods and functions, relating to the intention of the class. As for low cohesion, the class is less specific, thus making the class mre broad in context.

# Coupling:
Coupling refers to the relationship between two classes, the dependency of eachother. For tightlhy coupled classes, altering one will significally effect the other, making it very hard to maintain code without significantly changing both codes simultaneously. Loosely coupled classes mean that altering one class won't heacily effect the other, making customisation and editing of code easier.

## 2. What is the difference between top-down and bottom-up design? Which best describes a function oriented design?

# Top-Down vs Bottom-Up
These models describe how a system is designed, two approaches having a range of different advantages and disadvantages. The top-down approach describes a broad system design and building it in its entirity, then breaking tasks into smaller parts.  The design is then broken into parts and is then further designed, checking for problems. This is mainly used in structured programming languages such as Fortran and C. Pros for Top-Down approach are that defects in the design can be found early, thus being able to be corrected early. There is also an easier isolation of interface errors. Bottom up design refers first detailing smaller and detailed individual parts then joining it together for a complete solution, object oriented languages such as Java Python and C# use this design approach. Pros for Bottom-Up approach include flexible testing as the approach allows easier test condions which are easier to observe.

# Function Orientated Design 
FOD is when a design is decomposed into a range of interacting units each having a clearly set and defined function. The geneic procedure for the design is that it starts with a high level description of the function of what the system does which is then refined into greatly detailed parts, leading to a top-down structure.

## 3. In which design methodology would a class diagram be most useful?

## 4. What are the four pillars of object oriented programming? Give a single-sentence description of each.

# Abstraction
Hiding the detailed functions of a class, and wrapping up its complexity, so it can be used without entirely knowing what it is.

# Encapsulation
Removing public access of parts of code, and making it private, in which code should be able to control it's own state. 

# Inheritance
Allowing one objects to acquire attributes (properties and methods) of another object.

# Polymorphism
Allowing methods and parameters to be used acrossed several other methods.



