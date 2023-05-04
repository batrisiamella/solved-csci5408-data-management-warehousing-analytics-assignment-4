Download Link: https://assignmentchef.com/product/solved-csci5408-data-management-warehousing-analytics-assignment-4
<br>
<strong>Objective:</strong>

<table>

 <tbody>

  <tr>

   <td width="616">·         The objective of this assignment is to understand BI framework, creating star/snowflake schema, and concept of sentiment and semantic analysis.</td>

  </tr>

 </tbody>

</table>

<strong>Assignment Rubric</strong>

<table>

 <tbody>

  <tr>

   <td width="94"> </td>

   <td width="104">Excellent(25%)</td>

   <td width="113">Proficient (15%)</td>

   <td width="109">Marginal (5%)</td>

   <td width="121">Unacceptable(0%)</td>

   <td width="83">Problem #whereapplied</td>

  </tr>

  <tr>

   <td width="94">Completeness</td>

   <td width="104">All required</td>

   <td width="113">Submission</td>

   <td width="109">Some tasks are</td>

   <td width="121">Incorrect and</td>

   <td width="83">Problem # 3</td>

  </tr>

  <tr>

   <td width="94">includingCitation</td>

   <td width="104">tasks arecompleted</td>

   <td width="113">highlights taskscompletion.However, missedsome tasks inbetween, whichcreated adisconnection</td>

   <td width="109">completed,which aredisjoint innature.</td>

   <td width="121">irrelevant</td>

   <td width="83"> </td>

  </tr>

  <tr>

   <td width="94">Correctness</td>

   <td width="104">All parts of the</td>

   <td width="113">Most of the given</td>

   <td width="109">Most of the</td>

   <td width="121">Incorrect and</td>

   <td width="83">Problem #2</td>

  </tr>

  <tr>

   <td width="94"> </td>

   <td width="104">given tasks arecorrect</td>

   <td width="113">tasks are correctHowever, someportions need</td>

   <td width="109">given tasks areincorrect. Thesubmission</td>

   <td width="121">unacceptable</td>

   <td width="83"> </td>

  </tr>

 </tbody>

</table>




<table>

 <tbody>

  <tr>

   <td width="94"> </td>

   <td width="104"> </td>

   <td width="113">minormodifications</td>

   <td width="109">requires majormodifications.</td>

   <td width="121"> </td>

   <td width="83"> </td>

  </tr>

  <tr>

   <td width="94">Novelty</td>

   <td width="104">The submission</td>

   <td width="113">The submission</td>

   <td width="109">The submission</td>

   <td width="121">There is no</td>

   <td width="83">Problem #1</td>

  </tr>

  <tr>

   <td width="94"> </td>

   <td width="104">contains novelcontribution inkey segments,which is a clearindication ofapplicationknowledge</td>

   <td width="113">lacks novelcontributions.There are someevidences ofnovelty,however, it is notsignificant</td>

   <td width="109">does not containnovelcontributions.However, thereis an evidence ofsome effort</td>

   <td width="121">novelty</td>

   <td width="83"> </td>

  </tr>

  <tr>

   <td width="94">Clarity</td>

   <td width="104">The written or</td>

   <td width="113">The written or</td>

   <td width="109">The written or</td>

   <td width="121">Failed to prove</td>

   <td width="83">Problem #1</td>

  </tr>

  <tr>

   <td width="94"> </td>

   <td width="104">graphical</td>

   <td width="113">graphical</td>

   <td width="109">graphical</td>

   <td width="121">the clarity. Need</td>

   <td width="83"> </td>

  </tr>

  <tr>

   <td width="94"> </td>

   <td width="104">materials, and</td>

   <td width="113">materials and</td>

   <td width="109">materials, and</td>

   <td width="121">proper</td>

   <td width="83"> </td>

  </tr>

  <tr>

   <td width="94"> </td>

   <td width="104">developed</td>

   <td width="113">developed</td>

   <td width="109">developed</td>

   <td width="121">background</td>

   <td width="83"> </td>

  </tr>

  <tr>

   <td width="94"> </td>

   <td width="104">applications</td>

   <td width="113">applications do</td>

   <td width="109">applications fail</td>

   <td width="121">knowledge to</td>

   <td width="83"> </td>

  </tr>

  <tr>

   <td width="94"> </td>

   <td width="104">provide a clearpicture of theconcept, andhighlights theclarity</td>

   <td width="113">not show clearpicture of theconcept. There isroom forimprovement</td>

   <td width="109">to prove theclarity.Backgroundknowledge isneeded</td>

   <td width="121">perform the tasks</td>

   <td width="83"> </td>

  </tr>

 </tbody>

