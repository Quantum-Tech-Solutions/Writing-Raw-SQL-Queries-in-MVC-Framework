##In relational database terms, an inner join produces a result set in which each element of the first collection appears one time for every matching element in the second collection. If an element in the first collection has no matching elements, it does not appear in the result set. The Join method, which is called by the join clause in C#, implements an inner join.

This article shows you how to perform four variations of an inner join:

####A simple inner join that correlates elements from two data sources based on a simple key.

####An inner join that correlates elements from two data sources based on a composite key. A composite key, which is a key that consists of more than one value, enables you to correlate elements based on more than one property.

####A multiple join in which successive join operations are appended to each other.

####An inner join that is implemented by using a group join.

Example - Simple key join
The following example creates two collections that contain objects of two user-defined types, Person and Pet. The query uses the join clause in C# to match Person objects with Pet objects whose Owner is that Person. The select clause in C# defines how the resulting objects will look. In this example the resulting objects are anonymous types that consist of the owner's first name and the pet's name.

<script src="https://gist.github.com/udaykumar-8329/b1e8fcf0cc35f8c4ee2dacd301dbab16.js"></script>
