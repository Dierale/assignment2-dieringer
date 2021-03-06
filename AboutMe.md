# Alexander Dieringer

#### Interesting Facts

Hey I'm Alex and I like to read, travel, game, and code.  When I'm reading I usually prefer to read Sci-Fi or Fantasy, but a good Thriller or Mystery story is always good.  Other than reading you'll probably see me playing either an MMO, RPG, or RTS game if I'm not trying to code my own game for fun.  I've traveled to eight different countries outside the United States, unless you want to group up the UK and then we're down to four instead.  When I'm traveling more locally I like to go camping and hiking in scenic areas.<br>

![camping](Camping.jpg "Campsite")

My favorite food is anything to do with blackberries really. Here have a picture<br>

![blackberries](Blackberry.jpg "Delicious Blackberries")

---
#### Foods to try

Speaking of foods, I have a few I really enjoy and I think that everyone should try at least one of following things.

| **Name** | **Available At** | **Estimated Cost** |
| --- | --- | --- |
| Blackberry Frozen Yogurt | Nutrissa shops (Mexico) | $10 |
| Barbacoa Tacos (Leg of Lamb) | Latin America | $10 |
| Alambres | El Maguey restaurants | $12 |
| Blackberry Lemonade | Ruby Tuesday restaurants | $7 |

---
#### Inspirational Quotes

> Why do you go away? So that you can come back.
> So that you can see the place you came from with new eyes and extra colors
And the people there see you differently, too.
> Coming back to where you started is not the same as never leaving.<br>
*- Terry Pratchett*

> The worst thing you can do is nothing.<br>
*- Terry Pratchett*

---
#### Algebraic Algorithms

**Chosen algorithm: Fibonacci**<br>
My S number is S503330 thus I must pick from algebra.

> The Fibonacci numbers are the numbers in the following integer sequence.
0, 1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, 144, ……..<br>
> In mathematical terms, the sequence Fn of Fibonacci numbers is defined by the recurrence relation<br>
>> Fn = Fn-1 + Fn-2<br>
>
> with seed values <br>
>
>> F0 = 0 and F1 = 1.

[source](https://www.geeksforgeeks.org/program-for-nth-fibonacci-number/)

```
pair<int, int> fib (int n) {
    if (n == 0)
        return {0, 1};

    auto p = fib(n >> 1);
    int c = p.first * (2 * p.second - p.first);
    int d = p.first * p.first + p.second * p.second;
    if (n & 1)
        return {d, c + d};
    else
        return {c, d};
}
```


---
[Back to README](README.md)
