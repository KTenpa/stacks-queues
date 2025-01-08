# Stack and Queue Implementations

This repository contains basic implementations of two fundamental data structures: **Stack** and **Queue**. Both structures are implemented using linked lists, which allows for efficient insertion and removal of elements.

### Data Structures Covered
- **Stack**: A collection that follows the **Last In, First Out (LIFO)** principle. Elements are added and removed from the top of the stack.
- **Queue**: A collection that follows the **First In, First Out (FIFO)** principle. Elements are added at the back and removed from the front.

### Key Features
- **Node-based Implementation**: Both data structures use nodes that are chained together to maintain the order of elements.
- **Unit Tests**: The code includes unit tests using [Jest](https://jestjs.io/) to ensure the correct behavior of the `push`, `pop`, `enqueue`, and `dequeue` methods, as well as other utility functions like `peek` and `isEmpty`.

## Files
- `stack.js`: Implementation of the **Stack** data structure.
- `queue.js`: Implementation of the **Queue** data structure.
- `stack.test.js`: Jest tests for the **Stack** implementation.
- `queue.test.js`: Jest tests for the **Queue** implementation.

## Installation and Usage

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/stack-queue.git
   cd stack-queue

 2. Install dependencies (ensure you have Node.js and npm       installed):
    ```bash
    npm install

3. Run the unit tests using Jest:
   ```bash
   npm test
