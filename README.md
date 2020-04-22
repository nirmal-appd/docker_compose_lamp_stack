
<h3>Docker Compose Usage</h3>

<b>A repo where I tried out the docker-compose feature of docker.</b>
<br/>
So, Dockerfile is standalone features or multi-features with too much code rewrite. Again spins to a container instance only.
<br/>
Docker compose is stitching these features and making a similar machine(or a beast depends on the services you add) with much less effort(less effort with more services).
<br/>
Well effort is inversely proportional to services/features (more the services, lesser the effort, less the services just stick to a Dockerfile for temp setups)
<br/>
Now, the fun part is stitching multiple Dockerfiles (which again spins up multiple containers) to a single multi-services instance.
<br/>
Also think of code reusability of sharing these Dockerfiles across projects. Your service is not limited to this project. It is independent dockerfile so just reuse it again in another compose build.
<br/>
One step away from kubernetes or k8s.
