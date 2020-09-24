# compose-issue

This is a example for issue: https://github.com/docker/compose/issues/7790


## Issue

To reproduce the problem, follow the steps below:

1. Run `bin/start`
2. **Problem:** Error caused by `deploy.resources.reservations.cpus` validation
3. Comment property `deploy.resources.reservations.cpus` in `docker-compose.yml` (line 17)
3. Run again `bin/start`
4. OK


## License

MIT © [Thiago Lagden](https://github.com/lagden)
