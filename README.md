# baike_spider
- Input: a txt file whose content consists of one key word upon multiple rows.
- Output: multiple csv files named after the key words, which are exported from Pandas dataframe. Baidu Baike has several titled paragraphs on each page, so the column names come from the title and the contents are stored as single rows in the dataframe. In other words, it's practical to retrieve the content by the title for each file when reloading it into a dataframe, just like using such data structures as a map or a dictionary.
