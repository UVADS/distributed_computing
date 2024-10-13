## INTRODUCTION

For massive training sets, it may not be possible to train a model on a single machine. This may be the case for deep learning models. In distributed training, the workload to train a model is split up and shared among worker nodes. We will study different approaches for distributed training to understand their strengths and challenges.

## Learning Objectives

At the conclusion of this module, you should be able to:

- Explain approaches for distributed model training
- Identify the benefits and challenges of synchronous and asynchronous training
- Explain the parameter server and Allreduce algorithms
- Explain why Ring-Allreduce can work better than Allreduce
- Progress toward executing an end-to-end predictive modeling project using a large dataset.
