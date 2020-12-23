## patch nginx
you need to add following to your nginx deployment (helm):

```helm
tcp:
  '4443': 'jitsi/jvb:4443'
```
with jitsi being the namespace, you deploy the app in.