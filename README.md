# This is a repository for a test project I have written.
The initial code contains a bug I am looking to resolve.
The project is based on Donny Wals "Using Core Data in a Modern SwiftUI Application".
I built the code Donny suggested as I liked the idea of have a single view for both Add and Edit.
All went well with the "speaker" code.
As my first extension to this code I added an "amplifier" entity with a 1 to 1 relationship with the "speaker" entity.
(My next extension would have been to make the amplifier entity have a 1 to many relationship with the speaker entity.)
I added some code to save the relationship between an amplifier and a speaker and the code crashed.
Apparently I am trying to "establish a relationship between objects in different context".
I do not know how to resolve this issue...

Any help would be most appreciated. Thank you.
