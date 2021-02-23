# Day 2
__02/23/21__

## What is the difference between a primary key and a foreign key?

A primary key is the key by which the data in the table will most commonly be referenced. This is typically the id of that item as it is a convenient unique property to search by. The foreign key is similar, in that it defines a value by which to search forn the children of a parent that have been given an id in order to define a relationship between the two data sets. The foreign key essentially takes the place of virtuals in Mongoose/Mongodb.

## What is an Alias?

An alias is a second name that can be given to a binding. Typically much shorter than the actual name, like a single character. This can make it much faster/easier to write as you would only need a single character to reference the binding instead of writing out it's entire name. If done right it's supposed to even maintain readability, but at a glance it seems like the opposite. While it is reasonable to understand a single character references this conceptual list, quickly reading and trying to understand the code all of the single characters make it more convoluted, at least in my opinion.

## Demonstrate how you would query a join statement that would get all of a doctors patients from the collection on the codeworks classroom.

```
internal IEnumerable<Patient> GetPatientsByDoctor(int id)
{
string sql = @"
SELECT p.*,
md.id as PatDocId
FROM doctors md
JOIN patients p ON p.id = md.patientId
WHERE doctorId = @id;";
return _db.Query<DoctorPatientViewModel>(sql, new { id });
}
```
- So it all starts with simply declaring the method, output type, and parameters.
- Then because we use dapper to sanitize our entries, it is more readable to bind the actual request before injecting.
- My logical understanding starts with the FROM statement, here we reference the table that holds the relationship.
- It then bounces down to the WHERE that specifies which collection is making the request. 
  - We have a doctor, and we want their patients, so we give it the doctor id, and pull all the relationships related to that particular doctor.
- Next we hit the JOIN statement. This goes to the patients table and pulls every patient who's Id is in the same relationship with the doctor's id.
  - It's here where it also references the SELECT line, that's what tells it to find every patient.
  - This is also what gives us the information by somehow appending the information it recieves to the relationship table that it gives us.
- Finally (for the injection) we attatch the relationship id to a child class of the original model who's only job is holding this property.
- Last but not least we make the dapper query, we tell it to give us the child class I mentioned before, and give it the string we just made and the doctor's id so it can actually make the request. 
## Afternoon Challenge

[https://github.com/Chase16Rogers/contract-jobs](https://github.com/Chase16Rogers/contract-jobs)