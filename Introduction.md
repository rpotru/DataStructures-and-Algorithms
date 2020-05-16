# Data Structures

A data structure is a concept we use to describe ways to organize and store types of data. 

Data can be stored in various primitive types as listed below.

- Boolean
- Character
- Integer
- Floating-point number

Data in multitude can be stored in containers such as Array, hash tables etc. We are familiar with Arrays where items are placed in sequential order and items can be retrieved using the index.
Hash tables store data in key,value pairs. Hash tables are also called in different terms such as hash, hashmap, dictionary,associative array or map.

Array Examples:
  - array_int_example = [3,8,21,0,99,101,5]     # array of integer type
  - array_str_example = [""david", "Mike", "Peter", "Jessie"]   # array of string type  
  
Hash table examples:
  - dict_person = ['Name' : 'Mike', 'Age' : '32' , 'City' : 'Boston']

array_int_example[1] = 8
array_str_example[3] = Jessie
dict_person['Name'] = Mike
  

# Algorithms 

There are 3 types of Algorithms.
 - Divide and Conquer
 - Greedy
 - Dynamic

## 1. Divide-and-conquer algorithms
They take a large problem, divide it into many smaller problems, and then combine the results to obtain a solution.

For example, you have an array with 1 million integers. It would take lot of time to traverse across the whole array. What we can do is to be able to divide the main array in sub-arrays like 20 of them each with 50k integers and run the computation in parallel to achieve the result in quick time.

## 2. Greedy algorithms
Greedy algorithms will do what is best at the point in time at which the algorithm is executing, whether it has the best overall impact to solve the problem at hand or not. 
Some problems require this type of algorithm to solve. 

One of the most popular is the traveling salesperson problem. This problem is one of the most important in computer science. You choose the initial city and then select the closest and then move on from there to be able to travel all cities with minimum distance.

## 3. Dynamic
With the dynamic approach, we make decisions catering for future implications while considering the past results.

# Big O Notation

Big O notation is heavily used while asessing the algorithm. It describes the worst-case running time of our algorithm.
There are many ways to describe Big O runtime, but here are some types of Big O run times you will come across:
- O(1): The algorithm has a constant execution time, which is independent of the input size.
- O(n): The algorithm is linear, and performance grows in proportion to the size of the input data.
- O(log n): The algorithm is logarithmic; as time increases linearly, then n will go up exponentially. This means that more elements will take less time.
- O(n log n): The algorithm is logarithmic multiplied by some variable n.
- O(n^2): The algorithm is quadratic, and the running time is proportional to the square of the input.
- O(2^n): The algorithm is exponential; execution time doubles with the addition of each new element.
- O(n!): The algorithm is factorial and will execute in n factorial time for every new operation that is performed.
