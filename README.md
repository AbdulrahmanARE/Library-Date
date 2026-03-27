# libraryDate (C++)

**A Lightweight C++ Date Manipulation Library**  
This project is a custom C++ library designed to handle and simplify date operations using Object-Oriented Programming concepts, without relying heavily on built-in date libraries.

---

## Features

### Date Creation & Validation
- Create date objects using different constructors
- Validate dates (day, month, year correctness)
- Check for leap years

### Date Calculations
- Add or subtract days, months, and years
- Increase or decrease dates by specific values
- Calculate the difference between two dates
- Get number of days in a month or year

### Date Comparison
- Compare two dates (before, after, equal)
- Check if a date falls between two dates
- Calculate age or duration between dates

### Calendar & Utilities
- Get day of the week for a given date
- Generate monthly and yearly calendars
- Check if a day is a weekend or business day
- Count business days between two dates

---

## Purpose
This project is designed to practice and improve skills in:
- C++ Class design  
- Object-Oriented Programming (OOP)  
- Date logic implementation  
- Problem-solving and algorithmic thinking  

---

## How to Run
1. Download `clsDate.h` and include it in your C++ project.  
2. Use the `clsDate` class by creating an object or calling its static methods.  
3. Refer to your main/test file for examples of all available functions.  
4. Compile your project using any C++ compiler (e.g., g++, Visual Studio).  

---

## Sample Usage

```cpp
#include <iostream>
#include "clsDate.h"
using namespace std;

int main() {
    // Using Object Methods
    clsDate Date1(1, 1, 2024);
    Date1.IncreaseDateByOneDay();
    cout << Date1.Day << "/" << Date1.Month << "/" << Date1.Year << endl;

    // Using Static Methods
    cout << clsDate::IsLeapYear(2024) << endl; // Output: 1 (true)

    return 0;
}
```

---

## Author
**Abdulrahman Ramadan** – A custom C++ library for efficient date handling and manipulation.
