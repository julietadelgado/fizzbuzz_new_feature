# Practice Launch X

### New feature

This is a repository where we are going to add a new functionality to our refactoring code.

The new functionality, given a score, will return Fizz, Buzz, FizzBuzz or the score.

To achieve this we create the next static method 

```
	static applyValidationInNumber(number){
        if(isNaN(number))
            return "Error: The value is not a number"
        
        if(number % 3 == 0 && number % 5 == 0)
            return "FIZZBUZZ";
        else if(number % 3 == 0)
            return "FIZZ";
        else if(number % 5 == 0)
            return "BUZZ";
        else
            return number;
    }
```