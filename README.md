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
