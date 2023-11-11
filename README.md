 # ifBlocked
A library for determining if a website is blocked by a school extension. Good for exploit creators, and filtering unblocked links.

## How to Use
1. Add the 'script.js' file from this repository into your project.
2. Once added, you can perform a check on a website like this:

   ```javascript
   if (blocked('github.com') === true) {
       console.log("website blocked");
   }
