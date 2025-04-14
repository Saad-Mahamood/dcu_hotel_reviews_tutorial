# Review Summarization of Hotel Reviews

Price comparison websites such as [trivago](http://company.trivago.com) depend on reviews to enable users to make an informed choices when 
selecting the right accommodation. However, with a large number of reviews it is necessary to summarise the most salient 
points from a number of reviews. Even with the prevalence of LLMs to perform text summarization with large context windows 
there is still a need to understand and perform content selection prior to review summarization. In this lab we will use 
a bilingual open dataset of hotel reviews and perform the following steps:

* Data preparation and high-level analysis.
* Language classification 
* Sentiment analysis 
* Content selection
* Review summarization using an open source language model

List of resources:

* Hotel review dataset: [https://www.cs.cmu.edu/~jiweil/html/hotel-review.html](https://www.cs.cmu.edu/~jiweil/html/hotel-review.html). The downloaded zip files should be placed in the `resources/data` directory.

## Installation Instructions

1. Clone this GitHub repository: `git clone git@github.com:Saad-Mahamood/dcu_hotel_reviews_tutorial.git`
2. Ensure that you have Python 3.13.x or higher installed. Use `python3 --version` to check.
3. Change directory: `cd dcu_hotel_reviews_tutorial/`
4. Create a virtualenv using Python 3.13.x or higher: `python3 -m venv ./venv`
5. Activate the virtual environment:
   * `source ./venv/bin/activate`
6. Go back to the project directory: `cd ..`
7. Now install the `pip` dependencies: `pip install -r requirements.txt`
   * Alternatively, if you are using `poetry` for python dependency management: `poetry sync` 
8. Start jupyter lab and browse the notebooks in this directory: `jupyter lab`
   * Alternatively, you can use your own IDE editor instead.  