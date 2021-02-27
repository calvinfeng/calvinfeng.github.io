---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

# Index

[About me](http://calvin-playground.us-west-2.elasticbeanstalk.com/about)

## Blog Posts

[Physics of Major Scale](./001_physics_of_major_scale) attempts to explain why is Major scale
structured the way it is from a classical mechanics perspective.

## Projects

### [Machine Learning Notebook](https://calvinfeng.gitbook.io/machine-learning-notebook/)

This is my central repository for collecting all my notes and references on machine learning, which
includes a lot of mathematical derivations to better my own understanding of every algorithm I learned.

### [Guitar Playground](https://guitar-playground.herokuapp.com/)

Ever since September 2019, guitar has become a huge hobby of mine. I want to keep track of my
progress in learning the instrument. The best way to do that is through recording myself. I built
a little tool to display my recordings as a timeline. It pulls data from YouTube and render them
chronologically.

### [TensorFlow in Go](https://github.com/calvinfeng/tensorgo)

I was trying to run TensorFlow with Go using C binding. It worked! But in retrospective, I don't
think the effort is worth production usage. I'd rather build a gRPC server in Python and let Go talk
to Python to run TF models. Nowadays it's even easier to just deploy the model on a SageMaker endpoint.

<img alt="TensorGo" width="500" src="assets/screenshot/tensorgo.png" />

### [Popcorn the Movie Recommender](https://github.com/calvinfeng/popcorn)

I was experimenting with matrix factorization and built a recommendation engine using MovieLens'
IMDB data. It has 25 million movie ratings from 160,000 users on 60,000 movies. I don't host this
service anymore because I didn't want to pay for the AWS bills. However you can still see my
source code. The algorithm can be found in my machine learning notebook.

<img alt="Popcorn" width="500" src="assets/screenshot/popcorn.png" />

### [MegaPx](https://github.com/calvinfeng/megapx)

This is the first ever full stack project I'd built, when I was still using Ruby on Rails. That
sort of tells how "ancient" it is. It is supposed to allow users to upload high resolution images
and browse by location. It's basically a 500px clone. I built it for educational purpose. I actually
felt that Rails put too many constraints on me. I'd rather build without heavy-weighted frameworks.

<img alt="MegaPx" width="500" src="assets/screenshot/megapx.png" />

## Studies

In my spare time, I like to write a GitBook on materials I learned from textbooks or online courses.
However, for machine learning courses like CS229, CS232n, CS224n, they are captured in my machine
learning notebook. I ran out of quota to make more free GitBooks.

### [Probablistic Robotics](https://calvinfeng.gitbook.io/probabilistic-robotics/)

This is my textbook notes on Sebastian Thrun's Probablistic Robotics.

### [Georgia Tech OMSCS](https://calvinfeng.gitbook.io/omscs/)

This is my repostory for course notes from Georgia Tech OMSCS.

### [Go Notebook](https://calvinfeng.gitbook.io/gonotebook/)

This started out as a tutorial and then it beecame my personal references to Go syntax, tools, and
design patterns.

## Tools

Over the years I have worked with many different tools for different project needs. This is a high
level overview of my "gear" list.

<img alt="Golang" width="50" src="assets/img/golang.png" />
<img alt="TypeScript" width="50" src="assets/img/typescript.png" />
<img alt="JavaScript" width="50" src="assets/img/javascript.png" />
<img alt="Python" width="50" src="assets/img/python.png" />
<img alt="Docker" width="50" src="assets/img/docker.png" />
<img alt="React" width="50" src="assets/img/react.png" />
<img alt="ROS" width="50" src="assets/img/ros.png" />
<img alt="PostgreSQL" width="50" src="assets/img/postgresql.png" />
<img alt="Cassandra" width="50" src="assets/img/cassandra.png" />
<img alt="MongoDB" width="50" src="assets/img/mongodb.png" />
<img alt="Tensorflow" width="50" src="assets/img/tensorflow.svg" />
<img alt="Apache Kafka" width="50" src="assets/img/kafka.png" />
<img alt="AWS Elastic Beanstalk" width="50" src="assets/img/elasticbeanstalk.png">
<img alt="AWS SageMaker" width="50" src="assets/img/sagemaker.png">
