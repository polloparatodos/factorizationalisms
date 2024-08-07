# Trinomial Factoring Demystifying Script

## Disclaimer

I have no idea what OS you're using, but I've tested it on Mac OS 12.3 Beta with Python 3.9

Will it work for you? I have no idea. But, if you find bugs, please do submit a PR or file an issue.

## Why would I want to use this?

Imagine, if you will, that you have a trinomial like the following:

-0.5x<sup>2</sup> + 40x -350

In order to factor this trinomial, you need to first take the value of A (-0.5) and C (-350) and multiply them together, which you'll get 175.

Not too bad, right? Well... this is annoying cause you'll need to find two values that factor nicely into 175 that also add up to 40. Gross...

## How do I use this?

It's easy! The steps are below!

1. Clone the repo to wherever you're comfortable, e.g., `~/git/factorizationalisms`
2. Go to the clones directory, e.g., `cd ~/git/factorizationalisms`
3. Run the script with your python interpreter either directly, Visual Studio Code, Pycharm, or w/e else you like.
4. Follow the prompt and enter in a number that is the result of multiplying `A * C`, Example: If `-0.5 * -350 = 175`, then enter `175`
5. Look at the STDOUT and see if anything looks familiar (hopefully, for you, you'll see a value post addition that equals your 'B' value
