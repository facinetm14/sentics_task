# sentics_task

<p> Here is my solution: <p>
  
  <li> Read the dumy_data and store in container based on columns</li>
  
  <li>Sort by timestamp but not necessary here because it's already sorted by timestamp</li>
  
  <li> group by sensorid </li>
  
  <li>For each sensor group, group elements by uniq_id</li>
  
  <li>For each sensor uniq_id groups, group by distance </li>
  
  <li> fusion by distance groups </li>
  
  <li> push the curent cluster to my list of clusters </li>
  
  <p> I tried to balance beetwen quality and time, if given chance I could optimized and refactor some part of the code and make it more efficient <p/>
  <p> I'm looking forward to hear your feedback </li>
 
