# Looking for coupling in unexpected places

## Question
Is not coupling just for software components?

## Heuristic
Looking for coupling in unexpected places

## Examples
- 2 independent services in the same server rack, sharing the same network components. Although they are not logically connected, they can affect each other
- Chaos Engineering can surface this problems

## Context
### Inspired by
[Kent Beck](https://twitter.com/KentBeck)

### Where
DDD Europe, Amsterdam, The Netherlands

### Date
February 2020