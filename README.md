```
fly -t tutorial login -c http://concourse.traefik-pks1.tdovan.co/ -u test -p test



fly -t tutorial set-pipeline -p demo-cicd -c demo-cicd.yml --load-vars-from secrets/demo-cicd.yml
fly -t tutorial unpause-pipeline -p demo-cicd
```
