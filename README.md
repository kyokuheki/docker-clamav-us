# docker-clamav-us
Unusable security is not security! This is a dockerized antivirus to sham and comply with unusable security rules.

## How to build
```
git clone https://github.com/kyokuheki/docker-clamav-us.git
cd docker-clamav-us
docker build -t docker-clamav-us --no-cache .
```

## How to run
Run clamav
```
docker run -it -v $PWD:/suspects --rm docker-clamav-us
```

Run bash
```
docker run --entrypoint bash -it -v $PWD:/suspects --rm docker-clamav-us
```
