# Release Notes

## V1.1.5

The following updates were made in v1.1.5
 - Modified order of steps slightly when setting up workstation

 - Added fixes for setting run_list using Powershell

 ```
 $ knife node run_list set node1 `'role[webserver]`'
 ```
 and
 ```
 $ knife node run_list set node1 `'recipe[apache::ohai_plugin],role[webserver]`'
 ```

 - Set `log-level` at command line after initial bootstrap (log level is set using `chef-client` cookbook in next section)
 ```
 sudo chef-client -l info
 ```

 - Removed this line as it was considered a security risk and not good practice to change environment from within a node

 ```
 chef > nodes.transform(:name => "node1") {|n| n.chef_environment("dev")}
 ```
