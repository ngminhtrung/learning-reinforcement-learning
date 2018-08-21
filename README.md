# Personal note on "Reinforcement Learning"

## Versions:
---
- 2018.08.17: Initialized by TrungNM9

## Thông tin chung
---
- Mô tả chung về Reinforcement Learning trên Wikipedia. [Link](https://en.wikipedia.org/wiki/Reinforcement_learning)
- Giới thiệu về Richard S. Sutton, người Canada, được coi là cha đẻ của Reinforcement Learning. [Link](https://en.wikipedia.org/wiki/Richard_S._Sutton)
- Phỏng vấn Richard S. Sutton:
    - [Medium - Interview with Dr.Richard Sutton: we might have strong AI algorithms by 2030](https://medium.com/syncedreview/interview-with-dr-richard-sutton-we-might-have-strong-ai-algorithms-by-2030-a1052332d878)
    - [KDnuggests - Exclusive: Interview with Rich Sutton, the Father of Reinforcement Learning](https://www.kdnuggets.com/2017/12/interview-rich-sutton-reinforcement-learning.html)

## Học Reinforcement như thế nào?
---
To be defined

Các câu hỏi trong quá trình học (tham khảo từ Mục tiêu của Khóa học CS243 bên dưới):
1. Define the key features of reinforcement learning that distinguish it from AI and non-interactive machine learning (as assessed by the exam)

2. Given an application problem (e.g. from computer vision, robotics, etc) decide if it should be formulated as a RL problem, if yes be able to define it formally (in terms of the state space, action space, dynamics and reward model), state what algorithm (from class) is best suited to addressing it, and justify your answer. (as assessed by the project and the exam)

3. Implement (in code) common RL algorithms including a deep RL algorithm (as
assessed by the homeworks)

4. Describe (list and define) multiple criteria for analyzing RL algorithms and evaluate algorithms on these metrics: e.g. regret, sample complexity, computational complexity, empirical performance, convergence, etc. (as assessed by homeworks and the exam)

5. Describe the exploration vs exploitation challenge and compare and contrast at least two approaches for addressing this challenge (in terms of performance,
scalability, complexity of implementation, and theoretical guarantees) (as assessed by an assignment and the exam)

## Tài liệu học tập:
---

### Sách
- **Reinforcement Learning: An Introduction**. Second edition, in progress. Richard S. Sutton and Andrew G. Barto c 2014, 2015. A Bradford Book. The MIT Press. [Link download](https://web.stanford.edu/class/psych209/Readings/SuttonBartoIPRLBook2ndEd.pdf). Note: Quyển này xuất bản lần đầu năm 1988 (1st edition), sau đó tác giả viết tiếp 2nd edition, tuy chưa xuất bản, nhưng đã public dưới dạng "draft complete" để mọi người đọc. 

### Toolkit 

Có thể code 100% mà không cần toolkit. Tuy nhiên có thể tham khảo Gym tại https://gym.openai.com/ để biết một vài ví dụ sử dụng reinforcement learning đã được implement sẵn (*Gym is a toolkit for developing and comparing reinforcement learning algorithms. It supports teaching agents everything from walking to playing games like Pong or Pinball.*).

Để xem các ví dụ đã được implement, xem mục "Environments" tại https://gym.openai.com/envs. Ở đây có các categories sau (tính đến 17.08.2018):
- Algorithms
- Atari
- Box2D
- Classic control
- MuJoCo
- Robotics
- Toy text

Ví dụ chọn bài toán kinh điển "cho taxi đi đón và trả khách" tại https://gym.openai.com/envs/Taxi-v2/ (trong category "Toy text"):
- Xem video minh hoạ ở bên phải của page
- Xem bài toán gốc được trình bày bởi Thomas G. Dietterich ở paper [Hierarchical Reinforcement Learning with the MAXQ Value Function Decomposition](https://www.jair.org/index.php/jair/article/view/10266), mục 3.1 A Motivating Example. 
- Xem hướng dẫn áp dụng environment "Taxi-v2" như thế nào (sử dụng Jupiter Notebook) tại [đây](https://www.oreilly.com/learning/introduction-to-reinforcement-learning-and-openai-gym)
- Xem source code của environment "taxi-v2" tại [đây](https://github.com/openai/gym/blob/master/gym/envs/toy_text/taxi.py). Chính là link ở cuối trang https://gym.openai.com/envs/Taxi-v2/

### Ví dụ mẫu để học

1. [Reinforcement Learning for Stock Trading](https://github.com/kaixids/Reinforcement-Learning-for-Stock-Trading):

    - Đây là Capstone Project Final Report của 1 bạn người Canada học Udacity Nano Degree.
    - Repo này hữu ích vì có report (giải thích logic) lẫn code để chạy.  


### Khóa học
- [MOOC Standford CS234: Reinforcement Learning](http://web.stanford.edu/class/cs234/index.html): Miễn phí
    - Giảng viên: [Emma Brunskill. Assistant Professor, Computer Science Stanford AI for Human Impact Lab](https://cs.stanford.edu/people/ebrun/)
    - Mô tả: 
        - Khóa học này mô tả toàn bộ lý thuyết cơ bản của Reinforcement Learning. 
        - Textbook là quyển *Reinforcement Learning: An Introduction* của Richard Sutton. 
        - Course materials của mỗi lecture sẽ bao gồm:
            - Một vài chương trong textbook
            - Slide bài giảng
            - Assignment kèm solution. 
        - Slide bài giảng không đơn thuần tóm tắt lại textbook, mà thêm cả suy luận và kiến thức của Emma Brunskill. Vì thế tốt nhất nên đọc cả textbook lẫn slide song song.
        - Assignment gồm cả phần viết (suy luận + toán), kèm code.
    - Tham khảo thêm bài giảng trong 2 tiếng của Emma Brunskill *A Tutorial on Reinforcement Learning* ở [đây cho phần 1](https://simons.berkeley.edu/talks/emma-brunskill-01-24-2017-1), và [đây cho phần 2](https://www.youtube.com/watch?v=8hK0NnG_DhY)    
    
- [MOOC Coursera: Machine Learning and Reinforcement Learning in Finance Specialization](https://www.coursera.org/specializations/machine-learning-reinforcement-finance): Miễn phí cho audit. 