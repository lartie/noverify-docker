# NoVerify in Docker

## What is NoVerify?

Please see [https://github.com/VKCOM/noverify](https://github.com/VKCOM/noverify)

## How to use?

```bash
docker run -v /path/to/your/project/root:/project -v /path/to/your/project/output:/tmp/noverify artemy/noverify:0.1
```

## How to change noverify command?

```bash
docker run -e ENTRYPOINT_CMD="noverify -stubs-dir=/root/phpstorm-stubs -cache-dir=$HOME/tmp/cache/noverify /app" -v /path/to/your/project/root:/project -v /path/to/your/project/output:/tmp/noverify artemy/noverify:0.1
```

## License

The MIT License (MIT). Please see [License File](LICENSE.md) for more information.
