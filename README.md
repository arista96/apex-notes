# apex-notes
Salesforce Apex

## Data Types and Variables
String songTitle = 'We Are The World';

Sample https://www.apexsandbox.io/ problem.

### Problem:
Given a person's age, return true if the person is a teenager (age 13 - 19).
isTeenager(5) = false
isTeenager(15) = true

###Answer:
```apex
public Boolean isTeenager(Integer age) {
    //code here
    if (age >= 13 && age <= 19) {
        return true;
    } else {
        return false;
    }
}
```