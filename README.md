# BloodHound's Day Off!

You know what I love more than automation? Understanding. That is why I've started this project. I love using tools like BloodHound and PowerView when I'm doing CTFs, but I've always wondered what would happen if I wasn't allowed to use BloodHound or if I wasn't able to use PowerView?

What would I do if I had to connect to LDAP and manually discover exploitable configurations or sensitive information? I know the basics of using LDAP and I'm sure there are a plethora of prebuilt queries to identify objects with Constrained Delegation or GenericAll, however what if I had taken the time to learn how to develop these queries myself?

So I decided to take the time now to not just learn more about LDAP and these attacks, but to create a tool custom to myself that automates some of the "checklist" things that I look for in BloodHound.

"Life moves pretty fast. If you don't stop and look around once in a while, you could miss it."
\-Ferris Bueller's Day Off

It's time to give BloodHound a day off.

# Features

This project will be in continous development as I come up with new ideas for attacks to discover and methods of automating some work. Comments and suggestions are always appreciated!

Currently Working On:
 - CLI Interface
 - Interacting with LDAP
 - Listing Users, Groups, and Computers
 - Searching properties like descriptions for sensitive information
