# Algorithmic Machine Learning
This repository contains Jupyter Notebooks for the Algorithmic Machine Learning Course at Eurecom.

## Objectives of the course
The goal of this course is mainly to offer students to gain hands-on experience on Data Science projects. It nicely merges the theoretical concepts students can learn in our courses on machine learning and statistical inference, and systems concepts we teach in distributed systems.

Notebooks require to address several challenges, that can be roughly classified in:

* Data preparation and cleaning
* Building descriptive statistics of the data
* Working on a selected algorithm, e.g., for building a statistical model, for running parallel Monte Carlo simulations and so on...
* Working on experimental validation

## Technical notes
Students will use the EURECOM cloud computing platform to work on Notebooks. Our cluster is managed by [Zoe](http://zoe-analytics.eu/), which is a container-based analytics-as-a-service system we have built. Notebooks front-end run in a user-facing container, whereas Notebooks kernel run in clusters of containers. For this course, we focus on Apache Spark kernel.

Our Notebooks are configured to use Spark Python API. This choice is motivated by the heterogeneity we expect from our students' background.

## Sources and acknowledgments
The majority of the Notebooks we use in our lectures are based on use cases illustrated in the book [Advanced Analytics with Spark](http://shop.oreilly.com/product/0636920035091.do), by Sandy Ryza, Uri Laserson, Sean Owen & Josh Wills.

Some Notebooks are instead based on publicly available data, for which we defined the tasks to complete.

Finally, some Notebooks are private, and cannot be pushed to this repository. This is the case for industrial Notebooks, taking the form of use cases by Data Scientists from companies we are in contact with.

Finally, all this could not be achieved without the skills of [Duc-Trung Nguyen](http://www.eurecom.fr/en/people/nguyen-duc-trung), PhD student in the Distributed Systems Group at Eurecom.
