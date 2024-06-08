# Best Practices for Schema

## 1. Function and Schema Specification

- Ensure functions have clear responsibilities and are not overly simplistic.
- Provide detailed descriptions for properties and parameters. Include enum values or range specifications where applicable.
- Avoid assuming default values without clear definitions. For instance, do not assume currency as USD.

## 2. Clarity and Logical Flow

- Make sure inputs and outputs for tools are not redundant or identical. Each tool should add value or perform a transformation.

- Ensure prompts and instructions are clear, include realistic scenarios, and are easy to follow or implement.

## 3. Naming and Structural Conventions

- Use specific, descriptive terms in naming consistently.
- It's always better to have descriptive names and without any whitespaces.

For example, use `build_strength` instead of `build strength`.

## 4. Enhanced Definitions and Details

- Provide more detailed and actionable definitions for properties like `theme` and system instructions.

## Function Output:

- In half of the functions including output might help the model to plan, i.e. `returns`, `output`, `yields`...
