# Balance Brackets Kata

## What we're looking for

We need you to write a C# method - the class doesn't matter - that has this signature:

```
public bool IsBalanced(string value)
{
 // 
}
```

Given a string ``value``, the method must return true or false depending on whether the brackets balance.


Brackets are these 6 characters: ``() {} []`` and by "balanced" we mean "correctly closed". Think of a parameterised method call: the opening paranthesis ``(`` must have a matching closing character ``)``; any interpolated brackets must be closed off before the "outer" brackets are closed, in other words they don't cross over.

---

## Examples:

``True``:

- ( )
- { } { }
- [ { ( ) } ]
- [ ( ) ( ) ]
- [()(())]

``False``:

- {
- }
- } }
- { } {
- [ { ( } ) ]

---

## What about Non-bracket characters?

Ignore them: they don't count towards bracket balancing. If ``value`` doesn't have any bracket characters, just return ``true``.

---

## We also need unit tests!

We're hot on test driven development, in the pure style, and that means test first and test often. Remember your early tutorials on TDD? That's what we practice.

---

## Pairing up, communications and all that stuff

You'll be sharing your screen with someone else, and they will be assessing *everything.*

As you go through the kata, don't isolate yourself. Talk, and talk a lot. We want to hear your thinking. 

So if you've got a problem in year head, *talk out loud* (don't worry, we do not record!)

If you need to pause to collect your thoughts, *please say so*. 

---

## Questions you might want to think about

* Can you factor the code for elegance and readability?

* How would you test with the minimum number of tests and test cases?

* What is the best way to verify your tests are correct?

* Speed! What are the bottlenecks?

## Thanks

***Many thanks to [@robcthegeek](https://github.com/robcthegeek)***
