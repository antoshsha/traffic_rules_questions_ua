# Application of RAG for traffic rules data

You can find the dataset with questions in the `prompts` directory. It was collected from [this](https://pdr.infotech.gov.ua/tests/themes) website. It contains the questions for Ukrainian traffic rules test divided in json files by topics. The number of file corresponds to the number of the section in Ukrainian traffic rules. This dataset was created specifically for evaluation of RAG system, so all of the questions can be answered without reference images.

In the `traffic rules` directory you can find markdown files with Ukrainian traffic rules divided by topics and cleaned from irrelevant information. Th part about road signs is skipped due to the objectives of the study. 

In the file `full_traffic_rules.md` you can find the full cleaned text of Ukrainian traffic rules.
The text of traffic rules was taken from [here](https://zakon.rada.gov.ua/laws/show/1306-2001-п#Text).
