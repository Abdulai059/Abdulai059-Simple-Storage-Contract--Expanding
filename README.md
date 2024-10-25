# Hackerboost Project Week 2: Expanding SimpleStorage with Solidity Concepts

This project is part of the Hackerboost program, Week 2, and it builds upon a basic `SimpleStorage` contract. The contract demonstrates key Solidity concepts, such as data types, functions, visibility levels, dynamic arrays, structs, and enums. It allows interaction with users by storing and retrieving their favorite numbers and managing contract states.

## Features

1. **Favorite Number Storage:**
   - Stores a single favorite number and supports multiple favorite numbers via a dynamic array.

2. **Structs and Data Storage:**
   - Implements a `Person` struct to store a person's name and favorite number, with functions to add and retrieve people’s data.

3. **Contract State Management:**
   - Uses an `enum` to manage contract states (Active/Inactive) and provides functions to activate or deactivate the contract.

4. **Visibility Levels:**
   - Demonstrates various visibility levels (`public`, `private`, `internal`, `external`) using different function access levels.

5. **Mathematical Operations:**
   - Includes a function that calculates the sum of all numbers from 1 to the stored favorite number.

## Challenges Faced & Resolutions

1. **Visibility Levels Understanding:**
   - Initially, it was challenging to differentiate between visibility levels, especially `internal` and `external`. To resolve this, additional research and tests were conducted to fully grasp how these functions behave within and outside of the contract.

2. **Handling Dynamic Arrays:**
   - Managing dynamic arrays for favorite numbers and structs required careful handling of memory and storage. Using `.push()` and proper function signatures helped streamline this process.

3. **Enum Implementation:**
   - Implementing the `enum` for contract states was tricky, especially when switching between states. Careful attention to state transitions ensured smooth functionality.

