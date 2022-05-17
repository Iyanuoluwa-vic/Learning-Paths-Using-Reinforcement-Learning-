# AlphaZero

Steps to Run

-dowload python 3

-Run main.py

-run visualization.py




For this assignment our group designed an agent-based system which over several iterations explores and learns an initially unknown environment, a five by five grid consisting of three different types of spaces, normal locations, pickup locations, and drop off locations. This agent was tasked with moving items from the aforementioned pickup locations to the aforementioned drop off locations, with the aim that over time, through reinforcement learning the agent would become more efficient with their movements and develop the capability to complete their assigned task in fewer iterations. Our group conducted five different experiments, each using a different combination of policies in order to better understand their effects on the agent and its ability to solve the task at hand. Each time an experiment is conducted, data we have deemed interesting, Q tables, the number of times each cell is visited, the percentage of cells visited, etc., is outputted to a file. Initially, we treated our Q Tables slightly differently from what we have seen thus far, instead of simply considering the Q values of each action of each cell, we also took into consideration the Q values of each action of each cell of each permutation of the location, whether or not the agent was holding a block, and the states of each of the pickup and drop off locations, as in whether or not blocks were available to pickup from pickup locations and whether or not drop off locations were full. Albeit interesting, this resulted in an overwhelming amount of data to comb through, thus in addition to these Q Tables, we also produced Q Tables simply representing the Q values of each action of each cell, while taking into consideration whether or not the agent was holding a block. This paper will serve as a medium for our group to communicate the findings of each run of each experiment, any interesting trends we may have noticed in each of these experiments, and which combination of learning algorithm and policy type, in our opinion based on our results, proved to be the most useful.



https://user-images.githubusercontent.com/33699531/164527303-8a003d43-79b9-41bb-b2ff-27ce87dd5775.mp4



