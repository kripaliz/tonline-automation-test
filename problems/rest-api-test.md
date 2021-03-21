# Rest API Test

### Solution details

Using the User api from the site https://gorest.co.in/, create automated API test for the below Acceptance Criteria



### Acceptance Criteria

#### Scenario 1: Create user

```markdown
Given I create a user with valid input details
When I get the details of the created user
Then the user details are the same as the input details
And the created_at field for the user contains the current date
```

#### Scenario 2: Update user

```markdown
Given I update an existing user with valid input details
When I get the details of the updated user
Then the user details are the same as the updated details
And the updated_at field for the user contains the current date
```
