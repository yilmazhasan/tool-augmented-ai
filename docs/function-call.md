# Function Call

A function call is a suggestion call by the model to the system using the LLM by an API to be performed.

## 1. Single Function Call

In a single function call; the user prompts such a query that requires exactly one function to be called.

>> _"What is the weather like in Tokyo?"_

## 2. Multiple Parallel Function Calls

In a multiple parallel function calls; the user prompts such a query that requires more than one function to e called.

>> _"What is the weather like in Tokyo and Paris?"_

## 3. Multiple Consecutive Function Calls

In a multiple consecutive function calls; the user prompts such a query that requires consecutive functions to be called; because the second function call would depend on the first one's output.

>> _"Create an appointment for XYZ on day A or B."_
>>> (First we need to check the availability of XYZ on day A and B to do so.)

## 4. No Function Call

In a no function call; the user prompts such a query that does not require a function to be called. The reason might be either because of a unsupported actions, or a query that might not require a function call at all.

>> _"What are the signs of the rain?"_

