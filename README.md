The object purpose algorithm

by Alexandros Vassiliades, Nick Bassiliades

This algorithm given a household object that is part of the English Language, it will return its purpose. In other words it will return
the Actions and Activities that we can perform with it. 

Example: Hammer can be used for hit, break, kill, nail...

Also, in case that the algorithm does not return any Action or Activities,  it will search for similar for similar object and see what
they can do as an Activity of Action and recommend these as purpose of the initial object.

Example:   Thor_Hammer can be used for ------

           Thor_Hammer is similar to Hammer
           
           Hammer can be used for hit, break, kill, nail...
           
Anyone who wants to use it needs first to make a small change in the path existing in the Java Code file, by going to the source code 
and define the new path for the Onto.ttl. Then, he need to create a new jar and give the name of the new jar in the main python program. 
As this is the mechanism of the program that sends SPARQL queries to the VirtualHome.
