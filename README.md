# Cheatsheet to react fetching 
## Loading 
- It is used for better UX while waiting for the data
- When we are fetching data we `setIsLoading=true` and based on this condition display message
- After fetching `setIsLoading=false`
- For better readability could be used inside `finally`:
```js
finally {
  setIsLoading(false);
}
```
## Errors
- In the same way as loading we are using `useState` for holding error
- Is being executed inside `catch`


[Source video](https://www.youtube.com/watch?v=00lxm_doFYw)