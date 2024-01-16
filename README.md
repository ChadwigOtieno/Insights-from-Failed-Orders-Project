# Task 1: Distribution of Failed Orders

## Analysis Overview

In this task, we investigated the distribution of failed orders based on various reasons for failure, including cancellations before and after driver assignment, as well as reasons for order rejection.

## Results

The analysis resulted in a comprehensive plot illustrating the distribution of failed orders across different categories. The key findings are as follows:

- **Cancellations Before Driver Assignment (Status 4 - cancelled by client):**
   - 8.2k orders, representing the highest count among failure categories.

- **Cancellations After Driver Assignment (Status 9 - cancelled by system):**
   - 2.9k orders, indicating a significant but lower count compared to cancellations before driver assignment.

- **Reasons for Order Rejection:**
   - Client cancellation (7.5k orders) comprises 68% of all rejections, while system cancellation (3.5k orders) accounts for the remaining 32%.

- **Count by Failure Categories and Reason for Rejection:**
   - *Driver Not Assigned:*
      - 4.7k orders (client cancelled)
      - 3.5k orders (system cancelled)
   - *Driver Already Assigned:*
      - 2.9k orders (client cancelled)
      - 0 orders (system cancelled)

## Observations

The analysis highlights that the majority of failed orders are attributed to clients canceling before a driver is assigned. Further investigation is needed to understand the underlying reasons for this high occurrence.

## Next Steps

To gain more insights into failed orders, subsequent tasks in the analysis will explore the distribution of failed orders by hours, average time to cancellation and distribution of average ETA by hours.

