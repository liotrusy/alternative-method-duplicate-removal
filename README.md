# Alternative Method Duplicate Removal

One constant theme that I come across in the world of programming is that there are different ways to solve problems, and some options require less steps or offer a better way to solve the problem.

During my training as a data scientist, I came across [this interesting analysis](https://github.com/dataquestio/solutions/blob/master/Mission350Solutions.ipynb) aimed at finding Profitable App Profiles for the App Store and Google Play Markets. As I inspected the code, I came a cross a stage of the data cleaning processs that I thought could (maybe) be improved. So, I dived in.

## The goal: Reduce the number of loops used to remove duplicate entries

In this project I explored the possibility to reduce the number of loops used to remove duplicate entries from the dataset. The original version of the solution can be found in [this link](https://github.com/dataquestio/solutions/blob/master/Mission350Solutions.ipynb). We won't focus on the entire analysis but only one the part that deals with Removing Duplicate Entries.

At the end of the project, I was able to improve the performance by 1.5x (reducing the number of loops needed by 10,840). Thanks for the authors of the orignial solution for the interesting analysis! It was an intereseting exploration.
