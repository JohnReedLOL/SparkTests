Running Individual Tests

Often it is useful to run individual tests in Maven or SBT.

```bash
# sbt
$ build/sbt "test-only org.apache.spark.io.CompressionCodecSuite"
$ build/sbt "test-only org.apache.spark.io.*"
```