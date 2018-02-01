Run this command to start s3 compitability tests aganist a castle instance
```
docker run -e S3_HOST=${HOSTIP} -v /logs/s3-tests/:/logs/s3tests/ quantum/s3-tests
```
