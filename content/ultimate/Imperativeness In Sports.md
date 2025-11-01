---
title: Imperativeness in Sports
date: 2023-09-29
---

**Imperative vs. Declarative**: This topic often surfaces in programming discussions. At its core, "imperative" describes the "how to" while "declarative" emphasizes the "what to do". 

-----
Let's examine an example:

**Imperative Approach**:
```python
numbers = [1, 2, 3, 4, 5, 6]
doubled_evens = []

for num in numbers:
    if num % 2 == 0:
        doubled_evens.append(num * 2)

print(doubled_evens)  # Output: [4, 8, 12]
```

In the imperative approach, we've specified *how* to get the result step by step.

**Declarative Approach** (using Python's built-in functions):
```python
numbers = [1, 2, 3, 4, 5, 6]
doubled_evens = list(map(lambda x: x * 2, filter(lambda x: x % 2 == 0, numbers)))

print(doubled_evens)  # Output: [4, 8, 12]
```

In the declarative approach, we describe *what* we want. We leverage Python's built-in functions to specify our intent without delving into the detailed procedure.

Both approaches yield the same result, but the means to achieve this result differ.

-----

A prevailing sentiment is that superior programs lean toward the declarative. This involves clearly outlining specifications, defining a set of rules or facts that a program must adhere to, and letting the compiler/language/framework address the imperative aspects.

Drawing a parallel between programming and sports coaching becomes intriguing. When newcomers are introduced to a sport, they are initially instructed in an imperative manner:

- Precise steps for executing a V-cut.
- The wrist flick needed to deliver a forehand.
- Using both hands to try a pancake catch.

As you delve deeper into the sport, you cultivate muscle memory, enabling you to instinctively follow these instructions—whether making cuts, executing throws, or faking out opponents. One might liken each athlete to a unique compiler.

However, when we elevate from individual actions to team tactics, instructions adopt a more declarative tone:

- "Move the disc from point A to B."
- "Engage the break space."
- "Focus on overwhelming the handler defensively." 

Different athletes and teams interpret and execute these directives in varying ways. For instance, while one player might favor a sweeping pass to bypass an opponent, another might opt for a high release.

As coaching ascends to elite levels, instructions should become increasingly declarative. Why? Such an approach nurtures creativity and experimentation, fostering a distinct style among athletes and teams. This distinctiveness—often dubbed 'chemistry'—gives rise to stars and exceptional teams. It's a unique blend that's hard to replicate, as each player brings a distinct touch to the game.

However, a pitfall I've observed in coaching is an over-reliance on imperative directives, especially when trying to elevate teams to competitive tiers:

- "When positioned here, make an upline move."
- "Opt for an overhead throw when faced with a direct mark." 

While such specific instructions can be readily grasped and acted upon by players, real-world matches present a myriad of scenarios. Preparing for every possible situation is almost impossible. Consequently, teams might find themselves strategically lack of depth, becoming predictable to their adversaries. The silver lining is that such an approach can foster team cohesion, as players are given clear, direct orders to follow.

I don't intend to deride the merits of imperative tactics. Just as the imperative paradigm holds value in programming, solving myriad problems, it has its place in sports coaching.

Nonetheless, my inclination is toward a more declarative coaching approach for team sports like Ultimate Frisbee. It not only allows athletes to infuse their personal style into the game but also promotes communication and strengthens interpersonal ties. There's no single "correct" method to follow a directive.

I aspire to craft a robust set of declarative principles tailored for Ultimate Frisbee. My hope is that these insights will positively influence teams, ensuring that the sport retains its dynamism and inclusivity—encouraging varied interpretations within a unified declarative framework.