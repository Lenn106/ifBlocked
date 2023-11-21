# ifBlocked
A library for determining if a website is blocked by a school extension. Good for exploit creators and filtering unblocked links.

## How to Use
1. Add the 'script.js' file from this repository into your project.
2. Once added, you can use one of the many features in the uses section.

# Uses 
<details>
  <summary>Extension Utilities</summary>
You can detect school extensions from a list and create custom handling for each one. You can also refer to the 'school' variable (true/false) for broad detection. 
 
 ```javascript
extensionUtil.check().then(result => {
  if (result.some(ext => ext.name === "Linewize")) {
    console.log("linewize");
  }
});
```
<details>
  <summary>Block Detection</summary>
You can detect if a website is blocked by a school extension, a tool for error handling and using alternative links.
 ```javascript
if (blocked('github.com') === true) {
  console.log("blocked");
}
```
