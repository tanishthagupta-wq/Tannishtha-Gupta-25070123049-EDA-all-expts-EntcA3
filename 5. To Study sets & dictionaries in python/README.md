# Experiment 5: To Study Sets and Dictionaries in Python

## Aim
To study sets and dictionaries in Python, understand their properties, perform various operations, and apply them to solve practical problem statements.

---

## Objectives
* To learn the creation and properties of Sets (unordered, unique elements).
* To understand Set operations such as union, intersection, difference, and symmetric difference.
* To study the concept of `frozenset`.
* To learn the creation and manipulation of Dictionaries (key-value pairs).
* To solve real-world problems using sets and dictionaries.

---

## Theory & Code Demonstrations

### 1. Sets in Python
A set is a collection that is unordered and unindexed. Sets do not allow duplicate values.

**Key Features:**
* **Creation:** Defined using curly braces `{}`.
* **Unordered:** Items do not have a defined order.
* **No Duplicates:** Duplicate values are ignored. Note that `True` and `1` are considered duplicates.
* **Mixed Data Types:** Can contain strings, integers, and booleans.

# Adding items
mytodolist.add("study")

# Removing items
mytodolist.remove("sleep")

# Membership Testing
print("eat" in mytodolist) # Returns True
2. Set OperationsPython allows mathematical set operations.OperationSymbolDescriptionCode ExampleUnion``Combines elements from both setsIntersection&Keeps only common elementsA & BDifference-Elements in first set but not secondB - ASymmetric Difference^Elements in either set, but not bothA ^ B3. FrozensetA frozenset is an immutable version of a set. Once created, elements cannot be added or removed.Pythonx = frozenset([1, 2, 3, 4, 5])
4. Dictionaries in PythonDictionaries are used to store data values in key:value pairs. They are ordered (in recent versions), changeable, and do not allow duplicates.Basic Operations:Python# Creation
student = {
    "roll": "25070123049",
    "name": "Tannishtha",
    "branch": "entc"
}

# Accessing Items
print(student["name"])

# Adding/Updating Items
student["year"] = "second"
student["name"] = "tannishtha" # Updates existing key

# Removing Items
student.pop("branch")
Practical Problem StatementsSet ApplicationsUnion Event Participants: Used set() to filter out duplicate registrations from a list of participants.
Common Subjects: Used intersection (&) to find subjects chosen by all three students (Alice, Bob, Charlie).Club Membership: Used intersection and symmetric difference to find students in both clubs vs. only one club.Absent Students: Used set difference (-) to find students present in the "all students" list but missing from the "present" list.Remove Invalid Entries: Demonstrated the difference between .remove() (raises error if missing) and .discard() (does not raise error).Dictionary ApplicationsUpdate Product Price: Updated the price of a specific item ("Laptop") in a product dictionary.Search Student Marks: Created a search function where the user inputs a name to retrieve marks, handling cases where the student is not found.User Login Validation: Validated a username and password against a stored dictionary of credentials.Find Highest Marks: Used max() with a key argument to find the student with the highest marks in a dictionary.

## Conclusion
Thus, the concepts of sets and dictionaries in Python were studied. We learned how to handle unique collections using sets and key-value data structures using dictionaries, applying them to solve data filtering and retrieval problems.
