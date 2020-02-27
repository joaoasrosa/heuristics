# Don't allow the model from one bounded context to propagate

## Question
Should I use event-driven architecture (message bus) or client-server architecture(rest)?

## Heuristic
Don't allow the model from one bounded context to propagate.

## Examples
- Consume and use an event in my bounded context
- Use an event as input, but use your own context

## Context
### Inspired by
[Gojko Adzic](https://twitter.com/gojkoadzic)

### Where
DDD Europe, Amsterdam, The Netherlands

### Date
February 2020