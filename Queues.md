# Queueing theory

Much of this is pulled from The Art of Computer Systems Performance Analysis

## Open and Closed Queues

* Open Queues have external arrivals and departures
* Closed queues have no external arrivals or departures.

## Operational Laws

### Utilization Law

$$ utilization = busytime/T = completions/T * busytime/completions $$

This indicates the utilization of the current queue system.

### Little's Law

total number in queue = arrival rate * mean time in device

If the job flow is balanced then the arrivale rate is equal to the throughput.
This lets us say that

$$ total number in queue = throughput * mean time in queue $$

Little's law allows us to derive response times:

Given a queue with a throughput of 35.84 and an average queue length of 8.88 then
the response time of the processor is:

$$ 8.88/35.84 = ~0.25 seconds $$


