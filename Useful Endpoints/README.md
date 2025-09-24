
## `https://www.linkedin.com/jobs-guest/jobs/api/seeMoreJobPostings/search`
**This endpoint is used for LinkedIn's Job section. It is used to fetch Job information. <br>**
Unfortunately, the pagination is static and you can only parse 10 jobs in one request.
<br>
### Parameters:
```py
https://www.linkedin.com/jobs-guest/jobs/api/seeMoreJobPostings/search?
  keywords=Software+Engineer&  # The Job title you are searching for.
  location=United+States&  # The location of the Job. e.g. United+Kingdom or South+Africa
  start=0  # The cursor, 0 means itll return 10 starting from the very first job. 100 means it'll return from the 101th
```
#
