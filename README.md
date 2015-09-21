# NFL Player Stats

## Description
Create classes to store stats for each football position


## Objectives

### Learning Objectives

After completing this assignment, you should…

* JavaScript classes and constructors


### Performance Objectives

After completing this assignment, you be able to effectively use

* JavaScript functions as constructors
* The `new` keyword.



## Details

### Deliverables

* A repo containing at least:
  * `scripts/main.js`
  * `index.html`

### Requirements

* No ESLint warnings or errors


## Normal Mode
Using JavaScript functions create classes for each of the following football positions. Each position lists the methods and properties that should belong to the class below. For each of the three positions listed, create at least two player variables that instantiate each class. The `index.html` page should link in your `main.js` script.

#### Quarterback:
##### Properties
* name
* team
* attempts
* completions
* yards
* touchdowns
* interceptions
* sacks
* longestCompletion
##### Methods
* completionPercentage()
* yardsPerAttempt()
* addAttempt(type, yards)
	* type: 'complete', 'incomplete', 'touchdown', 'interception', 'sack'
	* yards: number representing the number of passing yards

#### Rushing:
##### Properties
* name
* team
* attempts
* yards
* over20 (number of carries over 20 yards)
* touchdowns
* firstDowns
* fumbles
* longestRush
##### Methods
* yardsPerAttempt()
* addAttempt(type, yards)
	* type: 'fumble', 'first down', 'touchdown'
	* yards: number representing the number of yards carried

#### Kicking:
##### Properties
* name
* team
* attempts
* made
* longestFieldGoal
##### Methods
* fieldGoalPercentage()
* addAttempt(type, yards)
	* type: 'made' or 'missed'
	* yards: number representing the number of yards kicked
            
## Hard Mode
Update the `index.html` page to allow you to add attempts for each of your player variables. Display that players stats in a table and update the players stats as a new attempt is recorded.
            


## Notes

Notes go here...

## Additional Resources

* Read []()
