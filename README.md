# dsci553-project-1-foundations-and-applications-of-data-mining-solved
**TO GET THIS SOLUTION VISIT:** [DSCI553 Project 1-Foundations and Applications of Data Mining Solved](https://mantutor.com/product/dsci553-foundations-and-applications-of-data-mining-solved-5/)


---

**For Custom/Order Solutions:** **Email:** mantutorcodes@gmail.com  

*We deliver quick, professional, and affordable assignment help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;116027&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;DSCI553 Project 1-Foundations and Applications of Data Mining Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
Competition Project

1. Overview of the Assignment

In this competition project, you need to improve the performance of your recommendation system from Assignment 3. You can use any method (like the hybrid recommendation systems) to improve the prediction accuracy and efficiency.

2. Competition Requirements

2.1 Programming Language and Library Requirements

a. You must use Python to implement the competition project. You can use external Python libraries as long as they are available on Vocareum.

b. You are required to only use the Spark RDD to understand Spark operations. You will not receive any points if you use Spark DataFrame or DataSet.

2.2 Programming Environment

Python 3.6, Scala 2.12, JDK 1.8 and Spark 3.1.2

2.3 Write your own code

Do not share your code with other students!!

3. Yelp Data

In this competition, the datasets you are going to use are from: https://drive.google.com/drive/folders/1SIlY40owpVcGXJw3xeXk76afCwtSUx11?usp=sharing

We generated the following two datasets from the original Yelp review dataset with some filters. We randomly took 60% of the data as the training dataset, 20% of the data as the validation dataset, and

20% of the data as the testing dataset.

A. yelp_train.csv: the training data, which only include the columns: user_id, business_id, and stars.

B. yelp_val.csv: the validation data, which are in the same format as training data.

C. We are not sharing the test dataset.

D. other datasets: providing additional information (like the average star or location of a business)

a. review_train.json: review data only for the training pairs (user, business)

b. user.json: all user metadata

c. business.json: all business metadata, including locations, attributes, and categories

d. checkin.json: user checkins for individual businesses

e. tip.json: tips (short reviews) written by a user about a business

f. photo.json: photo data, including captions and classifications

4. Task (8 points)

In the competition, you need to build a recommendation system to predict the given (user, business) pairs. You can mine interesting and useful information from the datasets provided in the Google Drive folder to support your recommendation system.

You must make an improvement to your recommendation system from homework assignment 3 in terms of accuracy. You can utilize the validation dataset (yelp_val.csv) to evaluate the accuracy of your recommendation system. There are two options to evaluate your recommendation system:

(1) Error Distribution: You can compare your results to the corresponding ground truth and compute the absolute differences. You can divide the absolute differences into 5 levels and count the number for each level as following:

&gt;=0 and &lt;1: 12345

&gt;=1 and &lt;2: 123

&gt;=2 and &lt;3: 1234

&gt;=3 and &lt;4: 1234

&gt;=4: 12

This means that there are 12345 predictions with &lt; 1 difference from the ground truth. This way you will be able to know the error distribution of your predictions and to improve the performance of your recommendation systems.

(2) RMSE Error: You can compute the RMSE (Root Mean Squared Error) by using following formula:

where Predi is the prediction for business i and Ratei is the true rating for business i. n is the total number of the business you are predicting.

Input format: (we will use the following commands to execute your code)

/opt/spark/spark-3.1.2-bin-hadoop3.2/bin/spark-submit competition.py &lt;folder_path&gt; &lt;test_file_name&gt; &lt;output_file_name&gt;

Param: folder_path: the path of dataset folder, which contains exactly the same file as the google drive Param: test_file_name: the name of the testing file (e.g., yelp_val.csv), including the file path Param: output_file_name: the name of the prediction result file, including the file path

Output format:

a. The output file is a CSV file, containing all the prediction results for each user and business pair in the validation/testing data. The header is “user_id, business_id, prediction”. There is no requirement for the order in this task. There is no requirement for the number of decimals for the similarity values. Please refer to the format in Figure 1.

Figure 1: Output example in CSV

b. You also need to write comments that include the description of your method (less than 300 words) in the first part of your program. The description should include the explanation of the models you are using, especially the way you improved the accuracy or efficiency of the system. We look forward to seeing creative methods. Please also report the error distribution, RMSE, and the total execution time on the validation dataset in the description. Figure 2 shows an example of the description file. If the comments are not included or the comments are not informative, there will be a one-point penalty.

Figure 2: An example of description file

Grading:

We will compare your prediction results against the ground truth. We will use our testing data to evaluate your recommendation systems and grade based on the accuracy using RMSE.

NOTICE: the current RMSE baseline is 1.03 for the validation dataset.

The final submission with the highest accuracy will receive an extra 6 points on the final grade. The second place will receive an extra 5 points. The third one will receive extra 4 points and so on until the sixth one will receive extra 1 point.

To be more like a competition, you could see a “Leaderboard” button in the “Competition” on Vocareum. Every time you submit the code, your RMSE for validation data will be scored and show up on the leaderboard.

Partial credit will be given if your RMSE for testing data cannot achieve the threshold. If your homework

3 accuracy is x, and competition is y, and you do not meet the threshold, you would get

(1-(y-0.98)/(x-0.98))*total score of the competition.

5. Submission

You need to submit your Python scripts on Vocareum with exactly the same name: ● competition.py

6. Grading Criteria

(% penalty = % penalty of possible points you get)

3. All submissions will be graded on Vocareum. Please strictly follow the format provided, otherwise you won’t receive points even though the answer is correct.

4. Do NOT use Spark DataFrame, DataSet, sparksql.

5. We will not conduct regrades on competition submissions.

6. There will be no points awarded if the total execution time exceeds 25 minutes.

7. Common problems causing fail submission on Vocareum/FAQ

(If your program runs seem successfully on your local machine but fail on Vocareum, please check these)

1. Try your program on Vocareum terminal. Remember to set python version as python3.6,

And use the latest Spark

/opt/spark/spark-3.1.2-bin-hadoop3.2/bin/spark-submit

2. Check the input command line format.

3. Check the output format, for example, the header, tag, typos.

4. Your Python script should be named as competition.py

5. Check whether your local environment fits the assignment description, i.e. version, configuration.
