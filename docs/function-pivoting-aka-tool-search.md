# Function Pivoting aka Tool Search

## 1. Pivoting a function

JSON Schema pivoting is a way that there is a one Tool Search function which will search withing the tools and output the most relevant one so that the model can use that outputted function in next call.

### Benefit:

- Picking the right function will be under your control instead of LLMs.

- When there are too many functions; becuase you don't need to send them all, it will save a significant amount of tokens which will reduce the cost.

### Drawback:

- It causes at least 2 function calls in each case, so there will always be a delay. Moreover, it might not be that right to leave the decision of the functions to your app. LLMs are obviously better to choose the correct function with correct parameters. Lastly, many LLMs are not trained in that way, this would be just an experiment.


