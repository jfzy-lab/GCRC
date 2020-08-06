# GCRC
This work focuses on multiple-choice questions in Gaokao Chinese. A highly challenging multiple-choice MRC task is from the Chinese University Admission Examination (Gaokao in Chinese), which called GCRC as follows.Unlike its counterparts which rely on numerical reasoning and specialized field knowledge, GCRC focuses on testing language comprehension. All of the questions in this dataset are answerable without any other knowledge.GCRC is a human-created multiple-choice reading comprehension dataset, collected from the Chinese University Admission Examination. GCRC requires the model to have the ability to handle long text and understand the information of an article that expresses, implies, or relies on. 
# DataSet
* data format
[{"id": "1", "source": "ahmn_101", "title": "null", "passage": ["北宋山水画中，画面经常或山峦重叠，树木繁盛；或境地宽远，视野开阔；或铺天盖地，丰盛错综；...今天你游江南或去关陕，所得到的自然美的欣赏、感受，也仍然是很不相同的，正如看董源或范宽的画一样。但它们尽管有着风格上的重要差异，却又仍然同属于上述“无我之境”的美学范畴。"], "question": "下列对原文观点的概括，正确的一项是", "opt": ["借助看似纯客观的自然描绘，北宋画家常能表现出农村景物或山水自然与人生的生存或生活之间牧歌式的亲切关系。", "山水画如果想要表现无我之境，就需要艺术家全景整体性描绘自然，使自然风光与自然景物基本充满整个画面。", "古典诗歌可以极为清晰地表达自我，而封建时代的画家却无法彰显自我，只能表达地主士大夫所理想化了的山水。", "游客在前往江南或者关陕等地观光之时，所得到的自然美的欣赏、感受虽然很有不同，但是都能踢会到无我之境。"], "answer": "A"}...
* The meaning of a key value
"id "is the serial number；
"source" is the source of the test paper；
"passage" is an article in the test paper；
“question” refers to the questions raised according to the passage；
"opt" is options；
"answer":is the correct answer.
* The amount of data
There were 3,179 articles and 7,886 questions, which were divided into train, dev and test, with the number of which being 6310,788,788 respectively.
