# Xiangfei Meng (孟祥飞)

   ![Selfie](img/panorama.jpg)  
   Xiangfei Meng currently works at [**Bigo**](https://www.bigo.sg/) as a **Staff Engineer**, specialized in Computer Vision (mainly about **Video Enhancement**), and **Deep Learning Inference Engine** (focused on GPU Acceleration for iPhone). Before he joined *Bigo* in March, 2018, he received the master's degree in Computer Science and Technology from [**Beihang University**](http://www.buaa.edu.cn/) (BUAA), under the supervision of Professor [Hong Qin](https://www.cs.stonybrook.edu/people/faculty/HongQin) in State Key Laboratory of Virtual Reality Technology and Systems (VRLAB), School of Computer Science and Engineering (SCSE). He received his bachelor's degree in Computer Science and Technology from [Civial Aviation University of China](http://www.cauc.edu.cn/zh/) (CAUC) as an "**Outstanding Graduate**" in 2015. He got the honorary title of "**Top-10 College Students in CAUC**" in Autumn 2014. After that, he passed the National Entrance Examination for Postgraduate for SCSE, BUAA in December 2014 as the **top-score student** and attended BUAA as a postgraduate in September 2015.

   His research interests include Computer Vision, Machine Learning, and Computer Graphics. Recently, he focused on Video Enhancement and Deep Learning Inference Engine on mobile devices.

## Work Experiences

| Time              | Company   | Title          | Working Field                                     |
| :---------------- | :-------- | :------------- | :------------------------------------------------ |
| 2018/03 - now     | Bigo      | Staff Engineer | Video Enhancement, Deep Learning Inference Engine |
| 2017/06 - 2017/08 | Microsoft | **Intern**     | Visual Studio                                     |

## Education

| Time              | School                             | Phase         | Ranking |
| :---------------- | :--------------------------------- | :------------ | :------ |
| 2015/09 – 2018/03 | Beihang University                 | Postgraduate  | Top 5%  |
| 2011/09 – 2015/06 | Civil Aviation University of China | Undergraduate | Top 5%  |
| 2008/09 – 2011/06 | Taiyuan No. 5 Middle School        | Senior High   | Top 30% |

## Skills
1. Experienced **C/C++** programming skills with good coding style.
2. Familiar with mobile GPU programming, especially **Metal**.
3. Familiar with **Computer Vision** and (a little) **Computer Graphics**.
4. **NOT** familiar with LeetCode.

## Company Projects

### 1. Deep Learning Inference Engine (2020)

- Deep learning inference engine on mobile devices. Focused on Metal for iPhone.


- Top-level inference speed on typical CNN models (mobilenet, resnet, densenet, etc.) among common commercial inference engines (TFLite, MNN, TNN, CoreML).


- Fastest Metal implementation of wingorad convolution compared with all available Inference Engines.


### 2. Video Super Resolution (2019)

- Video super resolution algorithms for both light-weight version (mobile device) and heavy-computation version (GPU server).
- Focused on the real-scenario application.
- [video demo]()

### 3. Data-Driven Face Animation (2018)

- Data-driven face animation on mobile devices. Track expression of the face captured by camera, and retarget it to a cartoon model in real time.
- 3DMM and linear optimization.
- Rendering with GLES 2.0.

## School Projects

### 1. Fish Motion Capture and Retargeting by Monocular Camera (2017)
   ![FishImg](img/experimental_result.png)

   Motion capture and retargeting of fish generally have difficulties in marker attachment and feature description of the soft body. 

   We present a contour-based feature extraction to get the motion pattern of a fish from camera. A two-level motion retargeting scheme is proposed to retarget the recorded motion to a new fish model, regardless of its body and fin proportions.

   With this technique, we can drive a hand-drawn fish or a fish-like character (say a mermaid, or a flower) to swim with the same motion style as the real one in the fish tank.

   **Publication**:  
   Xiangfei Meng, Junjun Pan, Hong Qin, Pu Ge. **Real-time Fish Animation Generation by Monocular Camera**. *Computers & Graphics*. 71(2018): 55-65. [[pdf](paper/XiangfeiCAG.pdf)]

   Xiangfei Meng, Junjun Pan, Hong Qin. **"Motion Capture and Retargeting of Fish by Monocular Camera."** *2017 International Conference on Cyberworlds (CW 2017), IEEE*, Chester, UK, September 20-22, 2017. [[pdf](paper/XiangfeiCW2017.pdf)][[video](img/FishDemo.mp4)] 

### 2. Part Implementation of STL (2016)
   Partly implemented the C++ standard template library (STL), including several types of containers (vector, list, deque), their corresponding iterators (ordinary iterator, constant iterator, reverse iterator), a few container adaptors (stack, queue, priority_queue) and some common algorithms (sort, find). Mainly used C++ features include low-level memory management, specialization and the part specialization of template, function object, etc.

### 3. Ray Tracer (2016)
   ![CornellBox](img/CornellBox.png)

   Implemented a ray tracer as an offline renderer. This renderer is equipped with a parser to analyze model files containing triangles and spheres. The scene is then rendered with global illumination, which includes effects of ambient, diffuse, specular, reflection, refraction, soft shadow and color bleeding. The rendering process is speeded up by OpenMP with thread-level parallelization.

### 4. Pascal Compiler (2015)
   ![Assembly](img/assembly.png)

   Implemented a Pascal Compiler using pure C++ without other lexical/syntax tools. The compiler parses Pascal source code and translates it to Intel-i386 assembly code. The assembled executable can run on Windows operating system. The compiler provides full support for nested function definitions, recursion callings of functions, and the parameter passing either by values or references.

### 5. Spammer Detection in Social Networks (2014)

   Spammer detection is a typical scenario of the application of classifiers. To detect spammers in social networks, we collected 4109 profiles from [Weibo](http://weibo.com/), extracted their features and delivered them to several classifiers. We implemented a Bayesian classifier and a C4.5 Decision Tree classifier. Bayesian classifier is theoretically optimal as long as the conditional probability densities functions are known, and Decision Tree is independent of dimensions. Through the 10-fold cross validation, the Bayes Classifier showed 58.3% in recall, 85.4% in precision, and 0.693 in F1-Measure, and the Decision Tree showed 60.1% in recall rate, 85.4% in precision, and 0.706 in F1-Measure.

   Publication:  
   孟祥飞, 徐路, 王思雨. 基于新浪微博的社交网络垃圾用户分析与检测[J]. 科技与创新, 2014(15):125-127. [[pdf](paper/基于新浪微博的社交网络垃圾用户分析与检测.pdf)]  
   张宇翔, 孙菀, 杨家海, 周达磊, 孟祥飞, 肖春景. 新浪微博反垃圾中特征选择的重要性分析[J]. 通信学报, 2016, 37(8):24-33. [[pdf](paper/新浪微博反垃圾中特征选择的重要性分析.pdf)]

### 6. Moving Object Tracking (2013)
   ![4cars](img/4cars.png)

   Moving object tracking is a classical problem of Computer Vision since it can provide essential information on the shape and motion of the foreground objects.

   We implemented a real-time moving object tracking system with static camera.

1. Segment foreground pixels with Gaussian Mixture Model (GMM), which is a pixel-wise process.
2. Employ a morphology-open filter to eliminate the salt-and-pepper noise, and a connected component identification to label the salient components as foreground objects.
3. Identify the correspondence between consecutive frames by a Max A Priori algorithm, and handle the splitting, merging, appearing and vanishing of objects.
4. Estimate trajectories of detected objects by a group of Kalman Filters.

   The system is robust to the slight shaking of the camera, and the gradual change of the light. It can reach 20 FPS with 640×480 resolution on my laptop equipped with a 2.9GHz CPU and 4GB memory.

## Contact
[MengXiangfei_job@163.com](mailto:MengXiangfei_job@163.com) (for recruiting business)  
[XiangfeiMeng@buaa.edu.cn](mailto:XiangfeiMeng@buaa.edu.cn) (for academic communication)

