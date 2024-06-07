<h1>Assignment 1</h1>

[LINK] - https://www.kaggle.com/t/b04f415a66074f68b074d317d9fa3af9

[REFERENCES] -

https://piazza.com/class_profile/get_resource/lqt8bj4zlof29w/lr3r5r313a41qi
https://piazza.com/class_profile/get_resource/lqt8bj4zlof29w/lr7yt1vqdn52md
https://piazza.com/class_profile/get_resource/lqt8bj4zlof29w/lrdi7fy7o7p2dx
Speech and Language Processing (Chapter - 6)
In corpus linguistics, part-of-speech tagging (POS tagging or PoS tagging or POST), also called grammatical tagging is the process of marking up a word in a text (corpus) as corresponding to a particular part of speech, based on both its definition and its context.

https://paperswithcode.com/sota/part-of-speech-tagging-on-penn-treebank
Above URL shows the current state-of-the-art performance in PoS tagging on Penn Treebank Benchmark. While most of the entries in the leaderboard use a deep neural network architecture, classical models like HMM and MEMM are still being utilized given their ease of interpretation and their backing by exhaustive literature.

In the first assignment of this course, you will be tasked with implementing both HMM and MEMM taggers. Your models should be coded from scratch without use of any already existing implementations.



Please find more details about the assignment in the aforementioned link.


[UPDATE-2]

For HMM, I have heard a common doubt of probabilities becoming very low due to length of the sentences. To implement forward-backward algorithm, you can choose to initialize the matrices in a clever manner (refer to standard practices available online) and then incrementally update those matrices.

Refer to this page

https://stats.stackexchange.com/questions/274175/scaling-step-in-baum-welch-algorithm

Although this is not a part of forward-backward algorithm, implementing this step is solving the problem.

Refer to this page for more clarity on (get motivated to create) features for MEMM:

http://faculty.washington.edu/fxia/courses/LING572/maxent_adwait96.pdf