</table>




<strong>Citation:</strong>

McKinney, B. (2018). The impact of program-wide discussion board grading rubrics on students’ and faculty

satisfaction. Online Learning, 22(2), 289-299.

<strong><u>Tasks</u></strong>

<ul>

 <li>This assignment requires you to submit programming codes on gitLab, and a single PDF</li>

</ul>

file on Brightspace.

<strong>Problem #1</strong>

<strong>Business Intelligence Reporting using Cognos</strong>

1 . Download the weather dataset available on <a href="https://www.kaggle.com/PROPPG-PPG/hourly-">https://www.kaggle.com/PROPPG-PPG/hourly-</a>

<u>weat he r-surface-brazil-southeast-region?select=sudeste.csv</u>

2 . Explore the dataset and identify data field(s) that could be measured by certain factors or dimensions. (Follow recorded lecture #18, and synchronous session #18)

<strong><em>Example</em></strong><strong>: </strong>In a Sales dataset, you may find a measurable field “total sales”, which could be analyzed by other factors such as, “products”, “time”, “location” etc. These factors are known as dimensions. Depending on the data, you may also find possibilities of slice and dice, i.e. analysis could be possible in more granular level; From <strong>total sales by city </strong>to <strong>total sales by store</strong>

3 . Write 1/2 page explanation on how did you select the measurable filed, i.e. fact and what are the possible dimensions. Include this part in your PDF file.

<ol start="4">

 <li>Clean the dataset, if required perform formatting. You can perform the cleaning and formatting using spreadsheet operation or programming script. If you use program add that in GitLab, if you use other methods, write the steps in the PDF file.</li>

</ol>

5 . Create Cognos account and import your dataset. Identify the dimensions, and create/import the dimension tables.

6 . Based on your understanding of the domain (please read the information/metadata available on the dataset source, i.e. Kaggle), create star schema or snowflake schema. Provide justification of your model creation in the PDF file.

<ol start="7">

 <li>In addition to justification, attach screenshot of the model (star schema or snowflake schema) in the PDF file.</li>

</ol>

<ol start="8">

 <li>Display visual analysis of the data in a suitable format, e.g. bar graph showing temperature change in terms of a suitable dimension. Add the screenshot of the analysis on the pdf or add a screen recording of the analysis on your .zip folder.</li>

</ol>

<strong>Problem #2</strong>

<strong>Sentiment Analysis – Java Program only</strong>

1 . To perform this task, you need to consider the processed news (“content or descriptions” only,

<table>

 <tbody>

  <tr>

   <td width="754">

    <table width="100%">

     <tbody>

      <tr>

       <td></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>

ignore other fields) that you obtained and stored in MongoDB in your previous assignment. If you could not perform/complete the task, then obtain the processed MongoDb News collection by contacting your TA Kethan (C c me in that email)

2 . Write a script to create bag-of-words for each news article. (<strong>code from online or other sources </strong><strong>are not accepted</strong>)

e.g. news 1 = “Canada is cold cold. I feel good not bad”

bow1 = {“Canada”:1, “is”:1, “cold”:2, “I”:1, “feel”:1, “good” : 1, “not” : 1, “bad” : 1}

You do not need any libraries. Just implement a simple counter using loop.

Compare each bag-of-words with a list of positive and negative words. You can download list of

<table>

 <tbody>

  <tr>

   <td width="743">

    <table width="100%">

     <tbody>

      <tr>

       <td></td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>

positive and negative words from online source(s). You do not need any libraries. Just perform word by word comparison with a list of positive and negative words that you can get from any online platform. E.g. negative words can be found here <a href="https://gist.github.com/mkulakowski2/4289441">https://gist.github.com/mkulakowski2/4289441</a>

3 . Tag each news as “positive”, “negative”, or “neutral” based on overall score. You can add an additional column to present your finding.

<table>

 <tbody>

  <tr>

   <td width="144">News Article</td>

   <td width="144">NewsDescription/content</td>

   <td width="143">match</td>

   <td width="145">polarity</td>

  </tr>

  <tr>

   <td width="144">1</td>

   <td width="144">Canada is cold cold. Ifeel good not bad</td>

   <td width="143">cold, good, not, bad</td>

   <td width="145">negative</td>

  </tr>

 </tbody>

</table>




<strong>Problem #3</strong>

<strong>Semantic Analysis</strong>

1 . For this task, consider the processed news collection that you created in Assignment 3 .

2 . Use the following steps to compute TF-IDF (term frequency-inverse document frequency)

<ol>

 <li>Suppose, you have 50 news articles (description or content only) that are stored in 50 JSON arrays. You need to consider these data points as the total number of</li>

</ol>

<strong>documents (</strong><strong><em>N</em></strong><strong>)</strong>. In this case <strong><em>N</em></strong>= 5 0

Now, use the search query “Canada”, “Moncton”, “Toronto”, and search in how many documents these words have appeared.

<table>

 <tbody>

  <tr>

   <td width="159">Total Documents</td>

   <td colspan="3" width="339">5 0</td>

  </tr>

  <tr>

   <td width="159">Search Query</td>

   <td width="76">Documentcontainingterm(df)</td>

   <td width="180">Total Documents(N)/ numberof documents term appeared(df)</td>

   <td width="84">Log10(N/df)</td>

  </tr>

  <tr>

   <td width="159">Canada</td>

   <td width="76">30</td>

   <td width="180">50/30</td>

   <td width="84">0.221848749</td>

  </tr>

  <tr>

   <td width="159">Moncton</td>

   <td width="76">5</td>

   <td width="180">5 0/ 5</td>

   <td width="84">1</td>

  </tr>

  <tr>

   <td width="159">Toronto</td>

   <td width="76">10</td>

   <td width="180">50/10</td>

   <td width="84">0.698970004</td>

  </tr>

 </tbody>

</table>




<ol>

 <li>Once you build the above table, you need to find which document has the highest occurrence of the word “Canada”. You can find this by performing frequency count of the word per document.</li>

</ol>

<table>

 <tbody>

  <tr>

   <td width="235">Term</td>

   <td colspan="2" width="248">Canada</td>

  </tr>

  <tr>

   <td width="235">Canada appeared in 30 documents</td>

   <td width="123">Total Words (<strong><em>m</em></strong>)</td>

   <td width="125">Frequency (<strong><em>f</em></strong>)</td>

  </tr>

  <tr>

   <td width="235">Article # 1</td>

   <td width="123">6</td>

   <td width="125">2</td>

  </tr>

  <tr>

   <td width="235">Article # 2</td>

   <td width="123">10</td>

   <td width="125">1</td>

  </tr>

  <tr>

   <td width="235">:</td>

   <td width="123">:</td>

   <td width="125">:</td>

  </tr>

  <tr>

   <td width="235">Article #3 0</td>

   <td width="123">8</td>

   <td width="125">1</td>

  </tr>

 </tbody>

</table>




<ol>

 <li>You should print the news article (programmatically), which has the highest relative frequency. You can find this by computing (<strong><em>f</em></strong>/<strong><em>m</em></strong>) .</li>

</ol>

<strong>Assignment 4 Submission Format:</strong>

<ul>

 <li></li>

</ul>

<table>

 <tbody>

  <tr>

   <td width="806">

    <table width="100%">

     <tbody>

      <tr>

       <td> </td>

      </tr>

     </tbody>

    </table></td>

  </tr>

 </tbody>

</table>

<ul>

 <li><strong>Compress all your reports/files into a single .zip file and give it a meaningful name.</strong></li>

</ul>

You are free to choose any meaningful file name, preferably – <strong>BannerId_Lastname_firstname_5408_A4 </strong>but avoid generic names like assignment-4.

<ul>

 <li><strong>Submit your reports only in PDF format.</strong></li>

</ul>

Please avoid submitting .doc/.docx and submit only the PDF version. You can merge all the reports into a single PDF or keep them separate. <strong>You should also include output (if any) and test cases (if any) in the</strong>

<strong>PDF file in the proper format (e.g. tables, charts etc. as required).</strong>

<ul>

 <li><strong>Your executable code/script needs to be submitted on https://git.cs.dal.ca/</strong></li>

</ul>