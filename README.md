# DonorsChoose
DonorsChoose is a nonprofit organization that allows individuals to donate directly to public school classroom projects.DonorsChoose.org receives hundreds of thousands of project proposals each year for classroom projects in need of funding. A large number of volunteers is needed to manually screen each submission before it's approved to be posted on the DonorsChoose.org website.

## Attribute

<table style="width:100%"> 
        <tr> 
            <th>Feature</th> 
            <th>Description</th> 
        </tr> 
        <tr> 
            <td>project_id</td> 
            <td>Unique ID related to proposed project</td> 
        </tr> 
        <tr> 
            <td>project_title</td> 
            <td>Title of the proposed project</td> 
        </tr> 
        <tr> 
            <td>project_grade_category</td> 
            <td>Grade Level of the student</td>           
        </tr>       
        <tr> 
            <td>project_subject_categories</td> 
            <td>Subject categorries of the proposed project</td> 
        </tr> 
         <tr> 
            <td>project_subject_subcategories</td> 
            <td>ubject sub  categorries of the proposed project</td> 
        </tr>        
        <tr> 
            <td>school_state</td> 
            <td>Location of school</td> 
        </tr> 
        <tr> 
            <td>project_essay_1</td> 
            <td>Essay of first application</td> 
        </tr>       
        <tr> 
            <td>project_essay_2</td> 
            <td>Essay of second application </td> 
        </tr> 
        <tr> 
            <td>project_essay_3</td> 
            <td>Essay of third application </td> 
        </tr>  
        <tr> 
            <td>project_essay_4</td> 
            <td>Essay of fourth application </td> 
        </tr>        
        <tr> 
            <td>teacher_id</td> 
            <td>Unique ID of the teacher of proposed Project</td> 
        </tr>          
        <tr> 
            <td>teacher_prefix</td> 
            <td>Prefix of teacher Title </td> 
        </tr>         
        <tr> 
            <td>teacher_number_of_previously_posted_projects</td> 
            <td>Number of project submitted by the teacher previously</td> 
        </tr> 
    </table> 
    
## Objective
The objective is to predict whether or not a DonorsChoose.org project proposal submitted by a teacher will be approved.

#### t-SNE on Donors Choose the dataset
<ul>
<li> Plot t-SNE plots with  feature set categorical, numerical features + text data (BOW,TFIDF,AVG W2V,TFIDF W2V).</li>
</ul>
        
#### KNN on Donors Choose the dataset
<ul>
<li> Find the best hyper-parameter using k-fold cross-validation, simple cross-validation, GridSearchCV or RandomizedSearchCV    to get the maximum AUC value.</li></ul>
        
#### Naive Bayes on Donors Choose the dataset
<ul>
<li>Find the best hyper-parameter using the Gridsearchcv or random search to get the maximum AUC value.
<li>plotting the ROC curve and print the confusion matrix.
<li>Find the top features and feature names using values of the `feature_log_prob_` parameter of MultinomialNB.
</ul>
        
#### Logistic Regression on Donors Choose dataset.
<ul>
<li>Use bigram BOW and TFIDF in the text data.
<li>Find the best hyper-parameter using the grid-search-cv or random search to get the maximum AUC value.
<li>plotting the ROC curve and print the confusion matrix.</ul>
        
#### SVM on Donors Choose a dataset
<ul>
<li>Find the best hyper-parameter using a grid-search-cv or random search to get the maximum AUC value.
<li>plotting the ROC curve and print the confusion matrix.</ul>

#### Decision Trees on Donors Choose the dataset
<ul>
<li>Find the best hyper-parameter using the grid-search-cv or random search to get the maximum AUC value.
<li>Visualize the decision tree with Graphviz.</ul>

#### Random Forests GBDT on Donors Choose the dataset
<ul>
<li>Find the best hyper-parameter using the grid-search-cv or random search to get the maximum AUC value.
<li>plotting the ROC curve and print the confusion matrix.</ul>

#### K means Agglomerative DBSCAN clustering algorithms on Donors Choose the dataset: 
<ul>
<li>Feature_selection using SelectFromModel        
<li>K-Means Clustering: Find the best ‘k’ using the elbow-knee method (plot k vs inertia_)
<li>Agglomerative Clustering: Apply the agglomerative algorithm on a different number of clusters. 
<li>DBSCAN Clustering: Find the best ‘eps’ using the elbow-knee method.</ul>

