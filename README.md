## Project Structure and Collaboration

To manage collaboration efficiently, our team worked in **three separate Python files**, each focusing on a distinct stage of the pipeline. This modular approach helped us avoid merge conflicts and allowed team members to contribute in parallel.

### 1. `data_retrieval_preprocessing_eda.py`
- Handles API setup and comment extraction from Reddit and YouTube
- Cleans and preprocesses data
- Performs initial exploratory data analysis (EDA)

### 2. `sentiment_analysis.py`
- Applies sentiment analysis using VADER
- Performs topic modeling using LDA
- Visualizes results and identifies key themes

### 3. `graph_network_analysis.py`
- Builds Reddit reply networks and YouTube egonets
- Computes centrality measures (degree, eigenvector)
- Exports network graphs for Gephi visualization

Each script was independently developed and tested, then integrated into our final project report. This structure provided clarity, minimized overlap, and improved our team’s workflow throughout the assignment.

## Sample Dataset for Submission

Due to the file size constraints, we have included **sample datasets** which are less than 10 MB instead of full data.

- `reddit_sample.json` – Subset of Reddit data (randomly sampled)
- `youtube_sample.json` – Subset of YouTube data (randomly sampled)

The full datasets (original Reddit: 25.8 MB, YouTube: 17.2 MB) were used during analysis but are excluded to meet size restrictions. All scripts will still work on these smaller files for demonstration purposes.

The link for our team channel is https://teams.microsoft.com/l/channel/19%3ASf8tMcnu2Dvym8UZjvz4-wen4ppADuBOs4SJkf710zI1%40thread.tacv2/General?groupId=c3ec10f7-438a-413d-8a4d-7638022e6409&tenantId=d1323671-cdbe-4417-b4d4-bdb24b51316b. We have added the teachers as the collaborators. 
