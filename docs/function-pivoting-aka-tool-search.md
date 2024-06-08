# Function Pivoting aka Tool Search

## 1. Pivoting a function

JSON Schema pivoting is a way that there is a one Tool Search function which will search withing the tools and output the most relevant one so that the model can use that outputted function in next call.

### Benefit:

- Picking the right function will be under control
- When there are too many functions; it will save a huge amount of token count.

### Drawback:

- This will cause 2 function calls in each case, so there will always be a delay.


