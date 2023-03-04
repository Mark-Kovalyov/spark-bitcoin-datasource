run:
	spark-submit \
        --verbose \
        --master local[*] \
        --driver-memory 1G \
        --executor-memory 1G \
        --deploy-mode client \
        --packages mayton:bitcoin-blocks-parser:1.0-SNAPSHOT \
        --class "mayton.bitcoin.Demo" \
        target/scala-2.12/bitcoin-demo_2.12-1.0.jar

package:
	sbt "clean; package"
