# Adversarial User Cases

Not always; the users are happy, the convesations straightforward and perfect, and the functions succeed.

## 1. Missing information

The user does not provide all parameters in advance to call a function.

Not always, users provide all the informations at once, there might be some missing and some extra informations. This is basically because of that they don't know what the params are.

The model might need to ask one by one for the required values.

> _I want to have an appointment on day A or day B_
>> (_The model needs to know for which department, and for which doctor._)

- It's recomended for the model to ask not all at once, but instead, one by one or two at a turn.

## 2. Unhappy user cases

- Just because there might happen some possible issues i.e. function throws an error, users might get unhappy
- The user might be unhappy becuase the model can't understand what they try to do.

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
- Where the system prompt should decide in ambiguous cases.
- System should prevail always over users, in any circumstances, if the user tries to overwrite the system behaviour by prompt; it shouldn't be allowed by the model.

## 9. Toxic user

- The user might use a toxic/slang language.

## 10. Noisy input
- The user might have copied and pasted a noisy data where the arguments have to be extracted to call a function.
