class QueueUsingList:
    def __init__(self):
        self.queue = []

    def enqueue(self, data):
        """Add an element to the end of the queue."""
        self.queue.append(data)
u
    def dequeue(self):
        """Remove and return the first element of the queue."""
        if not self.is_empty():
            return self.queue.pop(0)
        else:
            return "Queue is empty"

    def is_empty(self):
        """Check if the queue is empty."""
        return len(self.queue) == 0

    def peek(self):
        """Get the first element of the queue without removing it."""
        if not self.is_empty():
            return self.queue[0]
        else:
            return "Queue is empty"

    def display(self):
        """Display the queue."""
        print("Queue:", self.queue)

# Example usage
queue_list = QueueUsingList()
queue_list.enqueue(1)
queue_list.enqueue(2)
queue_list.enqueue(3)
queue_list.display()  # Output: Queue: [1, 2, 3]
print(queue_list.dequeue())  # Output: 1
queue_list.display()  # Output: Queue: [2, 3]
