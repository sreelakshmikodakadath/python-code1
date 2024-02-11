def print_design(rows, cols):
    for i in range(rows):
        for j in range(cols):
            if (i + j) % 2 == 0:
                print("*", end=" ")
            else:
                print(".", end=" ")
        print()

# Sample 1
print("Sample 1:")
print_design(4, 7)

# Sample 2
print("\nSample 2:")
print_design(3, 5)
