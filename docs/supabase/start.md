## supabase-start

Starts the Supabase local development stack.

Requires `supabase/config.toml` to be created in your current working directory by running `supabase init`.

All service containers are started by default. You can exclude those not needed by passing in `-x` flag.

> It is recommended to have at least 7GB of RAM to start all services.

Health checks are automatically added to verify the started containers. Use `--ignore-health-check` flag to ignore these errors.
