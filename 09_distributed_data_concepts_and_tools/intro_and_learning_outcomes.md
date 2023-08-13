## INTRODUCTION

In learning Spark, we came across the ideas of replication and partitioning. In this module, we will dive deeper into these concepts. When data is partitioned across servers, data skew and hot spots can arise. We will study these issues and how they can be remediated. Next, you will learn about a specific distributed event and data streaming tool: Apache Kafka. You will get some hands-on experience setting up a Kafka server, creating topics, and sending and receiving messages.

## Learning Objectives

At the conclusion of this module, you should be able to:

- Explain the benefits of data replication
- Understand the advantages and disadvantages of leader-based replication
- Explain how leader-based replication works
- Identify the purpose of data partitioning
- Define data skew and give strategies to mitigate skew
- Understand how hot spots lead to data skew
- Identify the need for partition rebalancing and strategies that support it
- Understand common types of network faults
- Explain the concepts and benefits of Apache Kafka
- Describe the pub/sub model and its benefits
- Progress toward executing an end-to-end predictive modeling project using a large dataset