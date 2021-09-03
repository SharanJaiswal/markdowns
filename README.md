# Sample heading
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

*Note: this is italicized text*, or this is _italics_

**This is a bold text**

*This can be nested with the **bold** also.*

**this *is my* laptop**

This is normal paragraph line.

Lorem Ipsum kjbjkfsdbi  ud di   dun u nudhvdu ubnfouvnd fnvdfn   n no.
edfsd gbg  f f.

* this is first,
* this is second
    * this is third
        * this is forth and its the limit.
            * same bullet

1. first point
2. second point

Here's a link to my website. Click [here](https//:sharanjaiswal.github.io).

This is `button`.
Below is codeblock:
```
print('Hello World')
for i in range(10):
    print(i)
```

<h1 style = "font-size:3rem;color:orange;">Jupyter Notebook heading tutorial</h1>

https://www.markdownguide.org/

https://dillinger.io/

https://docs.github.com/en/github/writing-on-github

https://docs.github.com/en/github/writing-on-github/getting-started-with-writing-and-formatting-on-github

https://choosealicense.com/

---
- [Get Current Date](#get-current-date)
- [The datetime.date Class](#the-datetimedate-class)
- [The datetime.time Class](#the-datetimetime-class)
- [The datetime.datetime Class](#the-datetimedatetime-class)
- [Getting current date and time](#getting-current-date-and-time)
- [The datetime.timedelta Class](#the-datetimetimedelta-class)
- [Python `strftime()` method](#python-strftime-method)
- [Python `strptime()` method](#python-strptime-method)

---

* `date` class - to work with date
* `time` class - to work with time
* `datetime` class - combination of `date` and `time` classes

---
## The datetime.time Class

The `time` class of the `datetime` module is used to create `time` objects that can store time of day like hours, minutes, seconds, and microseconds.

The time class takes in all optional integer arguments. By default all of them are `0`.
- The first argument is hour from `0` to `24`
- The second one is minutes from `0` to `60`
- The third is seconds from `0` to `60`
- The fourth is microsecond from `0` to `999999`

```python
import datetime as dt
time1 = dt.time(10, 47, 20, 234566)
print(time1)
print("Hour:", time1.hour)
print("Minute:", time1.minute)
print("Second:", time1.second)
print("Microsecond:", time1.microsecond)
```

>**Note:** If you want more control and functionalities on time, use the `time` module.
---

Here,
- `%A` represents the weekday name i.e. `Thursday`
- `%B` represents the month's full name
- `%d` represents the day of the month
- `%Y` represents the year

There are many other format codes:

| Directive | Meaning                                   | Example             |
|-----------|-------------------------------------------|---------------------|
| `%a`      | Abbreviated weekday name                  | Sun, Mon, ...       |
| `%A`      | Full weekday name                         | Sunday, Monday, ... |
| `%w`      | Weekday as a decimal number               | 0, 1, ..., 6        |
| `%d`      | Day of the month as a zero-padded decimal | 01, 02, ..., 31     |
| `%b`      | Abbreviated month name                    | Jan, Feb, ..., Dec  |
| `%p`      | Locale?s AM or PM                         | AM, PM              |

---
***
___

## Python `strptime()` method