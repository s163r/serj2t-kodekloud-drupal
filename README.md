# serj2t-kodekloud-drupal
expose svcs
```sh
k expose deployment drupal --type=NodePort --name=drupal-service
k expose deployment drupal-mysql --name=drupal-mysql-service --port=3306
```

after edit node port drupal-service
