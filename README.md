# Explaining Variables and Functions

Teach a brand new programmer how a value gets stored and reused.

- [AI Use on This Assignment](#ai-use-on-this-assignment)
- [Before We Begin](#before-we-begin)
- [Setup](#setup)
- [Instructions](#instructions)
- [Short Response Questions](#short-response-questions)
  - [Prompt 1](#prompt-1)
- [Submitting](#submitting)

## AI Use on This Assignment

These are your own words. Do not use AI to draft or rewrite your responses —
that holds in every mode, including implementer mode. You may use it to check
grammar and spelling on writing you have already done, and you may use it
before you start to quiz you until you can explain each term out loud without
notes. Paste this if you want that kind of help:

> You are acting as a tutor. Quiz me on Python variables, data types and
> functions until I can define each one without looking anything up. Tell me
> when my reasoning is wrong or imprecise. Do not write or rewrite any part of
> my response for me.

A response you did not write is worth nothing to you in an interview, which is
where this writing is really aimed.

## Before We Begin

Welcome to your first short response assignment! If the code you write is what
gets your foot in the door for an interview, how you communicate is what gets
you the job. So treat these seriously. Write as if you were going to publish
this on a blog for the world to read. And if you are feeling confident,
actually publish it.

Explaining a concept is also how you find out whether you understand it. A gap
in your explanation is a gap in your knowledge.

## Setup

Work in `development/mod-1`. Make a draft branch before you start.

```sh
git checkout -b draft
```

There is no code to run here, so there is no virtual environment to make.
Pushing tells GitHub to check whether you have written a response yet, which
you can see in the **Actions** tab. That check counts words. Your instructor
reads what you wrote and replies on your pull request.

## Instructions

Write your response in `short_response.md`. Aim for a response with these qualities. Your instructor will give you
feedback on each one:

- [ ] Addresses all parts of the prompt
- [ ] Accurately uses relevant technical terminology
- [ ] Is free of grammar and spelling mistakes (double check with Grammarly!)
- [ ] Uses markdown to enhance readability (preview in VS Code with
      Command/Control + Shift + V)
- [ ] Is easy to comprehend

## Short Response Questions

### Prompt 1

Imagine you are teaching a brand new programmer a short lesson on functions. Your lesson should have four parts:

- A technical definition of a **function**, quoted and credited to a source you
  name. The
  [Python glossary](https://docs.python.org/3/glossary.html#term-function) and
  [W3Schools](https://www.w3schools.com/python/python_functions.asp) are both
  fine starting points.
- An explanation using an analogy of your own: "You can think of a function as
  a ..."
- An example in a Python code block (triple backticks). Your example has to
  store a value in a variable, pass it to a function, and use what comes back.
- An explanation of your example.

That last part has to use all six of these terms correctly:

- **variable**
- **data type**
- **function definition**
- **parameter**
- **return statement**
- **call**, also known as **invoke**

Defining them is the assignment, so we are not defining them here. Together
they trace the path a value takes, and an explanation that skips one usually
skips a step so ensure that you use all 6 terms before submitting.

Below is a suggested outline for your response. Change it if you would rather structure
it differently.

    [Your explanation of the concept with an analogy]

    Check out this example:

    ```python
    # Your example here
    ```

    [Your explanation of the example and the syntax]

## Submitting

```sh
git add -A
git commit -m "your message"
git push
```

Open a pull request to your instructor for feedback.
