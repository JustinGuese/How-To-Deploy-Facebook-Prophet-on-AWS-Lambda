# [HOW TO] Deploy Facebook Prophet on AWS Lambda
Previous owner:

Read the full story [here](https://medium.com/@marc.a.metz/docker-run-rm-it-v-pwd-var-task-lambci-lambda-build-python3-7-bash-c7d53f3b7eb2).

# My (Justin) Additions

Added Alpaca API and yfinance, the structure had problems with the new lambda, now it is working

- If you want to add your lambda function unzip the upload2s3.zip, add your function at python/lib/.../lambda_function.py and rezip it. Pay attention that you do not zip the folder as well - the structure needs to be python/lib/...
- Upload it to S3 and proceed like mentioned in the article.