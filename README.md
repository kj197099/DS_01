
# Inventory Management System

# Project Overview
This *Inventory Management System* in C++ is designed to handle inventory operations efficiently for a small shop. The system allows users to perform essential operations, including adding, removing, searching, and displaying items in the inventory. Using linked lists as the primary data structure, this application dynamically manages inventory data, providing easy access and manipulation without predefined size limits.

# Features
- Add Item: Allows the addition of new items by entering details like ID, name, quantity, and price. Items are stored dynamically using a linked list.
- Remove Item: Removes items from the inventory based on item ID, with memory released upon deletion.
- Search Item: Searches for an item by its ID and displays its details if found.
- Display Inventory: Lists all items in the inventory, giving an overview of current stock.
- Exit: Closes the program and frees resources safely.

# Techniques and Design
- Object-Oriented Programming: Classes are used to modularize the code, improving readability and reusability.
- Linked List Data Structure: Enables dynamic storage of items, allowing easy addition, removal, and search operations.
- Memory Efficiency: Linked lists allocate only the required memory, adjusting as items are added or removed.
- Efficient Data Management: Operations are optimized to handle frequent updates to item availability and quantity smoothly.

# System Requirements
- Operating System: Windows 10 or Linux
- Processor:Intel Core i3 (minimum), Core i5 or higher recommended
- RAM: 4 GB (minimum), 8 GB recommended
- Development Environment: Any C++ IDE (e.g., Visual Studio, Code::Blocks) or Visual Studio Code with GCC or Microsoft C++ Compiler

# Menu and Operations
1. Add Item:
   Input item details, which are then stored in a linked list.
2. Remove Item:
   Enter the item ID to remove it from the inventory.
3. Search Item:
   Search for an item by ID to view its details.
4. Display Inventory:
   Display all items and their details currently in the inventory.
5. Exit:
   Close the application and free up resources.

# Process Flow
- Adding a New Item:Creates a new node with item details, appending it to the linked list.
- Removing an Item:Locates the item by ID, removes it from the list, and releases memory.
- Searching for an Item: Traverses the list to find and display the specified item by ID.
- Displaying All Items: Iterates through the list, showing each item’s details.

# Output
- Add Item: Confirms item addition with details.
- Remove Item:Confirms successful or unsuccessful removal.
- Search Item:Displays item details if found or shows a "not found" message.
- Display Inventory: Outputs a structured list of all inventory items.

---
