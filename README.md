def find_min_max(numbers):
    return min(numbers), max(numbers)

if __name__ == "__main__":
    nums = [12, 7, 25, 3, 18]
    smallest, largest = find_min_max(nums)
    print(f"Smallest: {smallest}, Largest: {largest}")

