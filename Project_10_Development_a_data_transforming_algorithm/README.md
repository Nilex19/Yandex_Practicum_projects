# Development a data transforming algorithm

The Sure Tomorrow insurance company wants to protect its clients' data. Our task is to develop a data transforming algorithm that would make it hard to recover personal information from the transformed data. This is called data masking, or data obfuscation. We are also expected to prove that the algorithm works correctly. Additionally, the data should be protected in such a way that the quality of machine learning models doesn't suffer. We don't need to pick the best model. For development a new algorithm we need:
- construct a theoretical proof using properties of models and the given task;
- formulate an algorithm for this proof;
- check that the algorithm is working correctly when applied to real data.
We will use a simple method of data masking, based on an invertible matrix.