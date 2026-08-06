# Implementation Notes

## Project Objective

Checksum Control Field is a compact polyglot exercise designed to restore programming fluency through repeated implementation of one verification concept across multiple languages.

Each implementation should remain:

* small
* readable
* independently executable
* deterministic
* aligned with the shared sample input

## Shared Input

All implementations may use:

```text
data/sample-input.txt
```

The source material should remain unchanged while comparing output across languages.

## Expected Behavior

Each implementation should:

1. Read or define the shared control-field input.
2. Normalize the input where necessary.
3. calculate a checksum or deterministic verification value.
4. Display the resulting value.
5. Confirm that repeated execution produces the same result.

## Implementation Map

### Web

The browser implementation provides a visible control surface.

Planned files:

```text
web/index.html
web/styles.css
web/script.js
```

The interface should display the current field status and allow the user to initiate verification.

### Python

The Python implementation should read the sample input and calculate a checksum using a standard hashing library.

Planned file:

```text
python/checksum.py
```

### Ruby

The Ruby implementation should perform the same basic verification procedure using Ruby’s standard digest library.

Planned file:

```text
ruby/checksum.rb
```

## Verification Principle

Identical input should produce stable output within each implementation.

Where the same checksum algorithm and input encoding are used, implementations across different languages should produce matching values.

## Commit Strategy

Each functional addition should receive its own focused commit.

Suggested sequence:

```text
Initialize checksum control field
Add shared sample input
Document implementation protocol
Add browser control surface
Add JavaSript verification behavior
Add Python checksum implementation
Add Ruby checksum implementation
```

## Current Status

Repository structure defined.

Shared control-field data established.

Implementation sequence ready.
