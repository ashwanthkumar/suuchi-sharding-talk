## Abstract
At Indix, all systems deal with huge volumes of data, which means, they need to be distributed. We started out with using open source distributed systems (like Hadoop, HBase, Solr, Spark, etc) to help accomplish some of our needs. Along the way, we’ve also had some problems where existing solutions wouldn’t really work for the use cases that we had or there was a large operation overheard associated with them. This pushed us to build a couple of “simple” distributed systems. As we built these we also realized that there were some common set of things to these. And, thus we built [Suuchi](http://github.com/ashwanthkumar/suuchi).

## About Author
Ashwanth Kumar is a Principal Engineer at Indix. His major interest lies in building and operating large data systems. When not dealing with data, he spends his time reading research papers in similar topics. 

## Demo Code Snippets
- [Example Service gRPC Spec](https://github.com/ashwanthkumar/suuchi/blob/19a075ca065112b1adcafbf9c75ac3a26fc9e1f9/suuchi-core/src/main/proto/suuchi.proto)
- [SuuchiRead](https://github.com/ashwanthkumar/suuchi/blob/582c66a0c0039312926a8c79b308567640f05306/suuchi-core/src/main/scala/in/ashwanthkumar/suuchi/rpc/SuuchiReadService.scala) and [SuuchiPut](https://github.com/ashwanthkumar/suuchi/blob/582c66a0c0039312926a8c79b308567640f05306/suuchi-core/src/main/scala/in/ashwanthkumar/suuchi/rpc/SuuchiPutService.scala)
- InMemory Store Recipe - https://ashwanthkumar.github.io/suuchi/recipes/inmemorydb/

## References
- https://speakerdeck.com/caitiem20/building-scalable-stateful-services-1
- http://www.i-programmer.info/news/136-open-source/8220-microsoft-puts-orleans-code-on-github.html
- [GRPC](http://www.grpc.io/)
- Consistent hashing and random trees: Distributed caching protocols for relieving hot spots on the World Wide Web - [Paper](https://github.com/papers-we-love/papers-we-love/blob/master/distributed_systems/consistent-hashing-and-random-trees.pdf)
- [Dynamo: The paper that changed the database world](https://vimeo.com/144994937)
- [RingPop](https://ringpop.readthedocs.io/) from Uber
- [Slicer: Auto-sharding for datacenter applications](https://www.usenix.org/system/files/conference/osdi16/osdi16-adya.pdf) Adya et al. (Google)  OSDI 2016
- [Gizzard](https://github.com/twitter/gizzard) on Twitter OSS
- [Bigtable: A Distributed Storage System for Structured Data](http://research.google.com/archive/bigtable.html) Fay Chang et al. (Google) OSDI 2006.
- [Dynamo: Amazon’s Highly Available Key-value Store](http://s3.amazonaws.com/AllThingsDistributed/sosp/amazon-dynamo-sosp2007.pdf) DeCandia et al. (Amazon) SOSP 2007.
- [Apache Cassandra](http://cassandra.apache.org/)
- [Project Voldemort](http://www.project-voldemort.com/voldemort/)

## Image Credits
- [Twitter by aguycalledgary](https://thenounproject.com/search/?q=twitter+bird&i=23267) from the Noun Project
- [team by Wilson Joseph](https://thenounproject.com/term/team/717083/) from the Noun Project
- [Earth by To Uyen](https://thenounproject.com/search/?q=internet+globe&i=318309) from the Noun Project
- [database by Kevin Woodland](https://thenounproject.com/search/?q=database&i=282705) from the Noun Project
- [options by Mert Güler](https://thenounproject.com/search/?q=toolkit&i=638516) from the Noun Project
- [SQL File by Viktor Vorobyev](https://thenounproject.com/search/?q=sql&i=342070) from the Noun Project
- [database by ✦ Shmidt Sergey ✦](https://thenounproject.com/search/?q=database&i=691819) from the Noun Project
- [sigma by Davo Sime from the Noun Project](https://thenounproject.com/search/?q=sigma&i=607382)
- [tools by Viktor Vorobyev from the Noun Project](https://thenounproject.com/search/?q=hammer&i=561830)
- [Info by Lance Weisser from the Noun Project](https://thenounproject.com/search/?q=info&i=91723)

## License
[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)  
<span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Suuchi - Toolkit for Application Layer Sharding</span> by [Ashwanth Kumar](https://ashwanthkumar.in) is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/). Based on a work at [https://github.com/ashwanthkumar/suuchi](https://github.com/ashwanthkumar/suuchi).
