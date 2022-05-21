# command line arguments
   - Version \
     **bal version**
   - Home \
     **bal home**
   - Project \
     **bal new 'Project name'**
   - module\
     **bal add 'module name'**
   - build\
     **bal build 'module name'**
   - run  \
     **bal.bat run "c:\Users\Belkis Vasquez\TestProjectBallerina"**
   - Clean cache \
     **bal clean**
   - Test \
     **bal test 'module name'**
   - Help \
     **bal help** (It shows the commands and what we can do with them)
    
# Standard Streams: 
   - **Standard Input** \
      io:readln()
   - **Standard Output**  \
      io:println() \
      .StandardOutput.ReadToEnd(); 
   - **Standard Error** \
     StandardError.ReadToEnd \
     
     string input = io:readln("Enter your input: ");
     
    int|error number = int:fromString(input);
    if(number is error) {
        io:println("Error occurred in conversion");
    } else {
        // Fine
    }
# environment variables
## File I/O

## Network I/O
 
