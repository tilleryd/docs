# _flyctl machine stop_

Stop a Fly machine

### About

Stop a Fly machine

### Usage
~~~
flyctl machine stop <id> [flags]
~~~

### Options

~~~
  -a, --app string      App name to operate on
  -c, --config string   Path to an app config file or directory containing one (default "./fly.toml")
  -h, --help            help for stop
  -s, --signal string   Signal to stop the machine with (default: SIGINT)
      --time int        Seconds to wait before killing the machine
~~~

### Global Options

~~~
  -t, --access-token string   Fly API Access Token
  -j, --json                  json output
      --verbose               verbose output
~~~

### See Also

* [flyctl machine](/docs/flyctl/machine/)	 - Commands that manage machines

