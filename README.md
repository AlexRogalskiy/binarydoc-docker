# BinaryDoc, Binary code is the best Document

`BinaryDoc` generates Documents with rich diagrams from Binary files directly for Java.

This docker image needs to work together with `mysql` with specified startup options. An sample [BinaryDoc Docker Compose file](https://github.com/fuiny/binarydoc-docker-compose/blob/master/docker-compose.yml "Pre-configured BinaryDoc Docker Compose file") has been set up, and we can follow the [user guide](https://github.com/fuiny/binarydoc-docker-compose "User Guide") for the steps.


Sample Diagrams in Generated documents:

- Control Flow Graph for Java method bytecode
[![Control Flow Graph for method java.net.Inet6Address.getByAddress](https://github.com/fuiny/binarydoc-help/raw/master/samples/cfg_java_method_java.net.Inet6Address_getByAddress.png)](https://github.com/fuiny/binarydoc-help/blob/master/samples/cfg_java_method_java.net.Inet6Address_getByAddress.pdf)

- UML Sequence Diagram for Java method bytecode
[![UML Sequence Diagram for method java.net.Inet6Address.getByAddress](https://github.com/fuiny/binarydoc-help/raw/master/samples/uml_sequence_java_method_java.net.Inet6Address_getByAddress.png)](https://github.com/fuiny/binarydoc-help/blob/master/samples/uml_sequence_java_method_java.net.Inet6Address_getByAddress.pdf)

- UML Hierarchy Diagram for Java Class
[![UML Hierarchy Diagram for class java.nio.channels.FileChannel](https://github.com/fuiny/binarydoc-help/raw/master/samples/uml_java_java.nio.channels.FileChannel_hierarchy.png)](https://github.com/fuiny/binarydoc-help/blob/master/samples/uml_java_java.nio.channels.FileChannel_hierarchy.pdf)

- `Jar,Jmod` files Dependency Network Diagram (`sfdp` layout)
[![Dependency Network Diagram for OpenJDK 13](https://github.com/fuiny/binarydoc-help/raw/master/samples/dn_files_gav_openjdk-net.java-openjdk-13.0_sfdp.png)](https://github.com/fuiny/binarydoc-help/blob/master/samples/dn_files_gav_openjdk-net.java-openjdk-13.0_sfdp.pdf)


There are web sites containing the documentes and diagrams generated by `BinaryDoc`:
- [BinaryDoc for OpenJDK](https://openjdk.binarydoc.org/)
- [BinaryDoc for Android](https://android.binarydoc.org/)
- [BinaryDoc for Kotlin](https://kotlin.binarydoc.org/)
- [BinaryDoc for Groovy](https://groovy.binarydoc.org/)
- [BinaryDoc for Scala](https://scala.binarydoc.org/)
- [BinaryDoc for Spring framework](https://spring.binarydoc.org/)
- [BinaryDoc for Apache Cassandra](https://apache-cassandra.binarydoc.org/)
- [BinaryDoc for Apache Tomcat](https://apache-tomcat.binarydoc.org/)
- [BinaryDoc for Eclipse Jetty](https://eclipse-jetty.binarydoc.org/)

Sample Docker Compose Setup
- [BinaryDoc Docker](https://github.com/fuiny/binarydoc-docker-compose)

Support
- [Report Issues in Github](https://github.com/fuiny/binarydoc-dockerfile/issues)

License
- This docker image can be used for `FREE` forever
