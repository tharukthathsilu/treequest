# TreeQuest: A Flexible Tree Search Library for LLM Inference 🌳✨

![TreeQuest Logo](https://img.shields.io/badge/TreeQuest-Tree%20Search%20Library-brightgreen)  
[![Latest Release](https://img.shields.io/badge/Latest%20Release-Click%20Here-brightblue)](https://github.com/tharukthathsilu/treequest/releases)

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [API Documentation](#api-documentation)
- [Examples](#examples)
- [Contributing](#contributing)
- [License](#license)

## Overview

TreeQuest is a powerful tree search library designed for flexible API integration, particularly for large language model (LLM) inference-time scaling. This library enables developers to implement efficient search algorithms with ease, enhancing the performance of their applications. With TreeQuest, you can manage complex data structures while maintaining a simple interface.

## Features

- **Flexible API**: Customize the search process to fit your specific needs.
- **Efficient Algorithms**: Implement advanced tree search techniques for optimal performance.
- **Scalability**: Scale your applications effectively during inference time.
- **User-Friendly**: Designed for ease of use, even for those new to tree structures.
- **Extensive Documentation**: Comprehensive guides and examples to get you started quickly.

## Installation

To install TreeQuest, you can download the latest release from the [Releases section](https://github.com/tharukthathsilu/treequest/releases). Simply download the appropriate file for your platform, and follow the instructions to execute it.

```bash
# Example command to execute the downloaded file
./treequest-install.sh
```

## Usage

Using TreeQuest is straightforward. Here’s a basic example to get you started:

```python
from treequest import TreeSearch

# Initialize the tree search
search = TreeSearch()

# Define your search parameters
search.set_parameters(depth_limit=10, heuristic='best_first')

# Execute the search
result = search.execute(initial_state, goal_state)

print("Search Result:", result)
```

## API Documentation

TreeQuest provides a rich API for developers. Here are some key components:

### TreeSearch Class

- **`__init__(self)`**: Initializes the tree search instance.
- **`set_parameters(self, depth_limit, heuristic)`**: Sets the parameters for the search.
- **`execute(self, initial_state, goal_state)`**: Executes the search algorithm and returns the result.

For more detailed API documentation, refer to the [official documentation](https://github.com/tharukthathsilu/treequest/releases).

## Examples

Here are some practical examples to demonstrate the capabilities of TreeQuest:

### Example 1: Depth-First Search

```python
from treequest import TreeSearch

# Create a depth-first search instance
dfs = TreeSearch()

# Set parameters for depth-first search
dfs.set_parameters(depth_limit=5, heuristic='depth_first')

# Execute the search
result = dfs.execute(start_node, target_node)

print("Depth-First Search Result:", result)
```

### Example 2: Best-First Search

```python
from treequest import TreeSearch

# Create a best-first search instance
bfs = TreeSearch()

# Set parameters for best-first search
bfs.set_parameters(depth_limit=10, heuristic='best_first')

# Execute the search
result = bfs.execute(start_node, target_node)

print("Best-First Search Result:", result)
```

## Contributing

Contributions are welcome! If you want to contribute to TreeQuest, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes.
4. Write tests for your changes.
5. Submit a pull request.

Please ensure your code adheres to the existing style and includes appropriate documentation.

## License

TreeQuest is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

For more updates, check the [Releases section](https://github.com/tharukthathsilu/treequest/releases). 

Feel free to reach out with any questions or feedback. Happy coding!