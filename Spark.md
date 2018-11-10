## Welcome to the BigData-Journey!

# **Deep dive to Spark**

Spark is a unified in-memory computing engine and a set of libraries for parallel processing data on cluster of machine.

- Unified- supports wide range of tools from simple data loading to complex machine learning tasks and process streaming data over the same computation engine

### **Spark toolkit**

![](https://github.com/muthuv11/BigData-Journey/blob/master/Src-Images/01-Sparks%20toolkit.jpg)

### **Spark's Basic Architecture**

The cluster of machines that spark use to execute tasks is managed by Spark's standalone cluster manager or YARN or Mesos - which keep track of the available resources.

Spark Application consists of **driver** process and a set of **executor** processes.

**Driver** -  responsible 3 things

- maintaining information about the spark application
- responding to the user's program
- Analyzing, distributing and scheduling the work across the executors

**Executor** - carries out the actual work that the driver assigns and reports the state of computation to the driver node.

(In a spark local mode where the driver and executor are simply individual processes residing in a single machine)

 



