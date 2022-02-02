# Assignment-2-Jasthi

# RamyaSri Jasthi

###### Barbeque Nation

In the Old **Mahabalipuram Road (OMR)**, the hub of IT industry of Chennai, several restaurants are expecting a good footfall as IT firms are slowly opening their premises. The increase in vehicular traffic through the OMR stretch has also caught up.A number of SEZ have emerged in and around Chennai. The **Mahindra World City** a Special Economic Zone (SEZ) with one of the world's largest high technology business zones, is currently under construction in the outskirts of Chennai. It also includes the World's largest IT Park by Infosys.

<hr>
# Nearest Airport and Address

## Maa Airport

1. Take a cab outside the airport
2. Option 2-Take a bus outside the airport
3. Step down at Barbeque Nation



### Recommended food items

* Potato Fries
* Biryani
* Manchuria

[Goto AboutMe] (AboutMe.md)

<hr>

## Recomended Games

Below table gives a breif intro about gaming activites and the location of gaming arena along with amount payable for any additional equipment opted.


|Sport | Location | Money Payable|
|  ---  |   ---   | :--- |
|cycling| Kansas | $ 4100|
|Skating| vegas | $ 2100|
|go kart| Florida | $ 1400|
|rally| Chicago | $ 7100|

<hr>

# Pithy Quotes

> "The greatest glory in living lies not in never falling, but in rising every time we fall."<br>
>***-Nelson Mandela***

>"The way to get started is to quit talking and begin doing."<br>
>***-Walt Disney***

<hr>

# Code Fencing

# Fibonacci Numbers

>In mathematics, the Fibonacci numbers, commonly denoted Fn, form a sequence, the Fibonacci sequence, in which each number is the sum of the two preceding ones. The sequence commonly starts from 0 and 1, although some authors omit the initial terms and start the sequence from 1 and 1 or from 1 and 2.[-Goto Source](https://en.wikipedia.org/wiki/Fibonacci_number).

Thus using above two equations `Fibonacci numbers` can be calculated easily by the following code: <https://cp-algorithms.com/algebra/fibonacci-numbers.html>

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

