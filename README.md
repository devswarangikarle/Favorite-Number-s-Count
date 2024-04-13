# Favorite-Number-s-Count
Rahul's favourite number is 9. Help Rahul find the number of occurences of 9 in a given number 'n'. Input The only line contains an integer. Output Print the count of 7.  Constraints 1 ≤ integer ≤ 231-1

def count_favorite_number(n):
    count = 0
    for digit in str(n):
        if digit == '7':
            count += 1
    return count

n = int(input().strip())

print(count_favorite_number(n))
