# Upload any static site to AWS S3

> Uploads a build/ folder for static site to S3 bucket

![units-test](https://github.com/and-cru/andcru-s3-static-upload/workflows/units-test/badge.svg?branch=master)

## Usage

Example usage below

```yaml
uses: and-cru/andcru-s3-static-upload@v11
with:
  milliseconds: 500
  s3-bucket-name: <s3-bucket>
```