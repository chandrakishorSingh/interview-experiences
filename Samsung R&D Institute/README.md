# Summary

I got the opportunity to give a test for a 2 month summer internship at Samsung R&D Institute, Banglore(SRIB) in Nov 2021. During the internship, the interns were also given the chance to get the PPO(pre-placement offer) by clearing a DSA based test called Software Advanced Test(SWC Advanced Test) which was conducted internally by SRIB.

I was able to clear the intern test and later the SWC Adv. test as well. In this post, I've described my interview experience for the 2 month intern position and of the SWC advances test. At the end, I've also shared some resources and tips to prepare for these interviews.

## 2 Month Summer Internship

- **Profile**: MAGPIE Intern(SRIB have renamed their Software Intern to MAGPIE Intern 🙂)
- **Mode**: Online(WFH)
- **Stipend**: 50000 per month

### Coding Round

- **Date**: 17 November 2021
- **Platform**: CoCubes
- **# of problems**: 3
- **Duration**: 70 mins
- **Difficulty**: Similar to LeetCode Easy/Medium
- **Note**: From the GFG interview experience articles, I assumed that the platform will not allow to use STL(for C++). Although, as far as I remember, this was not the case and all standard libraries that are used in competitive programming were allowed.

#### Problem 1

I don't remember the exact question. But it was an array based problem. It's solution just required sorting the array and then traversing it once to do some processing.

#### Problem 2

This was based on Binary Tree. Every node had some integer value. For each node, you are required to find the sum of the value of all nodes that comes before this node in its inorder traversal.

This can easily be solved by one inorder traversal.

#### Problem 3

This was again based on Binary Tree. I don't remember the problem but it just required a simple DFS.

### Interview Round

- **Date**: 13 December 2021
- **Mode**: Virtual using Google Meet and some online text editor
- **Duration**: 60 min

The interview can be divided into 4 parts of introduction, project discussion, coding problem and general discussion.

#### Introduction

- I took 5 min to give my introduction.
- I've already memorized my introduction by this time as this is somethings which is asked in every interview. So, it's better to craft a crisp and informative intro of yours beforehand.
- This should include, along with the obvious information like your name, branch, college, course etc., your key skills and proof of work i.e., your projects. It would be nice if you have something that you can show like some app/website which is deployed. Otherwise, projects with well written README and screenshots are also good.

#### Project Discussion

- This took around 10 min.
- I brifely explained the 3 projects that I've mentioned in my resume. Interviewer asked me to explain any one project in depth. So, I chose the one which I thought displays my skills the best.
- I explained its working flow, the reason behind choosing the tech stack that was used to build it and answered some clarifying questions along the way using [STAR](https://en.wikipedia.org/wiki/Situation,_task,_action,_result) method. Interviewer was interested in knowing the reason behind building this project and how it's helpful to anyone. Also, he asked me about the challenges I faced during building this project.  

#### Coding Problem: Implementation of Dynamic Stack

- This took around 30 min.
- I was asked to implement a dynamic stack. It's a standard problem. I used resizing array to build this. A video solution can be found [here](https://www.youtube.com/watch?v=70wePMJiH2c). Another(and easier to code) approach would be to use linked list to implement stack.

#### General Discussion

- After the interview grill was over, I was asked if I had any questions for the interviewer.
- I asked about his typical day at SRIB, the team and the domain & projects that he and his team works on.

## Full Time Role Details(PPO offer)

- **Designation**: Engineer/ Sr. Engineer
- **Profile**: Developer
- **CTC**: 14L Annual Gross + 1L Joining Bonus + Retention Bonus of 1L, 1.5L, 1.5L, 1L at the end of 12th, 24th, 36th and 48th month respectively.

### PPO Process

- In order to get the PPO offer, there was 2 requirements.
- One of them was to pass the SWC Adv. test. This was mandatory in order to be eligible for PPO offer. Every intern was provided a maximum of 3 attempts to pass the SWC test.
- Second was feedback of the reporting manager under whom the intern was working. Depending upon the feedback of the manager, one additional tech interview was taken(only in case of low feedback, otherwise only passing SWC was enough).

### SWC Advanced Test

- **# of questions**: 1
- **Duration**: 180 min
- **# of submission attempts**: 100
- **# of test cases**: 50
- **Allowed Languages**: C++, Java, Python
- **Platform**
  - It was conducted on VDI(Virtual Desktop Interface).
  - Works only on Windows.
  - Takes complete control over the machine.
  - Visual Studio for C++, Eclipse for JAVA and PyCharm for Python was provided in VDI. Code needs to be submitted on a browser(Internet Explorer) based environment.
  - Video proctoring through mobile phone was done.
  - Very frustating process to install the necessary VDI software and mobile app.
- I cleared the SWC test in my final(3rd) attempt 🥲. Below are the questions that were asked in each of my attempts.

#### SWC Attempt 1

- The question was exactly same as the one explained in the [video](https://www.youtube.com/watch?v=Kc43BLd3JJM).
- I thought that I have 3 attempts to clear the test so took this 1st test quite lightly and didn't prepared much. This was the biggest mistake!

#### SWC Attempt 2

**Question** : An Athlete have to run some fixed distance. He can run with 5 different speeds. Each of the 5 speed is associated with some energy requirement for each kilometer. Faster the speed, more energy per kilometer will be required. The athlete can change his speed after every kilometer. Given the initial energy, find the minimum time required to travel the distance.

**Solution** : This is a straight forward unbounded knapsack problem. The constraints were quite small and may be even the brute force solution would've worked. Although, by mistake, I didn't look at the constraints and directly tried to implement the dp approach. Passed only 23/50 test cases.

#### SWC Attempt 3

- This time I prepared hard and solved many problems that were asked previously by SRIB.
- The problem was exactly same as the one given in [this](https://www.youtube.com/watch?v=OJX1umVCsJc) video.
- Finally cleared the test!

## Tips & Tricks

- Make sure to solve previously asked problems. There is very high chance that the questions might repeat. GFG interview experience articles are great way to do this. [Here](https://www.geeksforgeeks.org/internship-interview-experiences-company-wise/?ref=ghm#Samsung) is a collection of those articles for SRIB. Another collection of problems which helped a lot is [this](https://github.com/MohMaya/TargetSMSNG) repository.
- SWC problems are usually easy/medium but their input format might be non-traditional. Take [this](https://www.youtube.com/watch?v=OJX1umVCsJc) problem for example. The solution is just a simple DFS but creating/traversing the graph itself is little difficult in terms of implementation.
- Do all the setup for SWC one day before as installation will take some time.

## Learnings

- Keep practising even after you've got your desired job. Doing 1 problem a day keeps unemployment away.




