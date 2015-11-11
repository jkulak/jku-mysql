jku-mysql Cookbook
=====================
Wrapper cookbook for mysql community cookbook.

Requirements
------------

- `mysql2_chef_gem` - for installing mysql2 gem
- `mysql` - Community mysql cookbok
- `database` - Community database cookbok


Attributes
----------
TODO: List your cookbook attributes here.

e.g.
#### jku-mysql::default
<table>
  <tr>
    <th>Key</th>
    <th>Type</th>
    <th>Description</th>
    <th>Default</th>
  </tr>
  <tr>
    <td><tt>['jku-mysql']['bacon']</tt></td>
    <td>Boolean</td>
    <td>whether to include bacon</td>
    <td><tt>true</tt></td>
  </tr>
</table>

Usage
-----
#### jku-mysql::default

Just include `jku-mysql` in your node's `run_list`:

```json
{
  "name":"my_node",
  "run_list": [
    "recipe[jku-mysql]"
  ]
}
```

Contributing
------------

1. Fork the repository on Github
2. Create a named feature branch (like `add_component_x`)
3. Write your change
4. Write tests for your change (if applicable)
5. Run the tests, ensuring they all pass
6. Submit a Pull Request using Github

License and Authors
-------------------
Authors: Jakub Kułak <jakub.kulak@gmail.com>
