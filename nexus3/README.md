nexus 3.0.0-M2
==============

docker image 

https://support.sonatype.com/entries/102266026-Nexus-3-0-Technology-Preview-Milestone-2-Release- 

Usage example:

```
sudo docker run -d -p 8081:8081 --name nexus3 ollin/nexus3
```

- wait for a few seconds and open the browser at http://localhost:8081/
- Don't use it in a production environment! It is a technical preview!
