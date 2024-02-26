# The model comparison on debate tweets and political leanings on the 2016 U.S. Presidential Election (2021 Spring DM)

* Team members: Zixuan Zhu, Disheng Liu, Bobby Leigh

* Project paper: 
{
https://github.com/class-data-mining-master/2021-spring-dm-project-team07-dtpl/blob/277850015e4b9be962a13f12b68020a2b057b285/Final%20Project%20Paper.pdf
}

* Project slides: 
{
https://github.com/class-data-mining-master/2021-spring-dm-project-team07-dtpl/blob/00913f1d28d86e05d0c15a2e2315fd10a45d64f7/DATA%20MINGING.pdf
}

## Description
{
We will use the data provided in the project_topics.pdf, user-setB. We will be using several models like Logistic regression, classification tree and Neural Network in building the best model to predict political leanings. 
Logistic regression’s result can be easy to interpret and fast when running, the problem is we need to try multiple regression manually to find the best factors to use and the assumption that we have linearity between repose and factors, the CART can be beneficial because we can consider all possible outcomes, the neural network can run by itself without need of manual inputs, however it cost time and memory to run and can be hard to apply under large data we have, if we don’t make subsets of it to use.
Finally, in this project, we use PCA to reduce the dimension of TF-IDF matrix to form one input feature, and sentiment score as an another feature. After training models(random forest, neural network and so on), we get the model to predict personal political leaning based on tweeter text.
}

{
data.zip:
{
https://github.com/class-data-mining-master/2021-spring-dm-project-team07-dtpl/blob/817a3768b77235a1e6d7d306bb010d1c52d85413/project_data_resources_part_i.zip ,
https://github.com/class-data-mining-master/2021-spring-dm-project-team07-dtpl/blob/7abf87bb6690ea61c5f6fcd8a3887d628cf946ba/project_data_resources_part_ii.zip
｝

final_project.rmd: 
{
https://github.com/class-data-mining-master/2021-spring-dm-project-team07-dtpl/blob/5bcdd9c1647f04c1b8626bb3810327b8a43f26e9/final_project(latest_verson).Rmd
}

final_project.html:
{
https://github.com/class-data-mining-master/2021-spring-dm-project-team07-dtpl/blob/51bb80407b7386823f533c793cb3eae43842dfbf/final_project-latest_verson-.html
}
}

## Prerequisites
{
R packages: tidaytext, ggplot, dplyr, tm, tidyverse, caret, ROCR, rpart
}

## Authors
{
Zhu, Zixuan (email: ziz57@pitt.edu) Liu, Disheng (email: dil36@pitt.edu) Lei, Chen (email: chl276@pitt.edu)
}

## Acknowledgments

{
First, we would like to express our sincere gratitude to the lecturer of the class, Professor Lin, for her dedicated effort in teaching this class. Without her we can’t master the data mining skills in such a short time and complete such a difficulty project. Also thanks for professor Lin for providing basic ideas and data resources for our project. Second, we would like to say thanks to all the people who participate in this class and reach out their hands when we in need. Last, we think all of us deserve the generosity to praise ourselves for surviving through another tough semester in COVID. We hope we can see everyone in person in the future and everything resume to be normal soon. 
}

### Inspiration
{
https://www.kaggle.com/erikbruin/text-mining-the-clinton-and-trump-election-tweets
}

## License
{Provide the license information, e.g.,}
[MIT](https://choosealicense.com/licenses/mit/)
