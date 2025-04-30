# BTM-LLM-Prompt-Engineering

## Explanation
The idea of this project is to see how well different LLM's can analyse test cases
We want to find the best prompts, that produce the best results. 
The basic structure is below, you are encouraged to change the prompts as you see fit. log the results and streamline the prompts. 


## Test Case Generation Steps

1. Run Project Initialization Prompt
   - Sets up the initial project structure
   - Establishes baseline configuration

2. Generate Test Case Table
   - Add one specification at a time
   - Use Test Case Table prompt
   - Include test ID, description, prerequisites, and expected results
   - Store results in testcase.html

3. Generate Detailed Test Case Explanation
   - Use Detailed Test Case Explanation prompt
   - Produces comprehensive test case documentation
   - Includes prerequisites, steps, and expected outcomes
   - Store results in description.html

4. Generate Test Properties Explanation
   - Use Test Properties Explanation prompt
   - Documents test complexity, risk level, and business impact
   - Includes technical challenges and dependencies
   - Store results in property.html

5. Generate Requirements Table
   - Use Requirements Table prompt
   - Maps functional and non-functional requirements
   - Links requirements to business needs
   - Store results in requirements.html

6. Generate 
   - Use Traceability Matrix prompt
   - Creates mapping between requirements and test cases
   - Ensures complete coverage of requirements
   - Store results in tracematrix.html

7. Generate Coverage Report
   - Use Coverage Report prompt
   - Analyzes test coverage across requirements
   - Identifies covered and uncovered areas
   - Store results in coverage.html

8. Generate Gap Analysis
   - Use Gap Analysis prompt
   - Identifies missing test cases and coverage gaps
   - Suggests additional test scenarios
   - Store results in gap.html

## Additionally
Add the results from each stage of prompting to the corresponding .html file
in the appropriate folder (given your LLM). This helps track and compare
results across different LLM models.
