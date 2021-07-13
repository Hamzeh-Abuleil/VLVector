# VLVector
A better version of the Vector container in C++; the VLV is a generic vector that has most of the Vector functions and supports Iterators.
Unlike the normal Vector that dynamically store its elements which could be expensive in some cases, 
the VLV switches between stack and heap(dynamic storing) according to the capacity which allow us to recycle previous allocations at some point.
It allows us to do most of the actions on the vector in constant time(O(1)).

=============================
=      File description     =
=============================
*HighestStudentGrade.cpp:
  File that was made to test VLVector.

*VLVector.cpp:
  Actualy VLVector file.
  
