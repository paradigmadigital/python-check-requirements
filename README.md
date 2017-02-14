# Python Check Requirements

Check the python requirements of a project via pip


## Role Variables

* `virtualenv`        : location of the virtualenv on the remote host
* `requirements_file` : location of the requirements.txt on the remote host

If virtualenv is not set, it will perform the checks globally

## Example Playbook

```yaml
- hosts: all
  roles:
    - python-check-requirements
```

## License

GPL

## Author

jamatute@paradigmadigital.com
