# Roman Numerals

## About this Kata ##

The Romans wrote numbers using letters : I, V, X, L, C, D, M.  They're still in use today, but they just don't fit well with base 2, 10 or 16. 

See:
- (https://en.wikipedia.org/wiki/Roman_numerals)

- (http://www.novaroma.org/via_romana/numbers.html)

### Part 1 - Integer to String Numerals 

We want you to write a method - the class doesn't matter - that has this signature:

```csharp
public string ToRoman(int value)
{
 // 
}
```

Given an integer ``value`` produce a string representation in Roman numerals.

Ensure:
- ``value`` is positive and non-zero
- ``value`` is not greater than 3000
- the result is a valid number in Roman numeral form

Examples:

- 1 => I
- 2 => II
- 4 => IV
- 14 => XIV
- 42 => DDDDII


### Part 2 - Numerals string to integer

We want you to write a method - the class doesn't matter - that has this signature:

```csharp
public int FromRoman(string value)
{
 // 
}
```

Given a string ``value`` produce the decimal form of the Roman numeral.

Ensure:
- ``value`` is a valid number in Roman numeral form

---

## We also need unit tests!

We're hot on test driven development, in the pure style, and that means test first and test often. Remember your early tutorials on TDD? That's what we practice.

## No cheating!

That means no ChatGPT nor Github Copilot!

---

## Pairing up, communications and all that

You'll be sharing your screen with someone else, and they will be assessing *everything.*

As you go through the kata, don't isolate yourself. Talk, and talk a lot: we want to hear your thinking. 

So if you've got a problem in year head, *talk out loud* (don't worry, we do not record!)

If you need to pause to collect your thoughts, *please just say so*. 

---

## Questions you might want to think about

* Can you factor the code for elegance and readability?

* How would you test with the minimum number of tests and test cases?

* What is the best way to verify your tests are correct?

* Speed! What are the bottlenecks?

## Thanks

***Many thanks to [@robcthegeek](https://github.com/robcthegeek)***
