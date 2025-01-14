# MongoDB $inc operator with nested fields
This example demonstrates a common error when using the `$inc` operator in MongoDB to update nested fields. Incorrect dot notation can prevent the update from functioning correctly. 

**Bug:** The original code attempts to increment a nested field ('nested.field') using incorrect dot notation. 

**Solution:** The solution corrects the dot notation to accurately target the nested field for incrementation.