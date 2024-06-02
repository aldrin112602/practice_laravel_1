# Laravel Framework 11.9.2

## Usage:

## Options:
- `-h, --help`            : Display help for the given command. When no command is given, display help for the list command.    
- `-q, --quiet`           : Do not output any message.
- `-V, --version`         : Display this application version.
- `--ansi|--no-ansi`      : Force (or disable `--no-ansi`) ANSI output.
- `-n, --no-interaction`  : Do not ask any interactive questions.
- `--env[=ENV]`           : The environment the command should run under.
- `-v|vv|vvv, --verbose`  : Increase the verbosity of messages: 1 for normal output, 2 for more verbose output, and 3 for debug.

## Available Commands:

### General
- `about`                     : Display basic information about your application.
- `clear-compiled`            : Remove the compiled class file.
- `completion`                : Dump the shell completion script.
- `db`                        : Start a new database CLI session.
- `docs`                      : Access the Laravel documentation.
- `down`                      : Put the application into maintenance/demo mode.
- `env`                       : Display the current framework environment.
- `help`                      : Display help for a command.
- `inspire`                   : Display an inspiring quote.
- `list`                      : List commands.
- `migrate`                   : Run the database migrations.
- `optimize`                  : Cache framework bootstrap, configuration, and metadata to increase performance.
- `serve`                     : Serve the application on the PHP development server.
- `test`                      : Run the application tests.
- `tinker`                    : Interact with your application.
- `up`                        : Bring the application out of maintenance mode.

### Authentication
- `auth:clear-resets`         : Flush expired password reset tokens.

### Cache
- `cache:clear`               : Flush the application cache.
- `cache:forget`              : Remove an item from the cache.
- `cache:prune-stale-tags`    : Prune stale cache tags from the cache (Redis only).

### Channel
- `channel:list`              : List all registered private broadcast channels.

### Configuration
- `config:cache`              : Create a cache file for faster configuration loading.
- `config:clear`              : Remove the configuration cache file.
- `config:publish`            : Publish configuration files to your application.
- `config:show`               : Display all of the values for a given configuration file.

### Database
- `db:monitor`                : Monitor the number of connections on the specified database.
- `db:seed`                   : Seed the database with records.
- `db:show`                   : Display information about the given database.
- `db:table`                  : Display information about the given database table.
- `db:wipe`                   : Drop all tables, views, and types.

### Environment
- `env:decrypt`               : Decrypt an environment file.
- `env:encrypt`               : Encrypt an environment file.

### Event
- `event:cache`               : Discover and cache the application's events and listeners.
- `event:clear`               : Clear all cached events and listeners.
- `event:list`                : List the application's events and listeners.

### Installation
- `install:api`               : Create an API routes file and install Laravel Sanctum or Laravel Passport.
- `install:broadcasting`      : Create a broadcasting channel routes file.

### Key
- `key:generate`              : Set the application key.

### Language
- `lang:publish`              : Publish all language files that are available for customization.

### Make
- `make:cache-table`          : Create a migration for the cache database table.
- `make:cast`                 : Create a new custom Eloquent cast class.
- `make:channel`              : Create a new channel class.
- `make:class`                : Create a new class.
- `make:command`              : Create a new Artisan command.
- `make:component`            : Create a new view component class.
- `make:controller`           : Create a new controller class.
- `make:enum`                 : Create a new enum.
- `make:event`                : Create a new event class.
- `make:exception`            : Create a new custom exception class.
- `make:factory`              : Create a new model factory.
- `make:interface`            : Create a new interface.
- `make:job`                  : Create a new job class.
- `make:listener`             : Create a new event listener class.
- `make:mail`                 : Create a new email class.
- `make:middleware`           : Create a new middleware class.
- `make:migration`            : Create a new migration file.
- `make:model`                : Create a new Eloquent model class.
- `make:notification`         : Create a new notification class.
- `make:notifications-table`  : Create a migration for the notifications table.
- `make:observer`             : Create a new observer class.
- `make:policy`               : Create a new policy class.
- `make:provider`             : Create a new service provider class.
- `make:queue-batches-table`  : Create a migration for the batches database table.
- `make:queue-failed-table`   : Create a migration for the failed queue jobs database table.
- `make:queue-table`          : Create a migration for the queue jobs database table.
- `make:request`              : Create a new form request class.
- `make:resource`             : Create a new resource.
- `make:rule`                 : Create a new validation rule.
- `make:scope`                : Create a new scope class.
- `make:seeder`               : Create a new seeder class.
- `make:session-table`        : Create a migration for the session database table.
- `make:test`                 : Create a new test class.
- `make:trait`                : Create a new trait.
- `make:view`                 : Create a new view.

### Migrate
- `migrate:fresh`             : Drop all tables and re-run all migrations.
- `migrate:install`           : Create the migration repository.
- `migrate:refresh`           : Reset and re-run all migrations.
- `migrate:reset`             : Rollback all database migrations.
- `migrate:rollback`          : Rollback the last database migration.
- `migrate:status`            : Show the status of each migration.

### Model
- `model:prune`               : Prune models that are no longer needed.
- `model:show`                : Show information about an Eloquent model.

### Optimize
- `optimize:clear`            : Remove the cached bootstrap files.

### Package
- `package:discover`          : Rebuild the cached package manifest.

### Queue
- `queue:clear`               : Delete all of the jobs from the specified queue.
- `queue:failed`              : List all of the failed queue jobs.
- `queue:flush`               : Flush all of the failed queue jobs.
- `queue:forget`              : Delete a failed queue job.
- `queue:listen`              : Listen to a given queue.
- `queue:monitor`             : Monitor the size of the specified queues.
- `queue:prune-batches`       : Prune stale entries from the batches database.
- `queue:prune-failed`        : Prune stale entries from the failed jobs table.
- `queue:restart`             : Restart queue worker daemons after their current job.
- `queue:retry`               : Retry a failed queue job.
- `queue:retry-batch`         : Retry the failed jobs for a batch.
- `queue:work`                : Start processing jobs on the queue as a daemon.

### Route
- `route:cache`               : Create a route cache file for faster route registration.
- `route:clear`               : Remove the route cache file.
- `route:list`                : List all registered routes.

### Sail
- `sail:add`                  : Add a service to an existing Sail installation.
- `sail:install`              : Install Laravel Sail's default Docker Compose file.
- `sail:publish`              : Publish the Laravel Sail Docker files.

### Schedule
- `schedule:clear-cache`      : Delete the cached mutex files created by scheduler.
- `schedule:interrupt`        : Interrupt the current schedule run.
- `schedule:list`             : List all scheduled tasks.
- `schedule:run`              : Run the scheduled commands.
- `schedule:test`             : Run a scheduled command.
- `schedule:work`             : Start the schedule worker.

### Schema
- `schema:dump`               : Dump the given database schema.

### Storage
- `storage:link`              : Create the symbolic links configured for the application.
- `storage:unlink`            : Delete existing symbolic links configured for the application.

### Stub
- `stub:publish`              : Publish all stubs that are available for customization.

### Vendor
- `vendor:publish`            : Publish any publishable assets from vendor packages.

### View
- `view:cache`                : Compile all of the application's Blade templates.
- `view:clear`                : Clear all compiled view files.
