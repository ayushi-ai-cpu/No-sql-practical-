# Hospital Patient Records Management System (MongoDB)

NoSQL Database Management project: a hospital patient records system built with MongoDB and the MongoDB shell (`mongosh`).

**Course:** NoSQL Database Management
**Mentor:** Mr. Harendra Singh Rajpoot
**Program:** BCA (Data Science & AI), 3rd Semester, Babu Banarasi Das University, Lucknow

## About
A dummy dataset of 50 patient records is stored in a `patients` collection inside the `HospitalDB` database. All names and details are fictional and used only for learning.

## Sample Document
~~~
{
  patient_id: "PAT001",
  name: "Aarav Pandey",
  age: 24,
  gender: "Male",
  blood_group: "AB+",
  city: "Patna",
  department: "Neurology",
  doctor: "Dr. N. Menon",
  admission_date: "2026-08-10",
  status: "Admitted",
  bill_amount: 57350,
  phone: "9870010001"
}
~~~

## Concepts Covered
- Database and collection creation
- CRUD: insertMany, find, updateOne, updateMany, deleteOne, deleteMany
- Query operators: $gt, $gte, $lt, $in, $or, $ne
- Projection, sort, skip and limit
- Aggregation: $group, $match, $sort, $project
- Indexing with createIndex
- Regular-expression search

## How to Run
1. Install MongoDB and mongosh.
2. Start mongosh.
3. Run the commands from `queries.js`.

## Files
- Project report (.docx)
- queries.js (all MongoDB commands)
