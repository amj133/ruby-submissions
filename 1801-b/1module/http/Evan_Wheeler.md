### Repo: https://github.com/anon0mys/HTTP-yeah-you-know-me

### Assessed By: Brian 

### Notes:

* Really cool use of Object.const_get in your assign_endpoint method. My only suggestion would be to try to make it more readable. For instance, instead of a one-liner, you could first say `endpoint_class = Object.const_get(@paths[path])` and then say `endpoint_class.new(request)`
* Great job going above and beyond with the directory structure
* Good use of mocks and fixtures
* Uses Rakefile to do more than just run the tests

## Evaluation Rubric

The project will be assessed with the following guidelines:

* 4: Above expectations
* 3: Meets expectations
* 2: Below expectations
* 1: Well-below expectations

### 1. Ruby Syntax & Style: 4

- [x] Applies appropriate attribute encapsulation  
- [x] Developer creates instance and local variables appropriately
- [x] Naming follows convention (is idiomatic)
- [x] Ruby methods used are logical and readable  
- [x] Developer implements best-choice enumerable methods
- [x] Code is indented properly
- [x] Code does not exceed 80 characters per line
- [x] A directory/file structure provides basic organization via lib/ and/or /test

### 2. Breaking Logic into Components: 4

- [x] Code is effectively broken into methods & classes
- [x] Developer writes methods less than 7 lines
- [x] No more than 3 methods break the principle of SRP

### 3. Test-Driven Development: 4

- [x] Each method is tested  
- [x] Functionality is accurately covered
- [x] Tests implement Ruby syntax & style   
- [x] Balances unit and integration tests
- [x] Evidence of edge cases testing
- [x] Test Coverage metrics are present (SimpleCov)
- [x] A test RakeTask is implemented

### 4. Functionality: 3

- [x] Application meets all requirements (extension not req'd)

### 5. Version Control: 3

- [x] Developer commits at a pace of at least 1 commit per hour
- [x] Developer implements branching and PRs
- [x] The final submitted version is merged into master
