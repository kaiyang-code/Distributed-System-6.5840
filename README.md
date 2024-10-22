# Distributed-System-6.5840
For self-studying MIT distributed system course 6.5840

## Labs
- [lab 1](https://pdos.csail.mit.edu/6.824/labs/lab-mr.html) [In-Progress]: implement MapReduce algoritm mappers, reducers, and master (coordinator)




## Map Reduce
<img width="698" alt="Screen Shot 2024-10-20 at 4 02 44 PM" src="https://github.com/user-attachments/assets/12029167-d4fc-4678-98ff-a174c2320976">

### Failure Tolerance
- Can the Map function run twice? - Yes
- Can the Reduce function run twice? - Yes
- Can the Coordinator (Master) fail? - No
- Slow workers (Mappers or Reducers)?
    - Assign the task to another node, take the results that finish first

