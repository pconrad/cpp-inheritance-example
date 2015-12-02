# cpp-inheritance-example
Example of Inheritance in C++


<pre>
               Person
                 |
                 v
              Student
              /     \
OffCampusStudent    OnCampusStudent
</pre>

<pre>
Person has std::string name
Student inherits from Person and also has int perm
OffCampusStudent inherits from Student and also has std::string streetAddress
OnCampusStudent inherits from Student and also has int swipesLeft (for dining hall plan)
</pre>

Now we write the code.

# gtest-hello-world: Google Test Hello World Example

In the subdirectory gtest-hello-world we have a short example of using GTest as a TDD framework.

In the course reader, there are more examples of using this framework.   This framework is available on the CSIL machines, and even if future courses don't *require* you to use TDD, you are encouraged to adopt the practice on your own.  Break your CS130A assignments down into smaller units that you can test, write your own tests, and test your code in small pieces BEFORE putting it together into the pieces that form the assignment you were given.  You'll likely have more success, get done faster, and will have valuable experience to talk about with potential internship and full-time job prospects.

# inheritance-example

The subdirectory inheritance example shows the example code.

