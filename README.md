Most of the code here is currently from the demo here https://docs.microsoft.com/en-us/dotnet/csharp/tutorials/microservices

The only work done so far was to figure out a way to get docker to play nice on OS X by using docker-compose instead of the simple docker example described at that url.

To run download repo localling and run
```
$ docker-compose build
$ docker-compose up
```

Then navigate to `localhost:8000/?lat=45.523062&long=122.676482` or `<ip>:8000/?lat=45.523062&long=122.676482`