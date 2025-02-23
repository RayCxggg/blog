---
title: "Vectors, Maps, and Strings"
date: "2025-02-23T00:00:00+08:00"
summary: "Some notes about leetcode and C++."
description: "Hello!"
toc: false
readTime: false
autonumber: true
math: true
tags: ["database", "java"]
showTags: false
hideBackToTop: true
hidePagination: true
---

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

// sum
int totalSum = accumulate(numbers.begin(), numbers.end(), 0);
```


### String

### Unordered_map

`unordered_map` is a type of associative container in the C++ Standard Library used to store key-value pairs.