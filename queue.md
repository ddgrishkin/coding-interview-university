# Queue
- [ ] [Queue (video)](https://www.coursera.org/lecture/data-structures/queues-EShpq)
- [ ] [Circular buffer/FIFO](https://en.wikipedia.org/wiki/Circular_buffer)
- [ ] [[Review] Queues in 3 minutes (video)](https://youtu.be/D6gu-_tmEpQ)
- [ ] Implement using linked-list, with tail pointer:
    - enqueue(value) - adds value at position at tail
    - dequeue() - returns value and removes least recently added element (front)
    - empty()
- [ ] Implement using fixed-sized array:
    - enqueue(value) - adds item at end of available storage
    - dequeue() - returns value and removes least recently added element
    - empty()
    - full()
- [ ] Cost:
    - a bad implementation using linked list where you enqueue at head and dequeue at tail would be O(n)
        because you'd need the next to last element, causing a full traversal each dequeue
    - enqueue: O(1) (amortized, linked list and array [probing])
    - dequeue: O(1) (linked list and array)
    - empty: O(1) (linked list and array)
