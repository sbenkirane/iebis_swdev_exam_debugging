# iebis_swdev_exam_debugging
Somebody from administration wanted to create a random phrase generators and created the code that you can find in Main.java for this purpose.

The code converts the dots (".") that are in an email address to slashes ("/"). Then a random word is created in front of the result to create weird sentences.

So for an email address like "john.doe.mis2016@ie.edu" the potential outputs is the following sentences:

```
Your john/doe/mis2016@ie/edu
Four john/doe/mis2016@ie/edu
Tour john/doe/mis2016@ie/edu
```

So basically, every time that you run the code, one of these sentences is printed in the console.

Furthermore, these sentences appear with equal equiprobability, so if we would run the code 1000 times, the repetitions of each sentence is close to 333 for each one. Obviously, we can not achieve exactly one third of the times with a random generator, but at least it is close.
