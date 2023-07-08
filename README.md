## Npm package url
https://www.npmjs.com/package/asyncfunctionhandler

## What is this?
A package which handles the asynchronous function and acts as a middleware.

## Installation
Run `npm i asyncfunctionhandler`

## Use
```
import asyncHandler from "asyncfunctionhandler";

router.get("/", asyncHandler(async (req, res) => {
    const data = await Data.find();
    res.send(data);
}))
```
## Parameters
This implementation of asyncHandler can be used as middleware in your Express routes to handle asynchronous functions and simplify error handling.
