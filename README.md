# ifBlocked
A library for determining if a website is blocked by a school extension. Good for exploit creators, and filtering unblocked links.

# How to Use
- Add 'script.js' in this repository to any code you want to use it in.
- Done! You can now check if a website is blocked like this:
  
  <code>
  if (blocked('github.com') === true) {
    console.log("Blocked");
} else {
    console.log("Unblocked");
  <code>
