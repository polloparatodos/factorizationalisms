def get_sums(max_value, cur_int):
    sums = int((max_value / cur_int)) + int(cur_int)
    print("{} + {} = {}".format(int((max_value / cur_int)), int(cur_int), sums))
    return sums


def get_factors(value):
    # init defaults
    factors = set()
    lower_limit = 1
    upper_limit = value + 1

    # If value is a negative number, lower_limit should be the value and 0 should be the upper_limit
    if value < 0:
        lower_limit = value
        upper_limit = 0

    print("Verify if any of the following, when added up, equal to your 'B' value")
    for i in range(lower_limit, upper_limit):
        if value % i == 0:
            product_friend = int((value / i)) + int(i)
            print("{} + {} = {}".format(int((value / i)), int(i), product_friend))
            factors.add(product_friend)
    print("Sums found are {}".format(factors))


if __name__ == '__main__':
    print('To utilize this script properly, please ensure you have a trinomial\nExample: -0.5x^2 + 40x - 350')
    get_factors(int(input("What is the result of multiplying the leading coefficient by your 'C' value? ")))

