# Chef Cookbook to disable unnecessary services

## Usage

in the attribute `disableservices` define list of service names which you want to disable.

## Examples

in Vagrantfile

```ruby
chef.json = {
  :disableservices => %w{
    ip6tables
    lvm2-monitor
}}
```

