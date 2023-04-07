# Algorithms for Data Science and Engineering

## ---  2023, Spring  ---

### Course Description

Data scientists, that peculiar mix of software engineer and statistician. The purpose of this course is to introduce some commonly used algorithms for data scientists and engineers. In particular, this class is meant to introduce randomized , statistical, algebraic, and optimized algorithms, with an emphasis on applications in the real life.

### Instructor: Yanhao Wang (王延昊)

- Ph. D. & Tenure-Track Associate Professor
- Office: Rm. East 115, Math. Building
- Email: <yhwang@dase.ecnu.edu.cn>

### Teaching Assistants

- Name: Jiaxi Pu (浦家希) & Jia Li (李佳)
- Office: Rm. East 102, Math. Building
- Email: <51215903021@stu.ecnu.edu.cn> & <jiali@stu.ecnu.edu.cn>

### Course Time

- Tuesday 9:50am -- 11:25am (Since February 28, 2023)
- Friday 1:00pm -- 2:35pm (Since March 3, 2023)

### Course Schedule

- 1: Introduction [[Slides_1](https://pan.baidu.com/s/16hZKOu4R2eysO5lVahWIMA)] (Code: 59aq) [[Slides_2](https://pan.baidu.com/s/1GaolUUupjFAlmaL6BDdzhg)] (Code: 17gr)
- 2: Sampling [[Slides_EN](https://pan.baidu.com/s/1_RL0BZDS-RIHvuZGONv3pw)] (Code: rwjf) [[Slides_CN](https://pan.baidu.com/s/1bcf20lrK6fBFQpZ8MVenEw)] (Code: ju5h) [[Tutorial](https://pan.baidu.com/s/1XqJTiJBCqFWETaWEui8cRQ)] (Code: twnd)
- 3: Probability Inequality [[Slides_EN](https://pan.baidu.com/s/1-SD8ynZqm4pNLhalQqjSzQ)] (Code: hqfc) [[Slides_CN](https://pan.baidu.com/s/10rKkzHuyf8dTTMMxj95QTw)] (Code: ugu5) [[Tutorial](https://pan.baidu.com/s/18rqYImr2HZkN9sTukh3BAg)] (Code: peuz)
- 4: Hashing [[Slides_EN](https://pan.baidu.com/s/1UMpOwbtjKufvZhNTmGuulw)] (Code: dg74) [[Slides_CN](https://pan.baidu.com/s/1Fl9Y77nagCk2gI7szLpBjw)] (Code: rmmh) [[LSH-1](https://pan.baidu.com/s/1KNxiUqXUX9TjqEUV7MGg6Q)] (Code: uzpf) [[LSH-2](https://pan.baidu.com/s/1hU416PR5nSCb5m7eh94KhQ)] (Code: 1cby) [[Tutorial](https://pan.baidu.com/s/1FuGlUZFMu-yI_QFS3WgpZA)] (Code: cw9d)
- 5: Sketch [[Slides_EN](https://pan.baidu.com/s/1CuQV8Db0dAC7F5umzEulXQ)] (Code: n5sh) [[Slides_CN](https://pan.baidu.com/s/1LPic-RmTSKVHqWBzNhbJYQ)] (Code: xuga)
- 6: Streaming Algorithm [[Slides_1](https://pan.baidu.com/s/1wCjC0fY14y1s2Lxwi9YAtg)] (Code: 5tua) [[Slides_2](https://pan.baidu.com/s/1HKme5nc2otFPkr1w3eLJ_g)] (Code: vcwr)
- 7: Markov Chain and Random Walk [[Slides_EN](https://pan.baidu.com/s/1SrjSNTIXsaxvVoTTKibQUw)] (Code: hjqy) [[Slides_CN](https://pan.baidu.com/s/1J1iqCG71BhPjIPfK_wXA9g)] (Code: 1cdf)
- Mid-Term Summary
- 8: Eigenvalue Computation [[Slides_EN](https://pan.baidu.com/s/1vtl5apn0fzE8GMIbAs9q-w)] (Code: akwx) [[Slides_CN](https://pan.baidu.com/s/1-PPpdnRv0deptgeJNsc0AQ)] (Code: 8g4t)
- 9: SVD and PCA [[Slides_EN](https://pan.baidu.com/s/18oDf3I5wT2y8Sz-I7aqtmA)] (Code: f4sn) [[Slides_CN](https://pan.baidu.com/s/1gh2QR8p8dzhOu2G9fGCW4w)] (Code: eiq7)
- 10: Matrix Decomposition
- 11: Linear & Integer Programming
- 12: Submodular Function
- 13: Community
- Summary

### Project

- **Project 1: Similarity Search**
  1. **Task Description:** Locality-Sensitive Hashing (LSH) is one of the most popular approaches to similarity search on high-dimensional data. The following dataset is an undirected graph representing the co-authorship between researchers. You need to construct an LSH scheme for similarity search: For any query node, you should find the top-10 nodes (excluding itself) whose neighbor sets have the highest Jaccard similarity scores with that of the query node. In the final report, please illustrate the performance of similarity search, such as accuracy, index time, query time, and space usage, etc.
  2. **Dataset** [[Download](https://pan.baidu.com/s/1ElIvXeScUikbx7HlY1-MQw)] (Code: thvw)
  3. **Report Template** [[Template](https://pan.baidu.com/s/1p7iB7yT_VF_B8PxV_T1OEw)] (Code: gg7i)
- **Project 2: Image Compression**
  1. **Task Description:** Principal component analysis (PCA) can be used to reduce the dimensions of the matrix (image) and project those new dimensions to reform the image that retains its qualities but is smaller in k-weight. You should choose 100 images from single class from the following dataset, and employ PCA to compress the images. In the final report, please illustrate the performance of image compression, such as reconstruction error, space saving, compressing rate, and case study, etc.
  2. **Dataset** [[Download](https://pan.baidu.com/s/1hYMMnxg2H3-8vuIXRPkD5w)] (Code: cs65)
  3. **Report Template** [[Template](https://pan.baidu.com/s/1p7iB7yT_VF_B8PxV_T1OEw)] (Code: gg7i)
- **Project 3: Recommender System**
  1. **Task Description:** Matrix Factorization (MF) and Nonnegative Matrix Factorization (NMF) are essential tools for recommendation. You should find and download a dataset containing user-item rating data. Then, you need to implement an MF or NMF-based algorithm to build a recommender system from the dataset. In the final report, please illustrate the performance of recommendation, such as reconstruction loss, accuracy, training time, and case study, etc.
  2. **Report Template** [[Template](https://pan.baidu.com/s/1p7iB7yT_VF_B8PxV_T1OEw)] (Code: gg7i)

### Textbook

- Ming Gao, Huiqi Hu: Algorithm Foundations of Data Science and Engineering [[JD]](https://item.jd.com/12863803.html) [[DangDang]](http://product.dangdang.com/29253772.html)
- Jure Leskovec, Anand Rajaraman and Jeff Ullman: [Mining of Massive Datasets](http://mmds.org)
- Avrim Blum, John Hopcroft, Ravindran Kannan: [Foundations of Data Science](https://home.ttic.edu/~avrim/book.pdf)

### Online Courses

- CS246 @ Stanford University by Jure Leskovec: [Mining Massive Data Sets](http://web.stanford.edu/class/cs246/)
- D&K @ Université Paris-Saclay by Albert Bifet: [IoT Stream Data Mining](https://albertbifet.com/dk-iot-stream-data-mining-2019-2020/)
- MTH 417 @ IIT Kanpur by Shalabh: [Sampling Theory](http://home.iitk.ac.in/~shalab/course1.htm)
- MATP6620 @ Rensselaer Polytechnic Institute by John E. Mitchell: [Integer and Combinatorial Optimization](https://homepages.rpi.edu/~mitchj/matp6620/)
