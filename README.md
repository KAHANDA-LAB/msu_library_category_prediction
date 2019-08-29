# msu_library_category_prediction

The dataset is stored in a TSV (Tab Separated Version) file, means each column is separated by a tab character. The file contains a header and 5 columns:
1. id. An identifier that is unique to the article.
2. url. The article is hosted under this URL by Montana State University ScholarWorks.
3. title. Title of the article. Multi-line titles are concatenated with a space.
4. abstract. Abstract of the article. Multi-paragraph abstracts are concatenated with a space.
5. subject. List of one or more LCSH (Library of Congress Subject Headings) terms related to the article.

In total, the dataset includes 1617 samples (articles) and 1175 unique LCSH terms.
