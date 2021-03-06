## Features

* Test Class
* Test Initialize
* Test Method
* Test Cleanup

The Class, Initialize, and Cleanup snippets use the current filename to name the symbol.

Example:  

In a file called "FindAccountTests.cs" it will produce:

```csharp
[TestClass]
public class FindAccountTests 
{

}
```

```csharp
[TestInitialize]
public void InitializeFindAccountTests()
{
    
}
```

```csharp
[TestCleanup]
public void CleanupFindAccountTests()
{
    
}
```

The testmethod snippet simply emits a test method with a dummy name, but it is the first tab stop so you just keep typing.

```csharp
[TestMethod]
public void MyTestMethod()
{
    
}
```

In all cases the second tab stop is within the symbol body.

## Release Notes

### 0.0.5
Made display name more searchable.

### 0.0.4

Initial release for testing via the marketplace.  Includes 4 snippets.