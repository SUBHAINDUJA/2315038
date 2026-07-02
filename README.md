# 2315038

# Afformed Campus Hiring Evaluation

## Stage 1 - Notification System REST API Design

---

## Stage 2 - Application Schema

---

## Stage 3 - Query Optimisation and Cost

### The given query is:

```sql
SELECT *
FROM notifications
WHERE studentID = 1042
  AND isRead = false
ORDER BY createdAt ASC;
```

### Is the Query Accurate?

Yes. The query correctly retrieves all unread notifications for a specific student and orders them by creation time in ascending order. It is optimized for a large dataset.

### Computational Cost

**Time Complexity:** `O(N)`

Where:

```
N = 5,000,000
```

We can use index to speed up the performance.

---

## Stage 4 - Query Performance

---

## Stage 5 - Redesigning to be Reliable and Fast

---

## Stage 6 - To Fetch Notifications from the API

---

## Stage 7 - Implementing Logging Middleware
