# Airline Sentiment

<table>
<tr>
<td>
  A sentiment analysis about the problems of each major U.S. airline.
  <br /><br />
  Context: Twitter data was scraped from February of 2015 and contributors were asked to first classify positive, negative, and neutral tweets, followed by categorizing negative reasons (such as "late flight" or "rude service").
</td>
</tr>
</table>

## Methodology and Insights

- Several pre-processing steps were applied to make the tweet text ready for learning, notably the removal of stop words and pruning of multiple inflections. 
- Two variants of vectorizer algorithms, Count Vectorizer and Term Frequency – Inverse Document Frequency, were employed as measures of term frequency and word originality, respectively. 
- The use of TD-IDF vectorization and logistic regression achieved the best testing accuracy. 
- The most common terms uncovered using TD-IDF include phone, pilot, plan--with possible sub-plans mentioned (platinum, plus, premier, premium), policy, order, relations, and representative. 
- More closely examining existing phone, pilot, and airline representative practices, as well as flyer plans, may reap further insights into each airline's customer experience.

## Built with

- [Natural Language Toolkit](https://www.nltk.org/) - A suite of libraries and programs for symbolic and statistical natural language processing.
- [Scikit-learn](https://scikit-learn.org/) - Simple and efficient tools for predictive data analysis.
- [NumPy](https://numpy.org/) - A library adding support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.
- [Pandas](https://pandas.pydata.org/) - A data analysis and manipulation library.
- [Matplotlib](https://matplotlib.org/) - A comprehensive library for creating static, animated, and interactive visualizations in Python.
