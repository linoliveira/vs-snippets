# Visual Studio C# Snippets
KISS C# snippets for Visual Studio (tested on VS 2019).

## Installation
1. Copy the files in `src` folder to `%USERPROFILE%\Documents\Visual Studio 2019\Code Snippets\Visual C#\My Code Snippets`
1. Restart Visual Studio

## Usage
### Basic method
1. Type `method` and press `TAB` twice.
1. Press `TAB` to select the method accessibility, return type and name.
1. Press `ENTER` to start writing code.

```c#
public void MethodName()
{

}
```

### AAA Pattern
1. Type `aaa` and press `TAB` twice.
1. Start writing the test.

```c#
// Arrange
var target = 1;

// Act
var result = target.ToString();

// Assert
Assert.Equal("2", result);
```

### XUnit test method with AAA
1. Type `tmethod` and press `TAB` twice.
1. Press `TAB` to change the method, condition and outcome.
1. Press `ENTER` to start writing the test.

```c#
[Fact]
public void MethodUnderTest_ConditionUnderTest_ExpectedOutcome()
{
    var target = 1;

    // Act
    var result = target.ToString();

    // Assert
    Assert.Equal("2", result);
}
```

## Contributing
I made this for improving my own productivity, but I am glad to accept pull requests with your ideas.

A few guidelines:
1. KISS the snippets with no clutter with 3 to 5 steps max.
1. You must update the `README.md` in a KISS manner!

## License
[MIT](https://choosealicense.com/licenses/mit/)