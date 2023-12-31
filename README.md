# Visualizing Data with AWS S3 and QuickSight

Follow these steps to visualize your data easily:

## Steps:

1. **Get Your Data**: Download both .csv and .json files with your data.
<hr>

2. **Access AWS Console**: Log in to the AWS Management Console.
<hr>

3. **Create an S3 Bucket**: Inside AWS, go to S3 and create a new bucket with a name you prefer.
<hr>

4. **Upload .csv File**: In your new bucket, upload the .csv file.
<hr>

5. **Update .json**: Open the .json file and update line 5 (URI) to point to your .csv file, which you want to visualize.
<hr>

6. **Save and Upload .json**: Save the changes and upload the modified .json file back to your S3 bucket.
<hr>

7. **Open QuickSight**: In a new browser tab, access Amazon QuickSight. If it's your first time, activate it (but remember to deactivate within a month).
<hr>

8. **Create a Dataset**: Choose S3 as your data source and create a new dataset.
<hr>

![QS Data Set](/imgs/Screenshot%202023-09-17%20134631.png)
![QS Data Set](/imgs/Screenshot%202023-09-17%20134712.png)

<hr>

9. **Copy Manifest URL**: Return to your S3 bucket and copy the URL of the manifest.json file.
<hr>

10. **Connect**: Paste the URL within the QuickSight upload popup to establish the connection.

![QS URl DataSet](/imgs/Screenshot%202023-09-17%20134858.png)

<

![QS Data Set](/imgs/Screenshot%202023-09-17%20135016.png)




![QS Data Set](/imgs/Screenshot%202023-09-17%20135038.png)

<hr>


## Congratulations! You're now ready to visualize your dataset in QuickSight.

![QS Data Set](/imgs/Screenshot%202023-09-17%20150515.png)
