# Priority-Queue
This priority queue is written in javascript. 

# create a new instance of a priority queue


var pq = new PriorityQueue(128, function(val1, val2){
    return val1 < val2;
})

Code above creates a minimum priority queue with maximum size of 128. 

To create a maximum pq, just simply modify your callback function to make it return true
when the first argument is greater than the second argument. 

# add a new element
pq.push(18);

# pop an element
pq.pop();

# check if the pq is empty
pq.empty();

# print current pq
pq.printQueue();
