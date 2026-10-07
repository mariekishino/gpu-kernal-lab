# Vector Addition

## Idea
1 thread handles 1 element.

## Index
i = blockIdx.x * blockDim.x + threadIdx.x

## Why bounds check?
The last block may contain more threads than N.

## Complexity
Time: O(N)
Work per thread: O(1)

## Learned
- kernel launch syntax
- threadIdx.x
- blockIdx.x
- blockDim.x