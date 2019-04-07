@@ -47,8 +47,10 @@ Gradle example:
Snapshot versions are useful during development and JitPack provides two ways to get them. You can specify a version for your dependency as:

 - commit hash

 - `-SNAPSHOT`

 - `-SNAPSHOT` 

 - `branch-SNAPSHOT`

`-SNAPSHOT` will build the latest commit on the master branch. It depends on your build tool how often it checks for new snapshot versions. For example, in Gradle add these lines to check for new versions on every build:    
