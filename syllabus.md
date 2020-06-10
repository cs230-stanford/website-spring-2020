---
layout: default
comments: false
keywords:

title: Syllabus
description: For all "Materials and Assignments", follow the deadlines listed on this page, not on Coursera! Assignments are usually due every Tuesday, 30min before the class starts.
buttons:
micro_nav: false
---

## Announcements
- **<span style='background-color: rgba(246,208,0,0.99);'>Please check out Piazza for an important announcement regarding revised final project deadlines.</span>**
- Please check out the [FAQ](/faq) for a list of changes to the course for the remote, spring offering.
- Please join [piazza](https://piazza.com/class/k8jbpjv3nd3lk) during the first week. This is where the majority of course announcements will be found.

## Syllabus

<table id="schedule" class="table table-bordered no-more-tables" style="width: 100%; font-size: 0.8em;">
    <colgroup>
        <col>
        <col>
        <col style="width: 25%;">
        <col style="width: 25%;">
        <col style="width: 50%;">
    </colgroup>
    <thead class="active" style="background-color:#f9f9f9" align="left">
        <th>Event</th>
        <th>Date</th>
        <th>In-class lecture</th>
        <th>Online modules to complete</th>
        <th>Materials and Assignments</th>
    </thead>
    <tbody>
        <tr>
            <td>Lecture&nbsp;1</td>
            <td> 04/07 </td>
            <td>
                <strong>Topics:</strong> <a href="/spring2020/lecture1.pdf">(slides)</a>
                <ul>
                    <li>Class introduction</li>
                    <li>Examples of deep learning projects</li>
                    <li>Course details</li>
                </ul>
            </td>
            <td>
                No online modules. If you are enrolled in CS230, you will receive an email on 04/07 to join Course 1 ("Neural Networks and Deep Learning") on Coursera with your Stanford email.
            </td>
            <td>
                No assignments.
            </td>
        </tr>
        <tr>
            <td id="Module_1" colspan="5" style="text-align:center; vertical-align:middle;background-color:#fffde7">
                <strong>Neural Networks and Deep Learning</strong> <a href="https://www.coursera.org/learn/neural-networks-deep-learning?specialization=deep-learning">(Course 1)</a>
            </td>
        </tr>
        <tr>
            <td>Lecture&nbsp;2</td>
            <td> 04/14 </td>
            <td>
                <strong>Topics: </strong>Deep Learning Intuition <a href="/spring2020/lecture2.pdf">(slides)</a>
            </td>
            <td><strong>Completed modules:</strong>
                <ul>
                    <li>C1M1: Introduction to deep learning <a href="/files/C1M1.pdf">(slides)</a></li>
                    <li>C1M2: Neural Network Basics <a href="/files/C1M2.pdf">(slides)</a></li>
                </ul>
                <strong>Optional Video</strong>
                <ul>
                    <li>Batch Normalization videos from C2M3 will be useful for the in-class lecture.</li>
                </ul>
            </td>
            <td>
                <strong>Quizzes (due at 9am PST):</strong>
                <ul>
                    <li>Introduction to deep learning</li>
                    <li>Neural Networks Basics</li>
                </ul>
                <strong>Programming Assignments (due at 9am PST)</strong>
                <ul>
                    <li>Python Basics with Numpy (Optional)</li>
                    <li>Logistic Regression with a neural network mindset</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Lecture&nbsp;3</td>
            <td> 04/21 </td>
            <td>
                <strong>Topics:</strong> Adversarial examples - GANs <a href="/spring2020/lecture3.pdf">(slides)</a>
                <ul>
                    <li>Attacking neural networks with Adversarial Examples and Generative Adversarial Networks</li>
                </ul>
                <strong>Optional Readings:</strong>
                <a href="https://arxiv.org/pdf/1412.6572.pdf">Explaining and Harnessing Adversarial Examples</a>, <a href="https://arxiv.org/pdf/1406.2661.pdf">Generative Adversarial Nets</a>, <a href="https://arxiv.org/pdf/1611.07004.pdf">Conditional GAN</a>, <a href="https://arxiv.org/pdf/1609.04802.pdf">Super-Resolution GAN</a>, <a href="https://arxiv.org/pdf/1703.10593.pdf">CycleGAN</a>
            </td>
            <td>
                <strong>Completed modules:</strong>
                <ul>
                    <li>C1M3: Shallow Neural Network <a href="/files/C1M3.pdf">(slides)</a></li>
                    <li>C1M4: Deep Neural Networks <a href="/files/C1M4.pdf">(slides)</a></li>
                </ul>
            </td>
            <td>
                <strong>Quizzes (due at 9am PST):</strong>
                <ul>
                    <li>Shallow Neural Networks</li>
                    <li>Key concepts on Deep Neural Networks</li>
                </ul>
                <strong>Programming Assignments (due at 9am PST):</strong>
                <ul>
                    <li>Planar data classification with a hidden layer</li>
                    <li>Building your Deep Neural Network: step by step</li>
                    <li>Deep Neural Network - Application</li>
                </ul>
            </td>
        </tr>
        <tr style="background-color:#ffb7bf">
            <td><strong>Project Meeting #1</strong></td>
            <td><strong>{{ site.course.project_timeline.proposal | date: site.course.project_timeline.syllabus_date_format }}</strong></td>
            <td><a href="/project/#proposal">Instructions</a></td>
            <td></td>
            <td>
                <strong>Meet with any TA between 4/06 and 4/22 to discuss your proposal.</strong>
            </td>
        </tr>
        <tr style="background-color:#b7ffbf">
            <td><strong>Project Proposal Due</strong></td>
            <td><strong>{{ site.course.project_timeline.proposal | date: site.course.project_timeline.syllabus_date_format }}</strong></td>
            <td><a href="/project/#proposal">Instructions</a></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td id="Module_2" colspan="5" style="text-align:center; vertical-align:middle;background-color:#fffde7">
                <strong>Improving Deep Neural Networks: Hyperparameter tuning, Regularization and Optimization</strong> <a href="https://www.coursera.org/learn/deep-neural-network?specialization=deep-learning">(Course 2)</a>
            </td>
        </tr>
        <tr>
            <td>Lecture&nbsp;4</td>
            <td> 04/28 </td>
            <td>
                <strong>Topics: </strong>Full-cycle of a Deep Learning Project (no slides)
            </td>
            <td>
                <strong>Completed modules:</strong>
                <ul>
                    <li>C2M1: Practical aspects of deep learning <a href="/files/C2M1.pdf">(slides)</a></li>
                    <li>C2M2: Optimization algorithms <a href="/files/C2M2.pdf">(slides)</a></li>
                </ul>
            </td>
            <td>
                <strong>Quizzes (due at 9am PST):</strong>
                <ul>
                    <li>Practical aspects of deep learning</li>
                    <li>Optimization Algorithms</li>
                </ul>
                <strong>Programming Assignments (due at 9am PST):</strong>
                <ul>
                    <li>Initialization</li>
                    <li>Regularization</li>
                    <li>Gradient Checking</li>
                    <li>Optimization</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td id="Module_3" colspan="5" style="text-align:center; vertical-align:middle;background-color:#fffde7">
                <strong>Structuring Machine Learning Projects</strong> <a href="https://www.coursera.org/learn/machine-learning-projects?specialization=deep-learning">(Course 3)</a>
            </td>
        </tr>
        <tr>
            <td>Lecture&nbsp;5</td>
            <td> 05/05 </td>
            <td>
                <strong>Topics:</strong> AI and Healthcare. Guest Speaker: Pranav Rajpurkar.
                <a href="/spring2020/lecture5_guest.pdf">(guest slides)</a>
                <a href="/spring2020/lecture5_main.pdf">(main slides)</a>
            </td>
            <td>
                <strong>Completed modules:</strong>
                <ul>
                    <li>C2M3: Hyperparameter Tuning, Batch Normalization <a href="/files/C2M3.pdf">(slides)</a></li>
                    <li>C3M1: ML Strategy (1) <a href="/files/C3M1.pdf">(slides)</a></li>
                    <li>C3M2: ML Strategy (2) <a href="/files/C3M2.pdf">(slides)</a></li>
                </ul>
            </td>
            <td>
                <strong>Quizzes (due at 9am PST, WED 5/6 (due to Coursera downtime)):</strong>
                <ul>
                    <li>Hyperparameter tuning, Batch Normalization, Programming Frameworks</li>
                    <li>Bird recognition in the city of Peacetopia (case study)</li>
                    <li>Autonomous driving (case study)</li>
                </ul>
                <strong>Programming Assignments (due at 9am PST, WED 5/6 (due to Coursera downtime)):</strong>
                <ul>
                    <li>Tensorflow</li>
                </ul>
            </td>
        </tr>
        <tr style="background-color:#ffb7bf">
            <td><strong>Project Meeting #2</strong></td>
            <td><strong>{{ site.course.project_timeline.milestone1 | date: site.course.project_timeline.syllabus_date_format }}</strong></td>
            <td><a href="/project/#milestone-1">Instructions</a></td>
            <td></td>
            <td>
                <strong>Meet with your assigned TA between 4/23 and 5/08 to discuss your first milestone report.</strong>
            </td>
        </tr>
        <tr style="background-color:#b7ffbf">
            <td><strong>Project Milestone #1 Due</strong></td>
            <td><strong>{{ site.course.project_timeline.milestone1 | date: site.course.project_timeline.syllabus_date_format }}</strong></td>
            <td><a href="/project/#milestone-1">Instructions</a></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td id="Module_4" colspan="5" style="text-align:center; vertical-align:middle;background-color:#fffde7">
                <strong>Convolutional Neural Networks</strong> <a href="https://www.coursera.org/learn/convolutional-neural-networks?specialization=deep-learning">(Course 4)</a>
            </td>
        </tr>
        <tr>
            <td>Lecture 6</td>
            <td> 05/12 </td>
            <td>
                <strong>Topics:</strong> Deep Learning Strategy (no slides)
                <br>
                <br>
                <strong>Optional Reading:</strong> <a href="https://arxiv.org/pdf/1603.07285.pdf">A guide to convolution arithmetic for deep learning</a>, <a href="https://arxiv.org/ftp/arxiv/papers/1609/1609.07009.pdf">Is the deconvolution layer the same as a convolutional layer?</a>, <a href="https://cs.nyu.edu/~fergus/papers/zeilerECCV2014.pdf">Visualizing and Understanding Convolutional Networks</a>, <a href="https://arxiv.org/pdf/1312.6034.pdf">Deep Inside Convolutional Networks: Visualizing Image Classification Models and Saliency Maps</a>, <a href="https://arxiv.org/pdf/1506.06579.pdf">Understanding Neural Networks Through Deep Visualization</a>, <a href="http://cnnlocalization.csail.mit.edu/Zhou_Learning_Deep_Features_CVPR_2016_paper.pdf">Learning Deep Features for Discriminative Localization</a>
            </td>
            <td>
                <strong>Completed modules:</strong>
                <ul>
                    <li>C4M1: Foundations of Convolutional Neural Network <a href="/files/C4M1.pdf">(slides)</a></li>
                    <li>C4M2: Deep Convolutional Models <a href="/files/C4M2.pdf">(slides)</a></li>
                </ul>
            </td>
            <td>
                <strong>Quizzes (due at 9am PST):</strong>
                <ul>
                    <li>The basics of ConvNets</li>
                    <li>Deep convolutional models</li>
                </ul>
                <strong>Programming Assignments (due at 9am PST):</strong>
                <ul>
                    <li>Convolutional Model: step by step</li>
                    <li>Convolutional Model: application</li>
                    <li>Keras Tutorial: This assignment is optional.</li>
                    <li>Residual Networks</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Lecture&nbsp;7</td>
            <td> 05/19 </td>
            <td>
                <strong>Topics:</strong> Interpretability of Neural Networks
                <a href="/spring2020/lecture7.pdf">(slides)</a>
            </td>
            <td>
                <strong>Completed modules:</strong>
                <ul>
                    <li>C4M3: ConvNets Applications (1) <a href="/files/C4M3.pdf">(slides)</a></li>
                    <li>C4M4: ConvNets Applications (2) <a href="/files/C4M4.pdf">(slides)</a></li>
                </ul>
            </td>
            <td>
                <strong>Quizzes (due at 9am PST):</strong>
                <ul>
                    <li>Detection Algorithms</li>
                    <li>Special Applications: Face Recognition & Neural Style Transfer</li>
                </ul>
                <strong>Programming Assignments (due at 9am PST):</strong>
                <ul>
                    <li>Car Detection with YOLO</li>
                    <li>Art Generation with Neural Style Transfer</li>
                    <li>Face Recognition</li>
                </ul>
            </td>
        </tr>
        <tr style="background-color:#ffb7bf">
            <td><strong>Project Meeting #3</strong></td>
            <td><strong>{{ site.course.project_timeline.milestone2 | date: site.course.project_timeline.syllabus_date_format }}</strong></td>
            <td><a href="/project/#milestone-2">Instructions</a></td>
            <td></td>
            <td>
                <strong>Meet with your assigned TA between 5/09 and 5/24 to discuss your second milestone report.</strong>
            </td>
        </tr>
        <tr style="background-color:#b7ffbf">
            <td><strong>Project Milestone #2 Due</strong></td>
            <td><strong>{{ site.course.project_timeline.milestone2 | date: site.course.project_timeline.syllabus_date_format }}</strong></td>
            <td><a href="/project/#milestone-2">Instructions</a></td>
            <td></td>
            <td></td>
        </tr>
        <tr>
            <td id="Module_5" colspan="5" style="text-align:center; vertical-align:middle;background-color:#fffde7">
                <strong>Sequence Models</strong>  <a href="https://www.coursera.org/learn/nlp-sequence-models">(Course 5)</a>
            </td>
        </tr>
        <tr>
            <td>Lecture&nbsp;8</td>
            <td> 05/26 </td>
            <td>
                <strong>Topics:</strong>
                <ul>
                    <li>Career Advice</li>
                    <li>Reading Research Papers</li>
                </ul>
                <strong>Optional Reading</strong>
                <ul>
                    <li><a href="https://www.cs.toronto.edu/~hinton/absps/JMLRdropout.pdf">Dropout: A Simple Way to Prevent Neural Networks from Overfitting</a></li>
                    <li><a href="https://arxiv.org/abs/1608.06993">DenseNet: Densely Connected Convolutional Networks</a></li>
                </ul>
            </td>
            <td>
                <strong>Completed modules:</strong>
                <ul>
                    <li>C5M1: Recurrent Neural Networks <a href="/files/C5M1.pdf">(slides)</a></li>
                </ul>
            </td>
            <td>
                <strong>Quizzes (due at 9am PST):</strong>
                <ul>
                    <li>Recurrent Neural Networks</li>
                </ul>
                <strong>Programming Assignments (due at 9am PST):</strong>
                <ul>
                    <li>Building a Recurrent Neural Network - Step by Step</li>
                    <li>Dinosaur Land -- Character-level Language Modeling</li>
                    <li>Jazz improvisation with LSTM</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td>Lecture&nbsp;9</td>
            <td> 06/02 </td>
            <td>
                <strong>Topics:</strong>
                <a href="/spring2020/lecture9.pdf">(slides)</a>
                <ul>
                    <li>Deep Reinforcement Learning</li>
                </ul>
                <br>
                <strong>Optional Reading:</strong>
                <ul>
                    <li><a href="https://web.stanford.edu/class/psych209/Readings/MnihEtAlHassibis15NatureControlDeepRL.pdf">Human-level control through deep reinforcement learning</a></li>
                    <li><a href="https://deepmind.com/research/publications/mastering-game-go-without-human-knowledge">Mastering the Game of Go without Human Knowledge</a></li>
                </ul>
            </td>
            <td>
                <strong>Completed modules:</strong>
                <ul>
                    <li>C5M2: Natural Language Processing and Word Embeddings <a href="/files/C5M2.pdf">(slides)</a></li>
                    <li>C5M3: Sequence-to-Sequence Models <a href="/files/C5M3.pdf">(slides)</a></li>
                </ul>
            </td>
            <td>
                <strong>Quizzes (due at 9am PST):</strong>
                <ul>
                    <li>Natural Language Processing and Word Embeddings</li>
                    <li>Sequence Models and Attention Mechanism</li>
                </ul>
                <strong>Programming Assignments (due at 9am PST):</strong>
                <ul>
                    <li>Operations on Word Vectors - Debiasing</li>
                    <li>Emojify!</li>
                    <li>Neural Machine Translation with Attention</li>
                    <li>Trigger Word Detection</li>
                </ul >
            </td>
        </tr>
        <tr>
            <td>Lecture&nbsp;10</td>
            <td> 06/09 </td>
            <td>
                <strong>Topics:</strong> <a href="/spring2020/lecture10.pdf">(slides)</a>
                <ul>
                    <li>Class wrap-up</li>
                    <li>What's next?</li>
                </ul>
            </td>
            <td></td>
            <td>
                <strong>Optional:</strong>
                <ul>
                    <li>If you’re interested in testing your ML/DL skills or preparing for job interviews in AI, you can take the <a href="https://www.workera.ai/candidates">Workera assessment</a></li>
                </ul>
            </td>
        </tr>
        <tr style="background-color:#ffb7bf">
            <td><strong>Project Meeting #4</strong></td>
            <td><strong>{{ site.course.project_timeline.poster_and_report | date: site.course.project_timeline.syllabus_date_format }}</strong></td>
            <td><a href="/project/#final-report">Instructions</a></td>
            <td></td>
            <td>
                <strong>Meet with your assigned TA between 5/23 and 6/9 (before class) to discuss your final project report.</strong>
            </td>
        </tr>
        <tr style="background-color:#b7ffbf">
            <td><strong>Project Final Report &amp; Video Due</strong></td>
            <td><strong>{{ site.course.project_timeline.poster_and_report | date: site.course.project_timeline.syllabus_date_format }}</strong></td>
            <td><a href="/project/#final-report">Instructions</a></td>
            <td></td>
            <td>
                <strong>Please read over the final project guidelines <a href="/project/#final-report">here</a> for information on the rubric and late submissions.</strong>
            </td>
        </tr>
    </tbody>
</table>

