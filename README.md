# Directory structure
```
build
  |
  com
    |
    ocajexam
           |
           tutorial
           |-GreetingsUniverse.class
           |
           |-planets
                |-Earth.class
                |-Mars.class
                |-Venus.class
src
  |
  com
    |
    ocajexam
	   |
	   tutorial
	   |-GreetingsUniverse.java
	   |
	   |-planets
		|-Earth.java
		|-Mars.java
		|-Venus.java
		
		
```

## Command to build the code that worked:
```
javac -cp src -d build src/com/ocajexam/tutorial/GreetingsUniverse.java
```

## Command to run that worked:
```
java -cp . com.ocajexam.tutorial.GreetingsUniverse
```
