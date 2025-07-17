# 🔍 Linear Search in C++

A simple C++ program that implements the **Linear Search** algorithm. This is a beginner-friendly example useful for understanding basic array traversal and search logic.

---

## 🚀 Features

- Accepts user input for array size and elements
- Accepts a search key
- Returns the **index** of the key if found
- Returns `-1` if the key is not found

---

## 💡 How It Works

The `linearSearch()` function checks each element in the array:

```cpp
for (int i = 0; i < n; i++) {
    if (arr[i] == key)
        return i;
}
return -1;
If the key is found, it returns the index of the element. If not, it returns -1.

📥 Input Format
First line: Number of elements n

Second line: n space-separated integers

Third line: Integer key to search

🖥️ Sample Run
makefile
Copy
Edit
Input:
5
10 20 30 40 50
30

Output:
2
🔧 Compilation & Run
bash
Copy
Edit
g++ -o linear_search linear_search.cpp
./linear_search
📚 Educational Purpose
This program is ideal for:

Learning basic search algorithms

Understanding linear time complexity (O(n))

Practicing input/output and arrays in C++

📝 License
Free to use for educational and personal learning purposes.
