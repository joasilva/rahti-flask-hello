# Demo: Flask hello-world in Rahti

Create new application with source-to-image tools:
```bash
oc new-app https://github.com/cscfi/rahti-flask-hello --name="course-flask-demo"
```

Expose the application at "http://course-flask-demo.rahtiapp.fi"
```bash
oc expose svc/course-flask-demo --hostname="course-flask-demo.rahtiapp.fi"
```
