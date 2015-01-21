# plushu-redis-service

Plushu service module for Redis

## Usage

(assuming a Plushu setup with the `apps`, `services`, `addons`, and `app-long-opt` plugins installed)

```bash
plushu services:install redis
plushu apps:create example
plushu --app=example addons:add redis
```
