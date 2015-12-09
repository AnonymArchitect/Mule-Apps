# Mule-Apps

RabbitMQ Management
###################################################
http://192.168.99.100:8088/#/queues

Neo4J Management
###################################################
http://192.168.99.100:7474/browser/

Movies-DB WebService via Browser
###################################################
http://192.168.99.100:8080/RestService/rest/MovieDB/GetListOfMovies
http://192.168.99.100:8080/RestService/rest/MovieDB/GetMovieDesription?MovieName=Fight+Club

Movies-DB WebService via ESB
###################################################
http://localhost:8088/moviedb?service=GetListOfMovies
http://localhost:8088/moviedb?service=GetMovieDescription&param=Fight+Club

RabbitMQ Queues füllen via ESB
###################################################
http://localhost:8089/pub?queue=movies&msg=Test+03.12.2015:+Diese+Nachricht+geht+in+die+Queue:+movies
http://localhost:8089/pub?queue=log&msg=Test+03.12.2015:+Diese+Nachricht+geht+in+die+Queue:+log
http://localhost:8089/pub?queue=test&msg=Test+03.12.2015::+Diese+Nachricht+geht+in+die+Queue:+test
http://localhost:8089/pub?queue=BLOEDSINN&msg=Test+03.12.2015:+Diese+Nachricht+enthält+ungültige+Übergabeparameter:+BLOEDSINN
