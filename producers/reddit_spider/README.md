# Reddit spider
Example Kafka producer.
This application scrapes a list of subreddits and stores results in Kafka.

Input: list of subreddits
Actions:
* Scan new posts
* Store:
    * Post text
    * Post metadata
    * Post author
    * (ignore comments)

