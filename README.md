# kubernetes_3
used for learning kubernetes

# run this to make the website go online on localhost:1337

- [ ] ensure that you built the my-app project using the method ot create the image so its locally available
    - [ ] docker build . -t kubernetes_2/node
- [ ] k create -f react-app.deployment.yaml && k create -f my-app.lb.yaml 

## to access a pod's terminal
```
k exec -it <pod name> sh
```
```
e.g. k exec -it my-app-58c75d7976-dvvzq sh
```