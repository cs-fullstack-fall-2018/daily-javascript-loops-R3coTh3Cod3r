# Daily Question: JavaScript loops

Consider the following code:

```javascript
<script type="text/javascript">
  var theCounter = 15;
  while (theCounter > 0)
  {
    document.write("The count at this time is " + theCounter + "<br/>");
    theCounter--;
  }
</script>
```

### What is the expected result when you run this script in the browser?
A. There will be no visible output, but the script will count down to 0.

B. The script will output a countdown from 15 to 0 in the browser window.

C. The script will output a countdown from 15 to 1 in the browser window.

D. The script will output 15, then 1, because it will only write the first and last values of a ```while``` statement.

The answer would be "C" because the variable is telling the set "int" is equal to 15 which is then use in the while loop stating "theCounter" aka "15" is greater than 0 which is proven to be true in this case which is then created which the open curly brace using "document.write" as a form of printing the function giving a "statement" plus the variable plus "<br/>" (don't know the term) and is close off with the the variable decreasing its value because of the two negatives which lowers all the way to 1.
