# 시스템 설계 스터디

## 스터디 내용

- 책: [가상 면접 사례로 배우는 대규모 시스템 설계 기초 - 알렉스 쉬](https://product.kyobobook.co.kr/detail/S000001033116)
- 학습 진행 범위: 주 40~60 page
- 기간: 2025.01.23 ~ 2025.02.27 (목, 변경 가능)
- 시간 및 장소: 매주 목요일 오후 9 ~ 11시 (2시간, 온라인)

## 일정

### 1주차(1.23): ▣ 1, 2, 3장: 1 ~ 50p → 50p
- 1장: 사용자 수에 따른 규모 확장성
- 2장: 개략적인 규모 추정
- 3장: 시스템 설계 면접 공략법

### 2주차(1.30): ▣ 4, 5장: 51 ~ 90p → 40p
- 4장: 처리율 제한 장치의 설계
- 5장: 안정 해시 설계

### 3주차(2.06): ▣ 6, 7, 8장: 91 ~ 140p → 50p
- 6장: 키-값 저장소 설계
- 7장: 분산 시스템을 위한 유일 ID 생성기 설계
- 8장: URL 단축기 설계

### 4주차(2.13): ▣ 9, 10장: 141 ~ 182p → 42p
- 9장: 웹 크롤러 설계
- 10장: 알림 시스템 설계

### 5주차(2.20): ▣ 11, 12, 13장: 183 ~ 246p → 64p
- 11장: 뉴스 피드 시스템 설계
- 12장: 채팅 시스템 설계
- 13장: 검색어 자동완성 시스템

### 6주차(2.27): ▣ 14, 15, 16장: 247 ~ 307p → 61p
- 14장: 유튜브 설계
- 15장: 구글 드라이브 설계
- 16장: 배움은 계속된다

## 참여자

- 강민우 (Back-end)
- 추호성 (Back-end)

## 진행 방식

- 각자 미리 정해둔 챕터 읽고 Github에 요약 → 리딩할 때 사용
- 챕터마다 질문 만들기 (github 이슈로 질문 작성)
    - 최대한 본인이 질문에 대한 답변 달아오기 (명확한 정답이 없을 확률이 높아 어떤 방식이 더 좋을지 토론)
- 주마다 한 명이 리딩하고, 해당 챕터에 대해서 공유 & 토론
    - 챕터마다 질문 뽑아서 토론 & 결론 정리
    - 읽으면서 인상깊었던 점, 중요하게 생각했던 것들 공유
    - 공부하면서 찾아봤던 추가적인 자료 공유

## 참고할 만한 링크

- [스터디 - Meet-Coder](https://github.com/Meet-Coder-Study/book-system-design-interview?tab=readme-ov-file)
- [스터디 - LIVID](https://github.com/Learning-Is-Vital-In-Development/23-7-SystemDesignInterview?tab=readme-ov-file)
- [System Design Fight Club](https://systemdesignfightclub.com/)
- [High Scalability](https://highscalability.com/)
- [ByteByteGo](https://bytebytego.com/)

## 책 레퍼런스 링크 모음

<details>
<summary>Chapter 1: Scale From Zero to Millions of Users</summary>

1. [Hypertext Transfer Protocol](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol)
2. [Should you go Beyond Relational Databases?](https://blog.teamtreehouse.com/should-you-go-beyond-relational-databases)
3. [Replication](https://en.wikipedia.org/wiki/Replication_(computing))
4. [Multi-master replication](https://en.wikipedia.org/wiki/Multi-master_replication)
5. [NDB Cluster Replication](https://dev.mysql.com/doc/refman/5.7/en/mysql-cluster-replication-multi-source.html)
6. [Caching Strategies](https://codeahoy.com/2017/08/11/caching-strategies-and-how-to-choose-the-right-one/)
7. [Scaling Memcache at Facebook](https://www.usenix.org/system/files/conference/nsdi13/nsdi13-final170_update.pdf)
8. [Single point of failure](https://en.wikipedia.org/wiki/Single_point_of_failure)
9. [Amazon CloudFront](https://aws.amazon.com/cloudfront/dynamic-content/)
10. [Sticky Sessions](https://docs.aws.amazon.com/elasticloadbalancing/latest/classic/elb-sticky-sessions.html)
11. [Active-Active for Multi-Regional Resiliency](https://netflixtechblog.com/active-active-for-multi-regional-resiliency-c47719f6685b)
12. [EC2 High Memory Instances](https://aws.amazon.com/ec2/instance-types/high-memory/)
13. [Running Stack Overflow](https://nickcraver.com/blog/2013/11/22/what-it-takes-to-run-stack-overflow/)
14. [NoSQL Use Cases](http://highscalability.com/blog/2010/12/6/what-the-heck-are-you-actually-using-nosql-for.html)
</details>

<details>
<summary>Chapter 2: Back-of-the-Envelope Estimation</summary>

1. [Google Back-Of-The-Envelope-Calculations](http://highscalability.com/blog/2011/1/26/google-pro-tip-use-back-of-the-envelope-calculations-to-choo.html)
2. [System Design Primer](https://github.com/donnemartin/system-design-primer)
3. [Latency Numbers Every Programmer Should Know](https://colin-scott.github.io/personal_website/research/interactive_latency.html)
4. [Amazon SLA](https://aws.amazon.com/compute/sla/)
5. [Google Cloud SLA](https://cloud.google.com/compute/sla)
6. [Azure SLA](https://azure.microsoft.com/en-us/support/legal/sla/)
</details>

<details>
<summary>Chapter 3: A Framework for System Design Interviews</summary>

_(외부 레퍼런스 없음)_
</details>

<details>
<summary>Chapter 4: Design a Rate Limiter</summary>

1. [Rate-limiting strategies](https://cloud.google.com/architecture/rate-limiting-strategies-techniques)
2. [Twitter Rate limits](https://developer.twitter.com/en/docs/twitter-api/rate-limits)
3. [Google Docs limits](https://developers.google.com/docs/api/limits)
4. [IBM Microservices](https://www.ibm.com/cloud/learn/microservices)
5. [AWS API Gateway throttling](https://docs.aws.amazon.com/apigateway/latest/developerguide/api-gateway-request-throttling.html)
6. [Stripe rate limiters](https://stripe.com/blog/rate-limiters)
7. [Shopify API limits](https://shopify.dev/api/usage/rate-limits)
8. [Redis Rate Limiting](https://engineering.classdojo.com/blog/2015/02/06/rolling-rate-limiter/)
9. [Rate limiter design](https://medium.com/@saisandeepmopuri/system-design-rate-limiter-and-data-modelling-9304b0d18250)
10. [Cloudflare rate limiting](https://blog.cloudflare.com/counting-things-a-lot-of-different-things/)
11. [Redis](https://redis.io/)
12. [Lyft rate limiting](https://github.com/envoyproxy/ratelimit)
13. [Rate limiters design](https://gist.github.com/ptarjan/e38f45f2dfe601419ca3af937fff574d)
14. [Edge computing](https://www.cloudflare.com/learning/serverless/glossary/what-is-edge-computing/)
15. [Iptables Rate Limiting](https://blog.programster.org/rate-limit-requests-with-iptables)
16. [OSI model](https://en.wikipedia.org/wiki/OSI_model#Layer_architecture)
</details>

<details>
<summary>Chapter 5: Design Consistent Hashing</summary>

1. [Consistent hashing](https://en.wikipedia.org/wiki/Consistent_hashing)
2. [Consistent Hashing Implementation](http://tom-e-white.com/2007/11/consistent-hashing.html)
3. [Amazon Dynamo](https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf)
4. [Cassandra Architecture](https://www.cs.cornell.edu/projects/ladis2009/papers/lakshman-ladis2009.pdf)
5. [Discord Elixir Scaling](https://blog.discord.com/scaling-elixir-f9b8e1e7c29b)
6. [Stanford CS168 Lecture](https://web.stanford.edu/class/cs168/l/l1.pdf)
7. [Google Maglev Load Balancer](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/44824.pdf)
</details>

<details>
<summary>Chapter 6: Design a Key-Value Store</summary>

1. [Amazon DynamoDB](https://aws.amazon.com/dynamodb/)
2. [Memcached](https://www.memcached.org/)
3. [Redis](https://redis.io/)
4. [Amazon Dynamo Paper](https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf)
5. [Apache Cassandra](https://cassandra.apache.org/_/index.html)
6. [Google Bigtable](https://static.googleusercontent.com/media/research.google.com/en//archive/bigtable-osdi06.pdf)
7. [Merkle Tree](https://en.wikipedia.org/wiki/Merkle_tree)
8. [Cassandra Architecture](https://cassandra.apache.org/doc/latest/cassandra/architecture/index.html)
9. [SSTable and LSM](https://www.igvita.com/2012/02/06/sstable-and-log-structured-storage-leveldb/)
10. [Bloom Filter](https://en.wikipedia.org/wiki/Bloom_filter)
</details>

<details>
<summary>Chapter 7: Design a Unique ID Generator</summary>

1. [UUID](https://en.wikipedia.org/wiki/Universally_unique_identifier)
2. [Flickr Ticket Servers](https://code.flickr.net/2010/02/08/ticket-servers-distributed-unique-primary-keys-on-the-cheap/)
3. [Twitter Snowflake](https://blog.twitter.com/engineering/en_us/a/2010/announcing-snowflake)
4. [Network Time Protocol](https://en.wikipedia.org/wiki/Network_Time_Protocol)
</details>

<details>
<summary>Chapter 8: Design a URL Shortener</summary>

1. [RESTful API Tutorial](https://restapitutorial.com/index.html)
2. [Bloom Filter](https://en.wikipedia.org/wiki/Bloom_filter)
</details>

<details>
<summary>Chapter 9: Design a Web Crawler</summary>

1. [US Library of Congress Archives](https://www.loc.gov/web-archives/)
2. [EU Web Archive](https://op.europa.eu/en/web/euwebarchive)
3. [Digimarc Watermarks](https://www.digimarc.com/products/digimarc-watermarks)
4. [Mercator Web Crawler](https://courses.cs.washington.edu/courses/cse454/09sp/papers/mercator.pdf)
5. [Web Crawling Survey](http://infolab.stanford.edu/~olston/publications/crawling_survey.pdf)
6. [Duplicate Content Issues](https://searchengineland.com/study-29-of-sites-face-duplicate-content-issues-80-arent-using-schema-org-microdata-232870)
7. [Rabin Fingerprinting](http://www.xmailserver.org/rabin.pdf)
8. [Bloom Filter Paper](https://courses.cs.washington.edu/courses/csep521/21wi/readings/bloom_cacm.pdf)
9. [Web Crawling Introduction](https://www.ics.uci.edu/~lopes/teaching/cs221W12/slides/Lecture05.pdf)
10. [PageRank Paper](http://ilpubs.stanford.edu:8090/422/1/1999-66.pdf)
11. [Google Dynamic Rendering](https://developers.google.com/search/docs/advanced/javascript/dynamic-rendering)
12. [Web Spam Detection](http://airweb.cse.lehigh.edu/2006/urvoy.pdf)
13. [IRLbot Paper](https://irl.cse.tamu.edu/people/hsin-tsang/papers/www2008.pdf)
</details>

<details>
<summary>Chapter 10: Design a Notification System</summary>

1. [Twilio SMS](https://www.twilio.com/sms)
2. [Nexmo SMS](https://www.vonage.com/communications-apis/sms/)
3. [SendGrid](https://sendgrid.com/)
4. [Mailchimp](https://mailchimp.com/)
5. [Exactly-Once Delivery](https://bravenewgeek.com/you-cannot-have-exactly-once-delivery/)
6. [Push Notifications Security](https://cloud.ibm.com/docs/mobilepush?topic=mobilepush-security-in-push-notifications)
7. [RabbitMQ Monitoring](https://www.datadoghq.com/blog/rabbitmq-monitoring/)
</details>

<details>
<summary>Chapter 11: Design a News Feed System</summary>

1. [Facebook News Feed](https://www.facebook.com/help/1155510281178725/)
2. [Neo4j Friend Recommendations](http://geekswithblogs.net/brendanpage/archive/2015/10/26/friend-of-friend-recommendations-with-neo4j.aspx)
</details>

<details>
<summary>Chapter 12: Design a Chat System</summary>

1. [Erlang at Facebook](https://www.diogenesjunior.com.br/wp-content/uploads/2020/05/EugeneLetuchy-ErlangatFacebook.pdf)
2. [Messenger Scale](https://www.theverge.com/2016/4/12/11415198/facebook-messenger-whatsapp-number-messages-vs-sms-f8-2016)
3. [Long Tail](https://en.wikipedia.org/wiki/Long_tail)
4. [Facebook Messages Technology](https://engineering.fb.com/2010/11/15/core-data/the-underlying-technology-of-messages/)
5. [Discord Message Storage](https://blog.discord.com/how-discord-stores-billions-of-messages-7fa6ec7ee4c7)
6. [Twitter Snowflake](https://blog.twitter.com/engineering/en_us/a/2010/announcing-snowflake)
7. [Apache ZooKeeper](https://zookeeper.apache.org/)
8. [WeChat Evolution](https://www.infoq.cn/article/the-road-of-the-growth-weixin-background)
9. [WhatsApp Encryption](https://faq.whatsapp.com/general/security-and-privacy/end-to-end-encryption/?lang=en)
10. [Slack Edge Cache](https://slack.engineering/flannel-an-application-level-edge-cache-to-make-slack-scale/)
</details>

<details>
<summary>Chapter 13: Design a Search Autocomplete System</summary>

1. [Facebook Typeahead](https://engineering.fb.com/2010/05/17/web/the-life-of-a-typeahead-query/)
2. [Building Prefixy](https://medium.com/@prefixyteam/how-we-built-prefixy-a-scalable-prefix-search-service-for-powering-autocomplete-c20f98e2eff1)
3. [Prefix Hash Tree](https://people.eecs.berkeley.edu/~sylvia/papers/pht.pdf)
4. [MongoDB](https://en.wikipedia.org/wiki/MongoDB)
5. [Unicode FAQ](https://unicode.org/faq/basic_q.html)
6. [Apache Hadoop](https://hadoop.apache.org/)
7. [Spark Streaming](https://spark.apache.org/streaming/)
8. [Apache Storm](https://storm.apache.org/)
9. [Apache Kafka](https://kafka.apache.org/)
</details>

<details>
<summary>Chapter 14: Design YouTube</summary>

1. [YouTube Statistics](https://www.omnicoreagency.com/youtube-statistics/)
2. [Demographics](https://blog.hubspot.com/marketing/youtube-demographics)
3. [CloudFront Pricing](https://aws.amazon.com/cloudfront/pricing/)
4. [Netflix on AWS](https://aws.amazon.com/solutions/case-studies/netflix-case-study/)
5. [Akamai](https://www.akamai.com/)
6. [BLOB](https://en.wikipedia.org/wiki/Binary_large_object)
7. [Streaming Protocols](https://www.dacast.com/blog/streaming-protocols/)
8. [Facebook Video Processing](https://www.cs.princeton.edu/~wlloyd/papers/sve-sosp17.pdf)
9. [Weibo Video Architecture](https://www.upyun.com/opentalk/399.html)
10. [Shared Access Signatures](https://docs.microsoft.com/en-us/rest/api/storageservices/delegate-access-with-shared-access-signature)
11. [Seattle Conference on Scalability: YouTube Scalability](https://www.youtube.com/watch?v=w5WVu624fY8)
12. [Understanding the Characteristics of Internet Short Video Sharing: YouTube as a Case Study](https://arxiv.org/pdf/0707.3670v1.pdf)
13. [Content Popularity for Open Connect](https://netflixtechblog.com/content-popularity-for-open-connect-b86d56f613b)
</details>

<details>
<summary>Chapter 15: Design Google Drive</summary>

1. [Google Drive](https://www.google.com/drive/)
2. [Upload file data](https://developers.google.com/drive/api/v3/manage-uploads)
3. [Amazon S3](https://aws.amazon.com/s3/)
4. [Differential Synchronization](https://neil.fraser.name/writing/sync/)
5. [Differential Synchronization Youtube Talk](https://www.youtube.com/watch?v=S2Hp_1jqpY8)
6. [How We've Scaled Dropbox](https://www.youtube.com/watch?v=PE4gwstWhmc)
7. [The rsync algorithm - Andrew Tridgell and Paul Mackerras (1996)](https://www.andrew.cmu.edu/course/15-749/READINGS/required/cas/tridgell96.pdf)
8. [Librsync](https://github.com/librsync/librsync)
9. [ACID](https://en.wikipedia.org/wiki/ACID)
10. [Dropbox Security Whitepaper](https://www.dropbox.com/static/business/resources/Security_Whitepaper.pdf)
11. [Amazon S3 Glacier](https://docs.aws.amazon.com/amazonglacier/latest/dev/introduction.html)

</details>

<details>
<summary>Chapter 16: The Learning Continues</summary>

**Real-world systems**

- [Facebook Timeline: Brought to You by the Power of Denormalization](http://highscalability.com/blog/2012/1/23/facebook-timeline-brought-to-you-by-the-power-of-denormaliza.html)
- [Scale at Facebook](https://www.infoq.com/presentations/Scale-at-Facebook/)
- [Building Timeline: Scaling up to hold your life story](https://engineering.fb.com/2012/01/05/web/building-timeline-scaling-up-to-hold-your-life-story/)
- [Erlang at Facebook](https://www.diogenesjunior.com.br/wp-content/uploads/2020/05/EugeneLetuchy-ErlangatFacebook.pdf)
- [Finding a needle in Haystack: Facebook’s photo storage](https://www.usenix.org/legacy/event/osdi10/tech/full_papers/Beaver.pdf)
- [Serving Facebook Multifeed: Efficiency, performance gains through redesign](https://engineering.fb.com/2015/03/10/production-engineering/serving-facebook-multifeed-efficiency-performance-gains-through-redesign/)
- [Scaling Memcache at Facebook](https://research.facebook.com/publications/scaling-memcache-at-facebook/)
- [TAO: Facebook's Distributed Data Store for the Social Graph](https://research.facebook.com/publications/tao-facebooks-distributed-data-store-for-the-social-graph/)
- [Amazon Architecture](http://highscalability.com/amazon-architecture)
- [Dynamo: Amazon’s Highly Available Key-value Store](https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf)
- [A 360 Degree View of the Entire Netflix Stack](http://highscalability.com/blog/2015/11/9/a-360-degree-view-of-the-entire-netflix-stack.html)
- [It’s All A/Bout Testing: The Netflix Experimentation Platform](https://netflixtechblog.com/its-all-a-bout-testing-the-netflix-experimentation-platform-4e1ca458c15)
- [Netflix Recommendations: Beyond the 5 stars (Part 1)](https://netflixtechblog.com/netflix-recommendations-beyond-the-5-stars-part-1-55838468f429)
- [Netflix Recommendations: Beyond the 5 stars (Part 2)](https://netflixtechblog.com/netflix-recommendations-beyond-the-5-stars-part-2-d9b96aa399f5)
- [Google Architecture](http://highscalability.com/google-architecture)
- [Google File System](https://pdos.csail.mit.edu/6.824/papers/gfs.pdf)
- [Differential Synchronization](https://neil.fraser.name/writing/sync/)
- [YouTube Architecture](http://highscalability.com/youtube-architecture)
- [Seattle Conference on Scalability: YouTube Scalability](https://www.youtube.com/watch?v=w5WVu624fY8)
- [Bigtable: A Distributed Storage System for Structured Data](https://storage.googleapis.com/pub-tools-public-publication-data/pdf/68a74a85e1662fe02ff3967497f31fda7f32225c.pdf)
- [Instagram Architecture: 14 Million users, Terabytes of Photos, 100s of Instances, Dozens of Technologies](http://highscalability.com/blog/2011/12/6/instagram-architecture-14-million-users-terabytes-of-photos.html)
- [The Architecture Twitter Uses to Deal with 150M Active Users, 300K QPS, a 22 MB/S Firehose, and Send Tweets in Under 5 Seconds](http://highscalability.com/blog/2013/7/8/the-architecture-twitter-uses-to-deal-with-150m-active-users.html)
- [Scaling Twitter: Making Twitter 10000 Percent Faster](http://highscalability.com/scaling-twitter-making-twitter-10000-percent-faster)
- [Announcing Snowflake](https://blog.twitter.com/engineering/en_us/a/2010/announcing-snowflake)
- [Timelines at Scale](https://www.infoq.com/presentations/Twitter-Timeline-Scalability/)
- [How Uber Scales Their Real-time Market Platform](http://highscalability.com/blog/2015/9/14/how-uber-scales-their-real-time-market-platform.html)
- [Scaling Pinterest - From 0 to 10s of Billions of Page Views a Month in Two Years](http://highscalability.com/blog/2013/4/15/scaling-pinterest-from-0-to-10s-of-billions-of-page-views-a.html)
- [Pinterest Architecture Update - 18 Million Visitors, 10x Growth,12 Employees, 410 TB of Data](http://highscalability.com/blog/2012/5/21/pinterest-architecture-update-18-million-visitors-10x-growth.html)
- [A Brief History of Scaling LinkedIn](https://engineering.linkedin.com/architecture/brief-history-scaling-linkedin)
- [Flickr Architecture](http://highscalability.com/flickr-architecture)
- [How We've Scaled Dropbox](https://www.youtube.com/watch?v=PE4gwstWhmc)
- [The WhatsApp Architecture Facebook Bought For $19 Billion](http://highscalability.com/blog/2014/2/26/the-whatsapp-architecture-facebook-bought-for-19-billion.html)

**Company engineering blogs**

- [Airbnb](https://medium.com/airbnb-engineering)
- [Amazon](https://aws.amazon.com/blogs/architecture/)
- [Asana](https://blog.asana.com/category/eng/)
- [Atlassian](https://blog.developer.atlassian.com/)
- [BitTorrent](https://engineering.bittorrent.com/)
- [Cloudera](https://blog.cloudera.com/)
- [Docker](https://www.docker.com/blog/)
- [Dropbox](https://dropbox.tech/)
- [eBay](https://tech.ebayinc.com/)
- [Facebook](https://engineering.fb.com/)
- [GitHub](https://github.blog/category/engineering/)
- [Google](https://developers.googleblog.com/)
- [Groupon](https://medium.com/groupon-eng)
- [HighScalability](http://highscalability.com/)
- [Instacart](https://tech.instacart.com/)
- [Instagram](https://instagram-engineering.com/)
- [LinkedIn](https://engineering.linkedin.com/blog)
- [Mixpanel](https://mixpanel.com/blog/)
- [Netflix](https://netflixtechblog.com/)
- [Nextdoor](https://engblog.nextdoor.com/)
- [PayPal](https://medium.com/paypal-tech)
- [Pinterest](https://medium.com/pinterest-engineering)
- [Quora](https://quoraengineering.quora.com/)
- [Reddit](https://www.redditinc.com/blog/topic/technology)
- [Salesforce](https://engineering.salesforce.com/)
- [Shopify](https://shopify.engineering/)
- [Slack](https://slack.engineering/)
- [Soundcloud](https://developers.soundcloud.com/blog/category/engineering)
- [Spotify](https://engineering.atspotify.com/)
- [Stripe](https://stripe.com/blog/engineering)
- [System Design Primer](https://github.com/donnemartin/system-design-primer)
- [Twitter](https://blog.twitter.com/engineering/en_us)
- [Thumbtack](https://medium.com/thumbtack-engineering)
- [Uber](https://eng.uber.com/)
- [Yahoo](https://yahooeng.tumblr.com/)
- [Yelp](https://engineeringblog.yelp.com/)
- [Zoom](https://medium.com/zoom-developer-blog)
</details>

<br><br>

