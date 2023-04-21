# Sorting-and-searching-algorithms
ALGORITHM insertion_sort(arr)
VAR
n, i, j, key: INTEGER
BEGIN
n ← length of arr
FOR i ← 1 to n-1 DO
key ← arr[i]
j ← i-1
WHILE j >= 0 AND arr[j] > key DO
arr[j+1] ← arr[j]
j ← j-1
END WHILE
arr[j+1] ← key
END FOR
END
