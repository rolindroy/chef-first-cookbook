# apache-lamp Cookbook

Sample Cookbook for create apache Vhost

### Platforms

- Linux/Ubuntu 14.04

### Chef

- Chef 12.0 or later

### apache-lamp::default

<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['apache-lamp']['bacon']</tt></td>
    <td>Boolean</td>
    <td>whether to include bacon</td>
    <td><tt>true</tt></td>
  </tr>
</table>

## Usage

### apache-lamp::default

TODO: Write usage instructions for each cookbook.

e.g.
Just include `apache-lamp` in your node's `run_list`:

```json
{
  "name":"my_node",
  "run_list": [
    "recipe[apache-lamp]"
  ]
}
```

## Contributing

TODO: (optional) If this is a public cookbook, detail the process for contributing. If this is a private cookbook, remove this section.

e.g.
1. Fork the repository on Github
2. Create a named feature branch (like `add_component_x`)
3. Write your change
4. Write tests for your change (if applicable)
5. Run the tests, ensuring they all pass
6. Submit a Pull Request using Github

## License and Authors

Authors: Rolind Roy  <rolind.roy@gmail.com>

