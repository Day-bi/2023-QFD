# Abstract
1. Prior QFD studies were qualitative and expert-driven, often overlooking quantitative analysis of engineering characteristics (EC).

2. This study introduces a data-driven framework that extracts and quantifies customer requirements (CR) from reviews and EC from manuals.

3. The CR-EC relationships are visualized using co-occurrence analysis and Importance–Performance Analysis (IPA), offering practical insights for data-informed product development.

# Data description
collecting dataset. CRs from customer reviews in [Amazon.com](http://Amazon.com) .applied commment. for washing machine the

- First, we collect the data. To extract *Customer requirements(CRs)*, we gather reviews from customers on the targeted washing machine model on Amazon.com. The data collection period spans from May 2015 to March 3, 2023, as of the collection date. The reviews comprise date, rating, title and contents.

- CRs involves collecting customer reviews from [amazon.com](http://amazon.com) for a specific washing machine model. The collection period spans from May 2015, to March 3, 2023, as of the collection data.  The reviews comprise date, rating, title and content.

|Dates|Ratings|Titles|Bodys|
|------|---|---|---|
|2023-02-20|5|Durable Solid excellent	|Superlike|
|2023-02-14|5|Great quality|Fantastic|
|...|...|...|...|
|2019-11-05|5|Less noise	|Less noise	|
|...|...|...|...|

- Combined titles and bodies of product reviews into single content entries, filtered out duplicates, and cleaned the data for language model pretraining.

# Data preprocsssing
