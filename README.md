# Process Scheduler Calculator: Round Robin Algorithm

This repository simulates Round Robin Algorithm for process scheduling and calculates the average time processes are active, average response time, and average response time.


## Clone Project

```bash
$ git clone https://git@github.com:jorgearaujo81/algoritmo_Round_Robin.git
$ cd algoritmo_Round_Robin
```

## Running

```bash
$ make run
```

## Examples Input and output

The number of processes is the first value and the second is the quantum
In the next lines it should receive the moment when the process arrived and separated by space the amount of time it will take to finish.
 
 ```
 N q
 arrival_1 duration_1
 arrival_2 duration_2
 ...
 arrival_N duration_N
 ```

 The output should show a string with the algorithm and the average of values separated by a space.

 ```
 RR finishTimeAverage responseTimeAverage waitTimeAverage
 ```

### Input 1

```
4 2
0 20
0 10
4 6
4 8
```

### Output 1

```
RR 31.5 2.0 20.5
```
