# How to run Chrome and firefox in headless mode in Pytest on [LambdaTest](https://www.lambdatest.com/?utm_source=github&utm_medium=repo&utm_campaign=Pytest-headless)

If you want to run chrome and firefox browser in headless mode for an automation test in Pytest on Lambdatest, you can use the following steps. You can refer to sample test repo [here](https://github.com/LambdaTest/pytest-selenium-sample).

# Steps:

You can run a test in headless mode by adding that as a desired capability in the `conftest.py` file. For example:

 ```
capabilities = {
        "build": "Sample PY Build",
        "platformName": "Windows 11",
        "browserName": "Chrome",
        "browserVersion": "latest",
        "headless": True
}
 ```


# Links:

[LambdaTest Community](http://community.lambdatest.com/)


