# Simple computer vision calculator
For the purposes of this projects I'm using a popular MNIST database of handwritten digits in order to simulate a possible application of machine learning. For example a calculator that can read handwritten digits and then give us the answer. The database can be imported using scikit-learn package.

Since I didn't have a dataset of mathematical symbols I wanted to explore artificial training set expansion by augmenting a few self made photos. For each mathematical operation that is considered by the program I made 6 handwritten symbols after which they undergone series of rotations and translations until there was about 1000 of each symbol ready to be added to the training set. The model is performing really well with symbols.

![image](https://user-images.githubusercontent.com/23265032/132756745-fd60ddee-04c5-483b-8141-78ac9806cb46.png)

![image](https://user-images.githubusercontent.com/23265032/132756835-afd9afc5-a1f4-4a05-a79c-1e864115d0a3.png)

At the end I present a few random examples from data. Should there be a need for a simple calculator that reads digits from MNIST dataset this one performs pretty OK and easily expandable by changing and carefully training any model in the future.

![image](https://user-images.githubusercontent.com/23265032/132756970-e1e3da5d-6e15-4a02-bb87-42917e9965f2.png)

![image](https://user-images.githubusercontent.com/23265032/132756872-abc86a6a-16e5-4343-9b09-79a6da0fe7e9.png)

![image](https://user-images.githubusercontent.com/23265032/132756895-d4e14c04-7ce4-4fef-a658-3468a8670ffd.png)

![image](https://user-images.githubusercontent.com/23265032/132756922-3899c415-15a9-4b3d-b405-36669b76ff2d.png)

![image](https://user-images.githubusercontent.com/23265032/132756936-37c96e64-5e69-49fa-a7e1-f3856e58629f.png)
