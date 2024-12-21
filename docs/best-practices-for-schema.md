# Best Practices for Schema

## 1. Function and schema specification

- Ensure functions have clear responsibilities and are not overly simplistic.
- Provide detailed descriptions for properties and parameters. Include enum values or range specifications where applicable.
- Avoid assuming default values without clear definitions. For instance, do not assume currency as USD.

## 2. Clarity and logical flow

- Make sure inputs and outputs for tools are not redundant or identical. Each tool should add value or perform a transformation.

- Ensure prompts and instructions are clear, include realistic scenarios, and are easy to follow or implement.

## 3. Naming and structural conventions

- Use specific, descriptive terms in naming consistently.
- It's always better to have descriptive names and without any whitespaces.

For example, use `build_strength` instead of `build strength`.

## 4. Enhanced Definitions and Details

- Provide more detailed and actionable definitions for properties system instructions.
- Including a detailed desription might help the model to choose the correct function at the correct turn.

## 5. Function output:

- Some of the functions including output might help the model to plan chain of thoughts, i.e. `returns`, `output`, `yields`...
 -The output does not necessarily should be in a seperate field, becuase not all compilers allow it. Thus, it's also acceptable to include it in a description with a natural language instead of JSON.