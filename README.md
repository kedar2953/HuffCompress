
---

# HuffCompress

HuffCompress is a C++ project that implements the Huffman coding algorithm for compressing and decompressing text files. Utilizing Object-Oriented Programming (OOP) and file handling concepts, this project efficiently reduces file sizes by approximately 50%.

## Features

- **Compression**: Compresses text files using the Huffman coding algorithm.
- **Decompression**: Decompresses Huffman encoded files back to their original text format.
- **Efficient Implementation**: Reduces file size by around 50% using advanced C++ concepts.

## Technologies Used

- **C++**
- **Object-Oriented Programming (OOP)**
- **File Handling**

## Project Structure

- `encode.cpp`: Handles the encoding (compression) process.
- `decode.cpp`: Handles the decoding (decompression) process.
- `huffman.cpp`: Contains the core Huffman coding algorithm and related functions.
- `huffman.h`: Header file for `huffman.cpp`.

## Getting Started

### Prerequisites

Ensure you have the following installed:

- g++ (GNU Compiler Collection)

### Running the Project

#### Encoding

To compress a text file:

1. Compile the encoding program:
    ```sh
    g++ encode.cpp huffman.cpp -o encode
    ```

2. Run the encoding program:
    ```sh
    ./encode input.txt compressedFile.huf
    ```

Replace `input.txt` with the path to the text file you want to compress, and `compressedFile.huf` with the desired name for the compressed file.

#### Decoding

To decompress a Huffman encoded file:

1. Compile the decoding program:
    ```sh
    g++ decode.cpp huffman.cpp -o decode
    ```

2. Run the decoding program:
    ```sh
    ./decode compressedFile.huf output.txt
    ```

Replace `compressedFile.huf` with the path to the Huffman encoded file you want to decompress, and `output.txt` with the desired name for the decompressed text file.

## Contributions

Contributions are welcome! Please fork the repository and submit a pull request for any improvements or bug fixes.

---

