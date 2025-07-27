# Jpeg2Png
Jpeg2Png is a *simple offline converter* for .jpg and .jpeg images to .png.

Features
🖼️ Supports .jpg and .jpeg input

📤 Outputs .png files

💻 Cross-platform (Windows / Linux / macOS)

🚫 No external dependencies (single .cpp file)

⚙️ No build system required (no CMake)

🔧 Requires only a C++17-compatible compiler (cl.exe, g++, clang++)

Build Instructions
On Linux/macOS:

g++ jpeg2png.cpp -std=c++17 -o jpeg2png
**OR**
clang++ jpeg2png.cpp -std=c++17 -o jpeg2png -Wall -Werror

On Windows (MSVC):

cl /std:c++17 jpeg2png.cpp

*Usage:*

jpeg2png <input> <output>
Example:

jpeg2png input_folder output_folder
All .jpg and .jpeg files in the input folder will be automatically converted and saved as out0.png, out1.png, out2.png, etc.
