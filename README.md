1. ¿Cual es la complejidad de tiempo de la función example()?

int example(int n)
{
  int count = 0;
  for (int i = n; i > 0; i /= 2)
     for (int j = 0; j < i; j++)
        count += 1;
  return count;
}

O(log n)

2. ¿Cual es la complejidad de tiempo de la función example2()?

void example2(int n, int arr[])
{
    int i = 0, j = 0;
    for(; i < n; ++i)
        while(j < n && arr[i] < arr[j])
            j++;
}

O(1)

3. ¿Cuál es la mejor complejidad de tiempo de bubbleSort?

Ω(n²)
