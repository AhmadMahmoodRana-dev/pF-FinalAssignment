# Programming Fundamentals – Assignment 3 (Superior University)

**Instructor:** Umar Khalil
**Course:** Programming Fundamentals
**Language:** C++

This repository contains all C++ programs written for Assignment 3 (Parts 1–4)
and the accompanying theory practice programs, organized into a single,
compilable project.

## 📁 Repository Structure

```
PF-Assignment-3/
├── Part-1/                         # Assignment 3 – Part 1 (functions, arrays, strings)
│   ├── 01_average_array.cpp
│   ├── 02_min_max_array.cpp
│   ├── 03_power_function.cpp
│   ├── 04_voltage_calculator.cpp
│   ├── 05_cricket_team_search.cpp
│   └── 06_word_length.cpp
├── Part-2/                         # Assignment 3 – Part 2 (arrays, strings, sorting)
│   ├── 01_second_highest_lowest.cpp
│   ├── 02_sum_array.cpp
│   ├── 03_temperature_converter.cpp
│   ├── 04_leap_year.cpp
│   ├── 05_vowel_counter.cpp
│   └── 06_alphabetical_sorter.cpp
├── Part-3/                         # Assignment 3 – Part 3 (arrays, 2D arrays, functions)
│   ├── 01_count_even_odd.cpp
│   ├── 02_display_2d_array.cpp
│   ├── 03_gcd.cpp
│   ├── 04_batting_strike_rate.cpp
│   ├── 05_string_length.cpp
│   └── 06_copy_word.cpp
├── Part-4/                         # Assignment 3 – Part 4 (2D arrays, function overloading)
│   ├── 01_sum_2d_array.cpp
│   ├── 02_subtract_2d_array.cpp
│   ├── 03_area_calculator.cpp
│   ├── 04_bowling_average.cpp
│   ├── 05_vertical_word_printer.cpp
│   └── 06_reverse_word.cpp
└── Theory-Practice-Programs/       # If-else / logical operator practice (20 questions)
    ├── 01_check_y_equals_10.cpp
    ├── 02_temperature_validator.cpp
    ├── ...
    └── 20_time_unit_converter.cpp
```

Each `.cpp` file is a standalone, compilable program with its own `main()`
function, corresponding to one problem from the original assignment sheets.

## 📋 Contents Overview

| Folder | Topics Covered |
|---|---|
| `Part-1` | Arrays, functions, custom power function, char arrays, search |
| `Part-2` | Arrays (2nd highest/lowest, sum), strings, leap year, bubble sort |
| `Part-3` | Arrays, 2D arrays, GCD (Euclidean algorithm), char array functions |
| `Part-4` | 2D arrays, function overloading, char array manipulation (reverse, print vertical) |
| `Theory-Practice-Programs` | `if / else if`, comparison & logical operators, loops |

## 🛠️ How to Compile & Run

Each file can be compiled independently using `g++`:

```bash
g++ Part-1/01_average_array.cpp -o average_array
./average_array
```

Or compile every program at once (Linux/macOS):

```bash
find . -name "*.cpp" -exec sh -c 'g++ "$1" -o "${1%.cpp}.out"' _ {} \;
```

## 📝 Notes

- All variables follow **camelCase** naming convention as required by the
  assignment instructions.
- Each program was written and tested individually; logic and structure
  match the original assignment submissions, with formatting cleaned up
  for readability.
- These programs are course assignment submissions, intended for
  personal reference and portfolio purposes.

## 📄 License

This repository is shared for educational and portfolio purposes.
