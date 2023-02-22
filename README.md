# React_bits_note
A compilation of React Patterns, techniques, tips and tricks.

1. Async nature of setState() /n
setState() does not immediately mutate this state, rather it creates a pending state transition. Accessing state immediately after calling setState() can potentially return the existing value. There is no guarantee of synchronous operation on setState() and calls may be batched for perf gains.
<img width="668" alt="image" src="https://user-images.githubusercontent.com/63888120/220496353-9b8430e4-4672-4b4c-9d28-7c56707b5f84.png">
possible solution: https://rajatexplains.com/setstate


