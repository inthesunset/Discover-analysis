# Discover-analysis
## Analysis on watcher and follower on bitbucket
- Firstly, I collect the number of followers for each user, and then the number of watchers for each repo. 
- Secondly, I calculate the number of watchers for each user by summing up all repos' watchers of that user.
- So there should be co-watcher-follower for each user. Assume ratio: co-watcher-follower/watcher obeys normal distribution. Assume mean is 0.5.
- Do a T test on mean. Found that 0.5 can't be accepted.
  1. First plot include a big noise(too many zero value)
  2. After clearing the zero value in dataset, I plot it in second figure.
- Then I try to see the relation among follower watcher and co-watcher-follower.
  1. Although correlation is aroung 0.5, the model doesn't work well.(linear regression)
