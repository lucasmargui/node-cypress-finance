
# Getting Start

Initialize a Node project

```bash
npm init –yes
```

Install Cypress

```bash
npm install -D cypress@12.5.0
```

Open Cypress

```bash
npx cypress open
```


## Testing Finance


### Create a new finances.cy.js file

<div align="center">

  <img src="https://github.com/lucasmargui/Node_Cypress_Finance/assets/157809964/8a41cc79-dbd5-48be-8806-77a13bae6330" style="width:50%">

 <img src="https://github.com/lucasmargui/Node_Cypress_Finance/assets/157809964/e8817b7f-d432-4282-86ac-4f027e00c670" style="width:70%">
  


</div>


### Select


Select an element on the screen we want to interact with using a feature called CSS selector


<div align="center">

 <img src="https://github.com/lucasmargui/Node_Cypress_Finance/assets/157809964/351b279e-2d94-41d9-ab13-2ed7a19b0bf9" style="width:70%">
 <img src="https://github.com/lucasmargui/Node_Cypress_Finance/assets/157809964/513aa84d-6109-4a11-a305-aa9732663ab1" style="width:70%">
</div>




### Create an auxiliary function

- Test Setup: Auxiliary functions help in setting up the test environment by performing tasks like logging in, seeding the database, or navigating to a specific page before each test.

- Reusable Actions: They encapsulate repetitive actions, such as clicking a button, filling out a form, or selecting an item from a dropdown menu, into reusable functions. This promotes code reusability and reduces duplication across tests.

- Assertions and Expectations: Auxiliary functions can be used to define custom assertions or expectations tailored to the application's specific requirements. These assertions enhance test clarity and help in accurately verifying the expected behavior of the application.

- Data Management: They assist in managing test data by generating mock data, cleaning up test artifacts, or resetting the application state between tests. This ensures test independence and reliability.

- Error Handling: Auxiliary functions can handle errors gracefully by implementing retry mechanisms, logging errors, or executing fallback actions to maintain test stability and robustness.

- Abstraction of Complex Interactions: For complex interactions such as drag-and-drop or multi-step workflows, auxiliary functions abstract away the complexity, making tests more readable and maintainable.

- Custom Commands: Cypress allows defining custom commands using auxiliary functions, enabling the extension of Cypress's functionality to better fit the testing needs of the application.

- Performance Optimization: They can optimize test performance by implementing strategies such as batching requests, parallelizing test execution, or minimizing DOM interactions.

<div align="center">
 <img src="https://github.com/lucasmargui/Node_Cypress_Finance/assets/157809964/79be4b43-25e1-4293-b6c8-c4fc6a3f6ea8" style="width:70%">
 </div>


### Assertions

- Chaining: Cypress assertions use a chaining syntax, allowing multiple assertions to be sequentially applied to the same subject. This makes it easy to express complex verification logic succinctly.

- Readability: Assertions in Cypress are designed to be human-readable, enhancing the clarity of test code and making it easier to understand the test's purpose and expected outcomes.

- BDD Syntax: Cypress assertions follow the Behavior-Driven Development (BDD) syntax, employing natural language constructs like expect, should, and assert to articulate test expectations in a descriptive manner.

- Automatic Retry: Cypress automatically retries assertions until the specified condition is met or the timeout is reached. This built-in retry mechanism reduces flakiness in tests caused by asynchronous behavior or transient UI states.

- Built-in Matchers: Cypress provides a rich set of built-in matchers for common assertions such as equality, containment, visibility, and element attributes. These matchers cover a wide range of verification scenarios without requiring additional configuration.

- Custom Assertions: Developers can define custom assertions using Cypress's API, allowing them to encapsulate domain-specific validation logic or complex verification criteria into reusable functions.

- Snapshot Testing: Cypress supports snapshot testing, enabling comparison of the current state of UI elements or application data against previously captured snapshots. This facilitates regression testing and ensures consistency across releases.

- Error Messaging: When an assertion fails, Cypress provides detailed error messages and stack traces, aiding in debugging and identifying the root cause of test failures quickly.

- Integration with Test Runners: Assertions in Cypress seamlessly integrate with popular test runners like Mocha or Jasmine, enabling developers to leverage familiar testing frameworks and conventions.

- Extensibility: Cypress's assertion library is extensible, allowing developers to integrate third-party assertion libraries or plugins to extend the capabilities of Cypress assertions as per project requirements.

<div align="center">

 <img src="https://github.com/lucasmargui/Node_Cypress_Finance/assets/157809964/cd5ccf18-4cf2-42d9-a8f9-5e4f81e330b3" style="width:70%">
 <img src="https://github.com/lucasmargui/Node_Cypress_Finance/assets/157809964/886f195a-092d-4f95-9177-f731f96188ab" style="width:50%">
</div>












