# Unreal Engine 5

## Contents

- [Unreal Engine 5](#unreal-engine-5)
  - [Contents](#contents)
  - [Blueprint vs. C++](#blueprint-vs-c)

## Blueprint vs. C++

**Blueprint** is a graphical language created specifically for Unreal. It can be programmed directly in the editor. Blueprint is quick to change, but is more appropriate for small to medium projects.

Blueprint and C++ can be used together in a project.

The various components of an event graph are:

1. **Event Graph**: It is the canvas on which we create our blueprints. We can _right click_ on it to get a list of possible nodes.
2. **Node**: It is a pre-made functionality that we can use in our blueprint.
3. **'Event' Node**: This is essentially a 'when' node.
4. **Pins**: Sockets (input/output) in nodes that we can connect.
   1. **Input Pin**: _When_ to run this node.
   2. **Output Pin**: What to do _after_ running this node.
5. **Connection**: It is a 'wire' between pins.
6. **Actor**: Any object that goes in a level.
7. **Component**: Objects that go _on_ an actor.
8. 