- Reference: https://blog.fabric.microsoft.com/en-us/blog/profiling-microsoft-fabric-spark-notebooks-with-sparklens
- Reference: https://blog.fabric.microsoft.com/en-us/blog/building-a-custom-sparklens-jar-for-microsoft-fabric/

- Download sbt version 0.13.18 at https://www.scala-sbt.org/download
- Modify build.sbt
- Modify \project\plugins.sbt
- Modify \src\main\scala\com\qubole\sparklens\QuboleJobListener.scala
- Modify \src\main\scala\com\qubole\sparklens\helper\HDFSConfigHelper.scala

- sbt compile
- sbt package

- The .jar file is available at \FabricSparklens\target\scala-2.12\sparklens_2.12-0.3.2.jar
