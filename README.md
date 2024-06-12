
# MD5 Algorithm Implementation In C++

This repository contains a C++ implementation of the MD5 hashing algorithm, designed to serve as a golden model for testing HDL implementations for a computer assignment in the Digital Logic Design course at the University of Tehran.

## Description

The MD5 algorithm is a widely used cryptographic hash function that produces a 128-bit (16-byte) hash value, typically rendered as a 32-character hexadecimal number. This implementation provides a straightforward way to generate MD5 hashes for given inputs and convert them to a hexadecimal format suitable for memory initialization files used in HDL testing.

## Features

- Complete implementation of the MD5 algorithm in C++.
- Generates preprocessed strings for MD5 and converts them to hexadecimal format.
- Serves as a golden model for testing HDL implementations.

## Installation

To compile the code, you will need a C++ compiler. You can use the provided `makefile` for easy compilation.

1. **Clone the repository**:
   ```sh
   git clone https://github.com/mohasnik/MD5-Algorithm-Implementation.git
   cd MD5-Algorithm-Implementation
   ```

2. **Compile the code**:
   ```sh
   make
   ```

## Usage

After compilation, the main program `MD5` will be created. You can use this program to generate the MD5 hash and the preprocessed hexadecimal memory initialization file.

1. **Run the main program**:
   ```sh
   ./MD5
   ```

2. **Provide input**:
   - Enter any string shorter than 448 bytes.
   
3. **Output**:
   - The MD5 hash result will be displayed.
   - The preprocessed hexadecimal memory initialization file will be created in the output directory.

## Directory Structure

- `src/`: Contains the source files for the MD5 algorithm implementation.
- `makefile`: Script to compile the code.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
