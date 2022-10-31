# Useful Regex
If `t` is the text to process...
```js
t.replaceAll('\n',' ').match(/(\w+ )?\d+:\d+(-\d+)?/g)
```

# Test Data
```
'|  11. How did Jesus’ resurrection fulfill Old Testament prophecy? (Job 19:25-27; Psalm 16:10; 30:3; Isaiah 26:19; Ezekiel 37:7-10)  12. Re-read John 8:31-36? What has the cross of Christ set us free for?  13. ‘Whenever we lose sight of the cross in our life, there is a need for Reformation.’ Where in the Church or your own life has the cross been lost sight of?  During the Reformation in the 16" Century, there were five phases of slogans that emerged that helped people grasp the essence of Christianity, life in Christ. They were:  Sola Scriptura (“Scripture alone”): The Bible alone is our highest authority. '
```
