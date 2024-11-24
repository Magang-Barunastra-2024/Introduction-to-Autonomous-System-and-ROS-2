# Introduction to Autonomous System and ROS 2

| Nama  | Division        | Sub-Division  |
| ----- | ---------- | ---------- |
| Name here   | PGR | Sub-div |

## Autonomous System Diagram
> Create a diagram of the Roboboat Autonomous System as creative as you imagine, use online resources as your help.

`Put your diagram in here`

## Publisher - Subscriber Implementation
> 1. Create a Publisher and Subscriber code implementation of ROS 2 with these specifications:
> - ![image](https://github.com/user-attachments/assets/7ab5de13-509e-4316-bc36-88f7c92f310b)
> 2. Notes:
> - The blue boxes are nodes and the green boxes are topics.
> - Every time a new number is received, it's added to the number counter.
> - Check the message definition using "ros2 topic info [topic_name]" and "ros2 interface show [msg_type]" (or use rqt)
> - Push your code into a new branch named **"pubsub"**
> 3. Output Example:
```
__________________________________________
ros2 topic echo /number_count

data: 38
---
data: 40
---
data: 42
---
__________________________________________
```
