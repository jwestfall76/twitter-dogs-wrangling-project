# twitter-dogs-wrangling-project

This project gathers data from three different sources.  One .csv file directly from download, another file downloaded pprogrammatically using the requests
library and a third using Twitter's API in the form of a json.txt file.  Using pandas, three separate dataframes are created.

Each dataframe is examined for issues in regards to tidiness of data as well as quality.  Each issue is documented and then cleaned up.  After each dataframe is clean, all three are merged into one dataframe.

The wrangle_report.pdf file goes into further detail on how the three dataframes were assessed and cleaned.

The act_report.pdf file provides some insights from the wrangled dataframe.

