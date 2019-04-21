## Deploy

```
aws s3 cp . s3://www.vic-l.com \
    --recursive \
    --exclude '*.DS_Store' \
    --exclude 'README.md' \
    --profile vic-l \
    --cache-control public,max-age=1209600
```