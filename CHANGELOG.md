## 0.5.1 (2014-06-10)

Bugfixes:

- Fix remote_process_exists? SSHKit raises SSHKit::Runner::ExecuteError on error
- Fix some cases of commands running in $HOME instead of in :app_path
- Fix starting unicorn under :unicorn_user
