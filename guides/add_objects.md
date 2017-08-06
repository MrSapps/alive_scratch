1. Create a script for the new object in scripts, i.e "your_object.nut".
2. In object_factory.nut add the type of your object to ObjectTypesAe and ObjectTypesAo depending on which games it can be "spawned" from.
This ID number relates to the number stored in the "Path" / level data. You can usually find it from the XML in "Pauls level editor".
3. Now when this object ID is seen in each game your object will be created.
4. In your script from 1. create a class that is copied from mine.nut as a base. Rename the class to match the name of the object. And then update the constructor to read the required properties from the object.
This list of properties can be found in the "Pauls level editor" XML files.
