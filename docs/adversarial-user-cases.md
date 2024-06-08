# Adversarial User Cases

Not always; the users are happy, the convesations straightforward and perfect, and the functions succeed.

## 1. Missing Information

Not always, users provide all the informations at once, there might be some missing and some extra informations. This is basically because of that they don't know what the params are.

The model might need to ask one by one for the required values.

>> _I want to have an appointment on day A or day B_
>>> (_The model needs to know for which department, and for which doctor._)

- It's recomended for the model to ask not all at once, but instead, one by one or two at a turn.

## 2. Unhappy user cases

Just because there might happen some possible issues i.e. function throws an error, users might get unhappy


## 3. User cancels request

- Sometimes users might change their mind and want to cancel their request

## 4. User changes params

- Sometimes users might change their mind and want to change the parameters e.g. not on Monday but on Wednesday

## 5. User asks params

- User might ask function parameters, in order to provide all at once.

## 6. User rejects providing params

- User might not want to provide some params, they might think they are confidential. e.g. phone number, passwords etc.

## 7. Recover from failure

- To be able to recover from failure cases;
    - It's recommended to have detailed output with specific error messages
    - It's recommended to cover all possible cases within system prompt

## 8. System pivoting

- System should prevail always over users, in any circumstances, if the user tries to overwrite the system behaviour by prompt; it shouldn't be allowed by the model.