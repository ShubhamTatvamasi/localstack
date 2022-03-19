# localstack

Install localstack:
```bash
python3 -m pip install localstack
```

Start localstack:
```bash
docker run -d \
  -p 4566:4566 \
  -p 4571:4571 \
  --name localstack \
  localstack/localstack
```

Stop localstack:
```bash
docker rm -f localstack
```
