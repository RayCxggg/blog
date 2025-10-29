---
title: "Relearning C++"
date: "2025-02-23T00:00:00+08:00"
summary: "Some notes about C++ and Leetcode."
description: ""
toc: false
readTime: false
autonumber: true
math: true
tags: ["database", "java"]
showTags: false
# hideBackToTop: true
hidePagination: true
hideLanguageButtons: true
---

Lately, I've been using LeetCode to prepare for an internship and was surprised by how much the C++ standard has evolved since I studied it as an undergraduate. It's fascinating to revisit C++ and explore the new features and improvements.

## Data Structures

### Vector

`vector` is a sequence container in the C++ Standard Library that provides dynamic array functionality.

```cpp
#include <vector>
using namespace std;
vector<int> numbers = {1, 2, 3};

// as function parameter
vector<int> twoSum(vector<int>& nums, int target) {};

// access element
cout << "The first element of the vector is:" << numbers[0] << endl;

// add element
numbers.push_back(1);
numbers.push_back("hello");

// remove element 
numbers.pop_back();

// used in loops
for (int num : numbers) {};

// size
int size = numbers.size();

// check if it's empty
bool isEmpty = numbers.empty();

// sum
int totalSum = accumulate(numbers.begin(), numbers.end(), 0);
```

### String

```cpp
#include <string>
using namespace std;
string str = "I love engineering."

// length
int len = str.length();

// used in loops
for (char c : str) {};

// find substr
bool isSubstr = str.find("love")

// return the starting index of the substr
int SubstrIdx = str.find("love")

// extract a substring
string substr = str.substr(pos, len)

// check if it's empty
bool isEmpty = str.empty();

```

### Unordered_map

`unordered_map` is a type of associative container in the C++ Standard Library used to store key-value pairs.

```cpp
#include <unordered_map>
using namespace std;
unordered_map<char, int> myMap = {
            {'I', 1},
            {'V', 5}
        };

// Checking if a Key Exists:
if (myMap.find(3) != myMap.end()) {
    // Key 3 exists
}
```