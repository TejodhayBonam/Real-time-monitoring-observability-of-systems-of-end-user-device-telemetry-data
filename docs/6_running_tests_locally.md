# Running Tests Locally

On the VS Code install the [python extension](https://code.visualstudio.com/docs/python/testing). It will automatically detects pytest files in the project folder. Follow the below steps to run the test:

## Ctrl+Shift+P and Select a python version 3.9 on VS Code

1. Ctrl+Shift+P and select python interpreter

   ![Alt](./images/test_python_interpreter.png "Select python interpreter")

2. On the side panel select testing icon

   ![Alt](./images/test_icon_vscode.png "Testing icon")

3. Complete the configuration on the side panel. Ensure testing files have the test\_ prefixes

   ![Alt](./images/test_pytest_config.png "Pytest configuration")

4. Select Unit Test option

   ![Alt](./images/test_select_unit_test.png "Select unit test")

5. Ensure to choose the right prefix for the test files. In our case, files used test\_\* prefix

   ![Alt](./images/test_name_prefix.png "Test name prefix")
