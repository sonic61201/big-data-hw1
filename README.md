# ELK

  - [Elasticsearch](https://www.elastic.co/products/elasticsearch)
  - [Logstash](https://www.elastic.co/products/logstash)
  - [Kibana](https://www.elastic.co/downloads/kibana)

I use Elasticsearch and Logstash and Kibana that Mark taught us before.

My keyword of my search is "NFL", National Football League. Why I use it? Because I love football. 

Kibana has some tools to let me format my exported file, like counts, date, histogram and it can even show the map.   

I create the file Date5.csv with Metric: count and split rows with aggregation: date histogram and Field: @timestamp, interval: auto. I use the dashboard in Kibana to create the testmap.json file with a map to show when the comment create and where it post to twitter.

By the way, I found a great plugin for google chrome named  "[es-csv-exporter](https://github.com/minewhat/es-csv-exporter)" that could export the .csv file in Kibana Dashboard.
