```
$ fly -t osones set-pipeline -p demo-cicd -c demo-cicd.yml --load-vars-from secrets/demo-cicd.yml
$ fly -t osones unpause-pipeline -p demo-cicd
```
