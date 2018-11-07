
# Repository Description 

## Downloading / Getting Libraries:
cv2:
`pip install opencv-python`  
editdistance:
`pip install editdistance`

## Flask Application:
Run app.py in flsk_content

## Flask Website Description:
1. Home
    - Breif Introduction of our project
2. About
    - Describes the model / technologies used
3. Text Analysis
    - Upload your text image and model infers your word
4. Application
    - Testing & Points to Consider & Going Forward

## Model / Repository Used:
1. [SimpleHTR](https://github.com/githubharald/SimpleHTR) 
2. [CTCWordBeamSearch](https://github.com/githubharald/CTCWordBeamSearch)

## PyMonngo Setup / Instructions 
1. Navigate to pymongo_ref folder in computer
2. run command through GitBash shell
`mongoimport -d g5 -c colt --type csv --file g5_tech.csv --headerline`
3. When you activate app with `python app.py`, from flsk_content folder, confirm database content is present on "about" route