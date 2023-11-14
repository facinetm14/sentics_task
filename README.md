# sentics_task

Here is my solution:

I Read the dumy_data and store in container based on columns
I Sort by timestamp but not necessary here because it's already sorted by timestamp
I group by sensorid
I For each sensor group, group elements by uniq_id
I For each sensor uniq_id groups, group by distance
I merge by distance groups
I creat a cluster and to push it to my list of clusters

I tried to balance beetwen quality and time, if given chance I could optimized and refactor some part of the code and make it more efficient

I'm looking forward to hear your feedback
