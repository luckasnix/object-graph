# Object Graph

## Documentation

### Constructor

- `nodeValues`: Array of objects to be converted in nodes of the graph
- `keyExtractor`: Function that generates a key for each node

### Properties

- `length`: Returns the length of the object graph

### Methods

- `get`: Returns a node of the object graph
- `getAll`: Returns all nodes of the object graph
- `copy`: Returns a copy of the original object graph
- `add`: Adds a node to the object graph
- `toAdded`: Returns a copy of the original object graph with a received node added
- `addMany`: Coming soon...
- `toManyAdded`: Coming soon...
- `update`: Updates a node in the object graph
- `toUpdated`: Returns a copy of the original object graph with a received node updated
- `updateMany`: Coming soon...
- `toManyUpdated`: Coming soon...
- `remove`: Removes a node to the object graph
- `removeMany`: Returns a copy of the original object graph with a received node removed
- `toRemoved`: Coming soon...
- `toManyRemoved`: Coming soon...
- `valuesOf`: Returns all values of the provided property
- `match`: Returns all nodes that match with the provided matcher
