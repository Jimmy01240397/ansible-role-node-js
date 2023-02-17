# Ansible Role: Node.js

Ansible role for Node.js:

* basic, opinionated install
* build tools install

## Requirements

None.

## Role variables

| var | required | default | comment |
|-----|----------|---------|---------|
| node_js_version | no | 18.x | Node.js version |

## Dependencies

None.

## Example Playbook

```yaml
- hosts: all
  become: true
  roles:
    - role: jimmy01240397.node-js
      node_js_version: 18.x
```

## License

MIT

## Author Information

None
