# 2315038

# Afformed Campus Hiring Evaluation



## Stage 3 - Query Optimisation and Cost

### The given query is:

sql
SELECT *
FROM notifications
WHERE studentID = 1042
  AND isRead = false
ORDER BY createdAt ASC;


### Is the Query Accurate?

Yes. The query correctly retrieves all unread notifications for a specific student and orders them by creation time in ascending order. It is optimized for a large dataset.

### Computational Cost

**Time Complexity:** `O(N)`

Where:


N = 5,000,000




