# 🟢 PART 1: PRACTICE QUESTIONS (50)

## 🔹 INSERT (1–10)

1[done]. Insert a student with name  age  course ,  gender 
2[done]. Insert multiple students at once
3[done]. Insert a student document without the `marks` field
4. Insert a student with `createdAt` date
5. Insert a student with a nested object (address)
6. Insert a student where `age` is a string instead of number
7. Try inserting a document with a duplicate `_id`
8. Insert a student with boolean field `isActive`
9. Insert a student with an array field `skills`
10. Insert a document with an extra field not defined in schema


🔹 FIND (11–20)
=============================

11. Find all students
12. Find students enrolled in **BCA** course
13. Find students whose age is greater than **18**
14. Find students from a specific city
15. Find students with name **Rahul**
16. Find students using both age and course conditions
17. Find students with marks less than **60**
18. Find students where `isActive` is true
19. Find the latest **5 inserted** students
20. Find only **one** student document

---

🔹 PROJECTION (21–28)
====================================

21. Display only `name` and `age`
22. Hide `_id` from the result
23. Show only the `course` field
24. Show only `name` and hide all other fields
25. Display both `marks` and `city`
26. Show only nested field `address.city`
27. Use `findOne()` with projection
28. Write an invalid projection and observe the error

🔹 UPDATE (29–38)
===========================
29. Update the age of a single student
30. Update course of multiple students
31. Increase marks by **10**
32. Update city where age is greater than **18**
33. Add a new field `graduated`
34. Remove an existing field
35. Update a nested field
36. Try updating without using `$set` and observe the result
37. Update multiple documents using a condition
38. Replace a document completely using update

 🔹 DELETE (39–44)
=================================

39. Delete a single student
40. Delete multiple students whose marks are less than **40**
41. Delete students based on city
42. Delete all students from the collection (⚠️ dangerous)
43. Observe the difference between `deleteOne` and `deleteMany`
44. Try deleting using an incorrect filter

🔹 OPERATORS (45–50)
===========================

45. Use `$gt` operator to filter students by age
46. Use `$lt` operator for filtering marks
47. Use `$in` operator to filter multiple courses
48. Use `$ne` operator in a query
49. Combine `$and` and `$or` operators
50. Use `$exists` operator to check field presence


======================================================================================================
 🔴 PART 2: INTERVIEW LEVEL QUESTIONS (30)

 🧠 CRUD + CORE (1–10)
 ===============================

1. Difference between `insertOne` and `insertMany`
2. `find()` vs `findOne()`
3. Difference between `updateOne` and `updateMany`
4. `deleteOne` vs `deleteMany`
5. Does MongoDB update overwrite documents by default?
6. Why is `$set` important in updates?
7. What is projection in MongoDB?
8. Why does MongoDB always include `_id` by default?
9. Is rollback possible after delete in MongoDB?
10. Are CRUD operations atomic in MongoDB?

 🧠 OPERATORS (11–20)
========================================

11. Difference between `$gt` and `$gte`
12. `$in` vs `$or` — when to use which?
13. When is `$and` operator optional?
14. Real-world use case of `$exists`
15. Use case of `$ne` operator
16. Difference between `$inc` and `$set`
17. What does `$unset` do?
18. When should `$regex` be used?
19. `$eq` vs direct comparison
20. How do operators work with indexes?

🧠 REAL-WORLD / MERN BASED (21–30)
================================================

21. How would you implement soft delete in MongoDB?
22. How do you ensure validation during update?
23. How is pagination implemented in MongoDB?
24. How do you apply sorting with find queries?
25. Would you allow delete operations in production?
26. How do you prevent direct database inserts?
27. How do you optimize find queries in production?
28. How do you handle partial updates in MongoDB?
29. How do you secure MongoDB operations in MERN apps?
30. Which MongoDB operations are most frequently used in real projects?
