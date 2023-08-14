In this hypothetical world, I will be talking about a project in C++.

For C++, there are various accepted notations (for example for loops and if statements) but it is always a good practice to use some linting for consistence. One possible linting tool for C++ is clang-tidy.


When it coems to testing, I would go with Catch.

Regarding building, I would honestly go with gcc or g++. The most important aspect is that the compiler version matches the actual code written. I would also consider the use of some memory leak detection tool as C++ does not have a garbage collector.

When setting up a CI, there are multiple platforms that can be used. The ones I have worked with personally are Azure DevOps and JIRA. Both tools are very powerful and can do everything done by Jenkins and Github Actions. The only problem is that they are not open-source.

Finally, I believe that nowadays it is pointless to have anything self-hosted. There is an abundance of cloud providers and all of them have ready-made environments for virtually every type of application and consequently it would be much simpler to use such environments instead of building your own environment locally.