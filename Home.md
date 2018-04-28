Welcome to the Java-Memory-Analysis wiki!


minimise memeory:

lazy allocation of collection
-dnt create something until u need to put something into it

dnt create colleciton in single object
-just store the object itself

size collections correctly
only 2 size put it correctly

HashMap mhy = new HashMap(2);

avoid expansion of large collections due to 2x algorithm
32 MB used to store 17MB of data

colloections do not shrink once expanded
may be reallcoation if collections uses drops


